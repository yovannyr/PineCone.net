# PineCone.net
# Integrate Anything with Everything on your favorite backend engine.

One of the biggest challenges today’s businesses face is to create business processes that integrate with different moving parts running on different platforms.

Microsoft has WWF and BizTalk server. However, they are limited to Windows platform and can only use SQL server as backend engine.

Amazon’s Simple Workflow Service (SWF) provides a seamless orchestration engine. However, you need to write your own code that interacts with it to create the workflow.

PineCone.net aims to solve the limitations listed above. Key features are :-
1. This is a framework written in .NET Core and hence can be deployed on different operating systems as well as Docker containers.
2. It supports JSON data.
3. Workflows can be created as simple JSON objects.
4. It supports synchronous and asynchronous workflows.
5. It supports creating your own backend engines and hooking the framework to it.
6. Your solution can either be in the cloud or on-premise or a combination of both.
7. Currently it is shipped with AWS engine (SWF and DynamoDB) and MySQL engine.
8. Plans to support other backends like SQL Server, Cassandra etc.
