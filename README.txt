how to setup and run the app:

unzip the folder and make sure files are in the same folder. Make sure mime-types module is installed. Run node server.js on PoweShell or Command Prompt and make sure you recieve the message “server is listening to port 2406”. In a webpage URL type “localhost:2406” and press enter. 

________________________________________________
what OS I developed under: 

Windows OS

________________________________________________
The browser I tested my code with:

Google Chrome

================================================
How I proceeded in completing the assignment:

1) I first created server js file that runs on the 2406 port - named server.js
- server on the net usually uses http or https ,
-For http we usually need to wait for server --> listen to the port, get post (five s, put , delete, head and ...),
Path is URL-- response serves data and etc.
For creating server, we should state which protocol we use
based on the protocol we create server
create requeshandler for server
request handler will have two argument -> req to and res from
with cosole.log req.method --> we can get method
with req.url we can get url of url of req
in the prevoius file we write res.writeHead
res.write --> not necessary
before server and file we write hello world.
res.end('rather than hello world we should write sth')
res.serverWriteHead(sth)
res(200 --> Code, {'content-type':'text/plain'}
So here we need to check the file is existwith existSysn and its directory StatsSync
if every thin is pk we change code and data
res.end(data)
res.writeHead(code,{'content-type': mime.lookup(filename) || 'text/html'}); 
404 and idex
then createurl obj
2) To create public folder in this folder I must have had :
-favicon
-404 page
- Css - Style file
- index Page
3)Layout index page as assigenemt show, 404 and external css file.
4)Create folder name Hero and jason files inside that
