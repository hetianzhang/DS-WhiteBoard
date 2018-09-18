"# DS-WhiteBoard" 
Second Project of Distributed System in The University of Melbourne.

1. Introduction
Shared whiteboards allow people to draw on a canvas simultaneously. It enables multi clients to present their
ideas and communicate with each other in real time. As a team project, we develop a RMI-architecture-based
distributed shared whiteboard in Java. It includes management part for the whiteboard room administrator,
GUI part for painting functions, and chat part for broadcasting messages based on Java Remote Method
Invocation (Java RMI), which is the object-oriented equivalent of remote procedure calls (RPC). For the
GUI part, we implement application in Java Swing and canvas in Graphics2D. Furthermore, by designing
the remote interfaces and remote objects, we implement the client to server networking communication and
remote function invocations. With regard to the synchronous updating for painting and chat among multi
clients, we using RMI client-side callback functions.

The functions of RMI-based distributed shared whiteboard are as follows:

1) A start window for server to set RMI registry ip address and port;

2) A start window for client to choose the user level (manager or user), set client id, username, whiteboard service ip address and port, and the whiteboard room name to create or enter;

3) Allow room manager to clear the canvas, open a new file, save current canvas, close the room, manage
  current room clients list, and the new room entrance requests.
  
4) Allow multiple users to draw simultaneously on a canvas including: drawing freehand, line, rectangle,
  circle, oval, and polygon with different width, color and filling style; eraser with different size; type
  Parallel or vertical words on the canvas.
  
5) Show information of current clients in the room and who is current editing the canvas;
	
6) Allow clients in the same whiteboard room to chat.
