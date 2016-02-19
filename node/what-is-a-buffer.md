#What is a buffer?

A buffer is just data sitting in memory. If the file is large, and many people are using the application, tons of memory will be used. Buffers are a way to send/receive the data in smaller chunks for more efficient memory usage.

### Characteristics:
+ Each buffer corresponds to a raw chunk of memory allocated outside of V8
+ Buffers are not resizable like arrays
+ Designed to handle raw binary data

> 2.17.16
