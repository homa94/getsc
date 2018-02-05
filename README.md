## GETSC Version 1.0

##### Get Status Code is a python script it can found directories of websites, From wordlist or automatically generating numbers.
##### If the user use the script without -s/--scode then the script will bring All the status code except 404.

#### Author:

```
Homa Hamza https://twitter.com/aokhh
```

### Examples:

```
python3 getsc.py -u http://www.example.com/
python3 getsc.py -u example.com
python3 getsc.py -u https://www.example.com/ -s 200
python3 getsc.py -u example.com -w wordlist.txt
python3 getsc.py -u example.com -w wordlist.txt -s 403
```

### Status Code:

##### 100 Continue 
##### 101 Switching Protocols
##### 200 OK 
##### 201 Created 202 Accepted
##### 203 Non-Authoritative Information
##### 204 No Content
##### 205 Reset Content
##### 206 Partial Content
##### 300 Multiple Choices
##### 301 Moved Permanently
##### 302 Found
##### 303 See Other
##### 304 Not Modified
##### 305 Use Proxy 
##### 306 Unused
##### 307 Temporary Redirect 
##### 400 Bad Request
##### 401 Unauthorized
##### 402 Payment Required
##### 403 Forbidden
##### 404 Not Found
##### 405 Method Not Allowed
##### 406 Not Acceptable
##### 407 Proxy Authentication Required
##### 408 Request Timeout
##### 409 Conflict
##### 410 Gone
##### 411 Length Required
##### 412 Precondition Failed
##### 413 Request Entity Too Large
##### 414 Request-URI Too Long
##### 415 Unsupported Media Type
##### 416 Requested Range Not Satisfiable
##### 417 Expectation Failed
##### 500 Internal Server Error
##### 501 Not Implemented
##### 502 Bad Gateway
##### 503 Service Unavailable 
##### 504 Gateway Timeout 
##### 505 HTTP Version Not Supported

#### For more information about status code:

```
https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html
```
