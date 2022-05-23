## HLog - Health Logs

A system that makes health blogs available to the users. The main focus of this project was to create a FAULT-TOLERANT Distributed System. There are 5 container nodes and only one of these nodes interact with the users. I call it the Leader node. The system is built in such a way that in case the leader node fails, the other 4 nodes conduct an election and elect a new leader. This guarantees streamless, continuous and reliable data supply to the user. I have made use of the RAFT consensus algorithm in order to achieve the goal of this project.<br/>
Here is a short video of the application, which demonstrates how the 4 nodes interact with each other, help in message storage and fault tolerance.<br/>
