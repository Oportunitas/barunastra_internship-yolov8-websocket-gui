<<<<<<< HEAD
# barunastra-yolov8-websocket-gui
A simple WebSocket Graphical User Interface, used to transmit real-time ASV YOLOv8 vision inference data to a client
- `asv-server-side`: Autonomous Surface Vehicle server-side code. Will be contained in ASV's Mini PC. Sends inferred images (images labeled with bounding boxes)
- `cpc-client-side`: Control PC client-side code. Will display the inferred images sent by ASV


## quick setup (sequential)
- (optional) set up IP address and port in which the WebSocket connection will run through. It is modifiable in `publisher.py` on server side, and in `displayer.py` on client side
- (optional) set up video inference preferences. It is modifiable in `asv-server-side/yolov8-object-recognition/yolov8_mylib.py`
- `link/mount camera/webcam` to server's os
- run `publisher.py` on the server computer
- run `displayer.py` on the client computer
- terminate program by using `ctrl+c` on both code, sequence-independent.
=======
# barunastra-yolov8-websocket-gui
A simple WebSocket Graphical User Interface, used to transmit real-time ASV YOLOv8 vision inference data to a client
- `asv-server-side`: Autonomous Surface Vehicle server-side code. Will be contained in ASV's Mini PC. Sends inferred images (images labeled with bounding boxes)
- `cpc-client-side`: Control PC client-side code. Will display the inferred images sent by ASV


## quick setup (sequential)
- (optional) set up IP address and port in which the WebSocket connection will run through. It is modifiable in `publisher.py` on server side, and in `displayer.py` on client side
- (optional) set up video inference preferences. It is modifiable in `asv-server-side/yolov8-object-recognition/yolov8_mylib.py`
- `link/mount camera/webcam` to server's os
- run `publisher.py` on the server computer
- run `displayer.py` on the client computer
- terminate program by using `ctrl+c` on both code, sequence-independent.
>>>>>>> c9556306391b7ee450ce0db69384df37c899f0a7
