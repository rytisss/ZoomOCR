# Web server
Formed results from application can be sent to local or remote server. Application is using secured [SocketIO](https://socket.io/) protocal which works as client. 


## Remote server
Quite a 'straight-forward' approach. The indicated regions (in the following image) should be filled. Press '**Connect**' to connect to the server. '**Copy Address**' copies the formed server address to the clipboard. If '**Send**' is checked, the updates (regonitions) will be send to the server and paused otherwise.  
  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/remote_server.png"/></kbd> 
  
## Local server
Local server mode can be access through the radio button:  
  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/server.png"/></kbd>  
  
The local server will be called on another application:  
  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/local_server.png"/></kbd>   
  
Server will be launched on the **127.0.0.1**, port **5000** and application will instantly connect to the server:  
  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/local_server_app.png"/></kbd>   
  
The results from web server can be access as it is shown in the picture:  
  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/server_getter_local.png"/></kbd>   
