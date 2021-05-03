# starcoin
Star coin is an opensource proof of work based cryptocurrency. A fun project.

### To create a simple blockchain run starcoin.py file.
It will run on port - `127.0.0.1:5000`
You can mine blocks and increase the size of the blockchain just by sending a request through PostMan.

### To test Peer to Peer netowrk and understand nodes, you can run starcoin_node_5001, starcoin_node_5002, starcoin_node_5003.
These should run on port - `127.0.0.1:5001`, `127.0.0.1:5002`, `127.0.0.1:5003`. 
You can send separate requests on each node through postman and try to alter the details on one node, which will be overwritten by the consensus netowrk(also know an 51% attack).
