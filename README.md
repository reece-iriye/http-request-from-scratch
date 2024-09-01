## Building HTTP Protocol from Scratch with Go


I am building a cURL-like HTTP Protocol from Scratch with Go to GET a better understanding about how networking, TCP, and HTTP work on a lower level. I am doing this in Go, because it's a great fast language with simple syntax that I think can be leveraged extremely well in this scenario—particularly Go-routines and structural typing.

### Learning Sources

I am using RFCs (Request for Comments) that have the original text about how th . Particularly, these are the versions I am using:

- [RFC 793: Transmission Control Protocol](https://www.ietf.org/rfc/rfc793.txt)
- [RFC 7230: Hypertext Transfer Protocol (HTTP/1.1): Message Syntax and Routing](https://datatracker.ietf.org/doc/html/rfc7230)
- [RFC 7231: Hypertext Transfer Protocol (HTTP/1.1): Semantics and Content](https://datatracker.ietf.org/doc/html/rfc7231)
- [RFC 7232: Hypertext Transfer Protocol (HTTP/1.1): Conditional Requests](https://datatracker.ietf.org/doc/html/rfc7232)
- [RFC 7233: Hypertext Transfer Protocol (HTTP/1.1): Range Requests](https://datatracker.ietf.org/doc/html/rfc7233)
- [RFC 7234: Hypertext Transfer Protocol (HTTP/1.1): Caching](https://datatracker.ietf.org/doc/html/rfc7234)
- [RFC 7235: Hypertext Transfer Protocol (HTTP/1.1): Authentication](https://datatracker.ietf.org/doc/html/rfc7235)
