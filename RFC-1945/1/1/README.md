# 1.1 목적

https://datatracker.ietf.org/doc/html/rfc1945#section-1.1

```
The Hypertext Transfer Protocol (HTTP) is an application-level
   protocol with the lightness and speed necessary for distributed,
   collaborative, hypermedia information systems. HTTP has been in use
   by the World-Wide Web global information initiative since 1990. This
   specification reflects common usage of the protocol referred too as
   "HTTP/1.0". This specification describes the features that seem to be
   consistently implemented in most HTTP/1.0 clients and servers. The
   specification is split into two sections. Those features of HTTP for
   which implementations are usually consistent are described in the
   main body of this document. Those features which have few or
   inconsistent implementations are listed in Appendix D.
```
Hypertext Trensfer Protocol(HTTP)은 하이퍼미디어 시스템을 위해 고안된 가볍고 빠른 application-level의 protocol입니다. HTTP는 1990년의 global information initative인 World-Wide Web에 사용되었습니다. 이 명세는 “HTTP/1.0”의 일반적인 사용을 반영합니다. 이 명세는 cliet와 server에서 일관적으로 구현되는 HTTP/1.0의 기능을 설명합니다. 이 명세는 2가지의 구간으로 나뉩니다. 문서의 분문이 되는 HTTP의 일관성을 가지는 대부분의 기능의 구현들과, 부록에 나열된 일관성을 가지지 않는 기능의 구현들입니다.

```
Practical information systems require more functionality than simple
   retrieval, including search, front-end update, and annotation. HTTP
   allows an open-ended set of methods to be used to indicate the
   purpose of a request. It builds on the discipline of reference
   provided by the Uniform Resource Identifier (URI) [2], as a location
   (URL) [4] or name (URN) [16], for indicating the resource on which a
   method is to be applied. Messages are passed in a format similar to
   that used by Internet Mail [7] and the Multipurpose Internet Mail
   Extensions (MIME) [5].
```

실용적인 정보 시스템은 검색, front-end 업데이트 및 주석등 단순하지 않은 많은 기능이 필요합니다. HTTP는 개방적으로 요청의 method를 설정하여 목적을 나타내는 것을 허용합니다. 이는 URI, URL 또는 URN의 규율로 표현된 자원의 사용 방법을 나타냅니다. 이러한 Message들은 Internet Mail과 Multipurpose Internet Mail Extensions(MINE)의 형태와 비슷하게 전달됩니다.

```
HTTP is also used as a generic protocol for communication between
   user agents and proxies/gateways to other Internet protocols, such as
   SMTP [12], NNTP [11], FTP [14], Gopher [1], and WAIS [8], allowing
   basic hypermedia access to resources available from diverse
   applications and simplifying the implementation of user agents.
```

HTTP는 또한 다른 Internet protocol의 proxies/gateway와 user agent 사이의 의사소통을 위한 일반적인 protocol로 사용됩니다. SMTP, NNTP, FTP, Gopher와 WAIS같은 기본적인 하이퍼미디어 자원 접근의 대한 다양한 application들과 간단한 user agent구현에 사용되었습니다.