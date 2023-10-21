# guvi-1st-assignment
1)  HTTP 1.1 Protocol
• It was released in 1997.
• It uses text based commands for HTTP requests.
• It added many performance enhancements e.g. caching, request pipelining, keepalive connections, transfer encoding, byte range requests etc.
• It can load one requests at a time. Hence one request per one TCP connection is possible.
HTTP 2 Protocol
• It was released in Feb. 2015 by IETF.
• It is binary and not textual.
• It is fully multiplexed.
• It interleaves multiple requests/responses in parallel without blocking on anyone.
• It uses single TCP connection to deliver multiple requests/responses (in parallel).


2)  Objects, in JavaScript, is it’s most important data-type and forms the building blocks for modern JavaScript.
  These objects are quite different from JavaScript’s primitive data-types(Number, String, Boolean, null, undefined and symbol) in the sense that while these primitive data-types all store a single value each (depending on their types).

Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
An object, is a reference data type. Variables that are assigned a reference value are given a reference or a pointer to that value. 
That reference or pointer points to the location in memory where the object is stored. The variables don’t actually store the value.

3)  IP ADDRESS AND MAC ADDRESS:
 The IP address of a device mainly helps in identifying the connection of a network (using which the device is connecting to the network). The MAC Address, on the other hand, ensures the computer device’s physical location. It helps us to identify a given device on the available network uniquely.
HTTP REQUEST METHODS:

The GET method requests a representation of the specified resource. Requests using GET should only retrieve data.

HEAD
The HEAD method asks for a response identical to a GET request, but without the response body.

POST
The POST method submits an entity to the specified resource, often causing a change in state or side effects on the server.

PUT
The PUT method replaces all current representations of the target resource with the request payload.

DELETE
The DELETE method deletes the specified resource.

CONNECT
The CONNECT method establishes a tunnel to the server identified by the target resource.

OPTIONS
The OPTIONS method describes the communication options for the target resource.

TRACE
The TRACE method performs a message loop-back test along the path to the target resource.

PATCH
The PATCH method applies partial modifications to a resource.
