# Day-1-task
Difference between HTTP/1.1 and HTTP/2 are:
   HTTP/1.1
a : It works on the textual format
b : There is head of line blocking that blocks
    all the requests behind it until it doesn’t get its all resources.
c : It uses requests resource Inlining for use getting multiple pages
d : It compresses data by itself

  HTTP/2
a : It works on the binary protocol 
b : It allows multiplexing so one TCP connection is 
    required for multiple requests.
c : it uses PUSH frame by server that collects all 
    multiple pages 
d : it uses HPACK for data compression
