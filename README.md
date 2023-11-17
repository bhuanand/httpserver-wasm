Simple HTTP Server for serving wasm files
---

Extends python3's `http.server.SimpleHTTPRequestHandler` to add custom headers and mimetypes required to
serve the wasm files.

By default server listens at port 8080
```
~/Downloads  ➟ python3 server.py
HTTP Server listening at port 8080 ..

```

Change the port by setting env `PORT`
```
~/Downloads  ➟ PORT=9090 python3 server.py
HTTP Server listening at port 9090 ..

```