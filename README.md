# neo4j-debug-timeline
A page that displays Neo4j debug log events on a timeline
![image](https://user-images.githubusercontent.com/45878183/153859228-6f94895a-a346-4d94-b40f-ca96bda93846.png)


Supported events :
* DBMS startup
* database backups
* Stop-the-world  GC pauses (>1s)
* Causal cluster : leader changes
* ERRORs
* checkpoints
* custom regex

Multiple files can be loaded simultaneously. Events can be grouped into separate swimlanes, either by database or by input file. If grouping by database, dbms-level events are displayed in a separate "dbms" swimlane.

Public endpoint : https://s3.eu-west-2.amazonaws.com/david.pecollet.public/neo4j-debug-timeline/timeline.html
