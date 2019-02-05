# StarkHub

#### How it works : <br />
     1. A central server is used for user authentication . 
     2. Central server sends information of newly connected nodes to each already connected nodes .
     3. Nodes can contact each other with search queries (query for searching a video).
     4. Source node then start streaming of video and destination node will enjoy the video .
     5. Every node is holding its own database (information about path of videos).
     6. RTSP protocol is used for streaming .
     7. Each node can maintain number of channels, upload videos to channels, can track subscribers.
     8. Each user can also like videos, subscribe to channels .
      
#### Technology used : 
     1. JAVA Application build on NETBEANS .
     2. Central server is concurrent server(can handle multiple connections simultaneously) .
     3. MySQL database at central server to store user information .
     4. MySQL database at each node to maintain information about its videos .
     5. VLCJ library to do streaming using VLC media player .
     
