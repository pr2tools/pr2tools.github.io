# pr2tools.github.io
###Server and Modified Platform Racing 2 Client for playing while PR2-servers are offline

Here is a simple server for Platform Racing 2. It runs local and allows to play PR2 alone. 
You can play all levels as long as pr2hub.com is available and also do other things like reading and sending PMs.
LevelEditor is disabled, needs more hacking do get it working (game freezes when it tries to load it).

Visit pr2tools.github.io, download and run the server-binary (PR2SRV.exe) and finally log in.
It will only work with the modified PR2 client which works with invalid packet hashes. It could work with the original PR2 client but I refused to implement the hash algorithm to prevent abuse by script kiddies. 

There is an alternative advanced way to  to access (only) the LevelEditor. You need to load the original PR2 client and modify the request to https://pr2hub.com/files/server_status_2.txt to do this.
Install e.g. [Charles Web Debugging Proxy](http://www.charlesproxy.com/), configure it [to intercept HTTPS](https://www.youtube.com/watch?v=x-N2XYUnOFY) and use the "map local" option. You need to map to a copy of server_status_2.txt where you changed the Derron IP to 127.0.0.1. Press '1' to run the server with precomputed hashes.

Multi-player support could be added but would require more work.
