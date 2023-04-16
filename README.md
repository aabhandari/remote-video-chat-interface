# Patient-to-health Care Providers: Remote Video Chat Interface

Design URL: https://aashishbhandari201.wixsite.com/peaceremote

A system/interface that will be able to connect patients to any available health care providers who have access to the platform, the health care providers will be able to provide consultation and recommendations to the patients. Each Patient will have their unique identifying ID that will be shared to the few available staff at the hospitals who will be able to perform the rapid diagnostics if necessary or give medication according to the health care providers recommendation. This will help alleviate the workload load of the remote based health practitioners.

The video chat app is made using a technology called WebRTC (Web Real-Time Communication) in which we can communicate in real-time from web browsers directly. WebRTC, simply, allows direct communication between browsers. In conventional methods, clients send requests, and the server responds. There may be some delay if there are multiple clients which may affect the video or voice call experience. But with WebRTC, clients can directly communicate with each other without the actual server. A signalling server is the one which takes the connection details and allows clients to connect.

Frameworks/Libraries/Technologies used are:
• Express - secure local server to host HTML, CSS and JavaScript files\
• Ejs - templating language\
• Socket.io - allows to communicate with actual server easily\
• Uuid - unique user IDs\
• Peerjs - handle ID connection, creates secure PeerJS server that handles exchange of information
