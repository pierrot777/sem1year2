# Networking Week 4 – Web, Email, DNS

## HTTP (Web Protocol)

HTTP = protocol used for the Web.

Client = browser  
Server = web server

Flow:
1 client sends HTTP request
2 server sends HTTP response

HTTP uses:
TCP
Port 80

HTTP is **stateless**
→ server does not remember past requests.

---

## HTTP Connections

Non-persistent HTTP
- new TCP connection per object

Persistent HTTP
- one connection for many objects
- faster (default today)

---

## HTTP Messages

Request message:
GET /index.html HTTP/1.1

Response message:
HTTP/1.1 200 OK

Common status codes:
200 → success  
301 → moved permanently  
404 → not found

---

## Cookies
Cookies store **user information** on the browser.

Used for:
- login sessions
- shopping carts
- personalization

---

## Email System

3 main components:

User agent
(email app like Gmail or Outlook)

Mail server
(stores emails)

Protocols:
SMTP → send mail  
POP3 / IMAP → retrieve mail

SMTP uses **TCP port 25**.

---

## DNS (Domain Name System)

DNS translates:

domain name → IP address

Example:
google.com → 142.250.x.x

DNS structure is **hierarchical**:

Root servers  
↓  
Top level domain (.com, .au)  
↓  
Authoritative servers