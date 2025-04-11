This project includes the improvement in the consensus algorithm.

Each python file consists of the code of the Blockchain with modidfied consensus.
Run each node file in 4-separate terminals which behave like 4 nodes in the blockchain network.

Run python/python3 node1.py file in terminal 1
Run python/python3 node1.py file in terminal 2
Run python/python3 node1.py file in terminal 3
Run python/python3 node1.py file in terminal 4

Each terminal will show the actions taken by blockchain node such as create block, add block, remove attacker's chain to introduce fairness.

To view the blockchain instance of each node, in the address bar of browser type as follows:
http://127.0.0.1:5000/getBlockchain  --> for node-1 blockchain instance (Attacker Node - hashing power is increased by sleeping the other nodes for some random time interval) 
http://127.0.0.1:5000/getBlockchain  --> for node-2 blockchain instance
http://127.0.0.1:5000/getBlockchain  --> for node-3 blockchain instance
http://127.0.0.1:5000/getBlockchain  --> for node-4 blockchain instance

Expected Output:
If any blockchain is trying to add longer blocchains that is out of order with the normal rate of addition. It not only get removed but also it is replaced by the
most genuine longest chain.
