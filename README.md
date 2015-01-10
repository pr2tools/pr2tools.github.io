# pr2tools.github.io
###Server and Modified Platform Racing 2 Client for playing while PR2-servers are offline

Here is a simple server for Platform Racing 2. It runs local and allows to play PR2 alone. 
You can play all levels as long as pr2hub.com is available and also do other things like reading and sending PMs.
LevelEditor is disabled, needs more hacking do get it working (game freezes when it tries to load it).

Visit pr2tools.github.io, download and run the server-binary (PR2SRVv2.exe) and finally log in.
It will only work with the modified PR2 client which works with invalid packet hashes. It could work with the original PR2 client but I refused to implement the hash algorithm to prevent abuse by script kiddies. 

There is an alternative advanced way to access (only) the LevelEditor:
1. Install [Switcheroo Redirector Google Chrome Extension](https://chrome.google.com/webstore/detail/switcheroo-redirector/cnmciclhnghalnpfhhleggldniplelbg/)
2. Open Redirector and type `https://pr2hub.com/files/server_status_2.txt` in the FROM-field and `https://pr2tools.github.io/server_status_2.txt` in the TO-field.
3. Load PR2 on kongregate
4. Start PR2 local server and hit '1'
You will not be able to play levels on kongregate, to play the levels use the pr2tools client.

Multi-player support could be added but would require more work.
