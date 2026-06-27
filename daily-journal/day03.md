# Day 3 - HTTP, APIs & Postman

## Objectives

* Understand how communication on the web works.
* Learn the request/response lifecycle.
* Learn the fundamentals of HTTP and REST APIs.
* Use Postman to interact with a real API.

---

## What I Accomplished

* Learned how browsers communicate with servers over HTTP.
* Learned the purpose of DNS and how domain names are translated into IP addresses.
* Learned the difference between HTTP and HTTPS.
* Learned the purpose of TCP and the TLS handshake.
* Learned what clients, servers, APIs, and JSON are.
* Used Postman to make my first HTTP GET request.
* Used Postman to make my first HTTP POST request.
* Learned the purpose of the five most common HTTP methods: GET, POST, PUT, PATCH, and DELETE.

---

## What I Learned

One of the biggest things I learned today was the complete lifecycle of a web request.

When a user enters a URL into a browser, the browser first checks its DNS cache before performing a DNS lookup if necessary. DNS translates the domain name into an IP address so the browser knows where to connect.

The browser then establishes a reliable connection using TCP. If the website uses HTTPS, a TLS handshake occurs to verify the server's identity and establish an encrypted connection.

Once the connection is established, the browser sends an HTTP request to the server. The server processes the request and returns an HTTP response, often containing HTML, JSON, or another type of data.

If HTML is returned, the browser discovers additional resources such as CSS, JavaScript, images, and fonts, then makes additional HTTP requests for each of them before rendering the page.

I also learned that JSON is simply a language-independent way of representing structured data, allowing programs written in different languages to communicate with each other.

---

## Challenges

* Understanding the differences between PUT and PATCH.
* Understanding the sequence of networking protocols before an HTTP request is sent.
* Keeping track of where each protocol fits into the request lifecycle.

---

## Wins

* Successfully explained the complete request lifecycle without looking at my notes.
* Used Postman to send both GET and POST requests.
* Correctly predicted the purpose of PUT, PATCH, and DELETE before learning their official definitions.
* Continued strengthening my understanding of networking fundamentals.

---

## Engineering Insight

HTTP isn't just something browsers use—it's a standardized way for two programs to communicate. Once I understood that, APIs stopped feeling mysterious and started feeling like conversations between software.

---

## Tomorrow's Goal

* Build my first FastAPI application.
* Create my first API endpoint.
* Return JSON from my own server.
* Test my own API using Postman.
