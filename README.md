# Directions/discussion:

**Unzip Project2.zip**

Navigate to source code

`cd /Project2_RTP/src`

Compile code

`javac Client.java`

Run server with listening port as argument

`java Server 12200`

Run client with listening server, port, and movie path as arguments

`java Client localhost 12200 ../movie.Mjpeg`

Click the Setup button on the window, then click Play to see streaming video

An example trace is in wireshark_trace.pcapng.gz. 

"wireshark_statistics.png" shows the packet loss and streaming rate.

Packet loss %:
According to the Wireshark "RTP Streams" window, packet loss was 0% when 
streaming from and to a local machine. 

Streaming rate: 
The "UDP" tab within the Conversations window shows that the streaming rate
was 654k bits/s. 
