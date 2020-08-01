# Sahil-Coin
To be installed:
# Flask==0.12.2: pip install Flask==0.12.2
# Postman HTTP Client: https://www.getpostman.com/
# requests==2.18.4: pip install requests==2.18.4
 I have created Three nodes and ran all the Three nodes on different ports of my localhost 
 whenever a new transaction is added it has to be mined by any node and rest of the nodes have to run replace_chain method to get the copy of the longest chain
 
 The format of transaction json code which has to be added in postman to run the add_transaction method ->which is a post method
 {
    "sender": "",
    "receiver": "",
    "amount": 
}

The nodes
{
    "nodes": ["http://127.0.0.1:5001",
              "http://127.0.0.1:5002",
              "http://127.0.0.1:5003"]
}
you have to add this json in postman of each node except the nodes own addresss while adding nodes to blockchain using add_node method

Note** You can replicate the same code and create many different nodes by just changing the keys.
In this project public key is basically the name 
