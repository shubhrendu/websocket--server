Splitted Zip Files for Websocket - Server

Run this command to merge them: cat SERVERCHUNK* > server.zip

Follow below steps to run the server application:

1. Extract the generated server.zip file
2. Executing "Websocket - Server.exe" file from inside win64 will launch Websocket server application.

Test Client-server connectivity:
1. Launched application will display the websocket server address like ws://192.168.137.1:3001
2. If server address is not displayed on application launch (default port: 3001 must already be in use and server will get started at different port)
3. Then right click on the application -> inspect background page -> console, and copy server address from console and use it in websoscket - client application to connect with it
4. Send/receive message across client and server.
5. Verify the message received at server in console ie. right click on the application -> inspect background page -> console
