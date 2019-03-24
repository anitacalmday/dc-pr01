# dc-pr01
 Key-Value Storage System
 
The task is to create a simple web and proxy server that stores and retrieves key-value pairs using socket programming interface. 
The server only permits commands such as GET PUT and DUMP in the request field followed by the key and value stored. 

# Functionality
* GET returns the value of the key specified
    * When the client makes a GET request, this request is passed through the proxy server. 
    * If the server has made the same request using the same key, the key-value should be retrieved from the proxy server instead of the server.
* PUT stores the key and a specified value on the server
* DUMP lists all of the key value pairs contained in the server.

#How To Run My Program: 

* Install telnet
* Ensure that your server/proxy server program is running. 
* Open a terminal and connect to the client using the command  telnet <ip address> <port #>  
    * I used telnet localhost 7777

Most of this description is taken from the project description that can be found @ https://docs.google.com/document/d/1l3hzaVQQZ8AUewcdKvqq-UvOLvrWtecKmb6nKbK_2Sw/edit
