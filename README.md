
```
python -m rtclite.app.sip.server -d -t ws -l 0.0.0.0:5080 -r localhost
```

Alternatively, to start the server supporting both WebSocket and UDP transport use the following command.
```
python -m rtclite.app.sip.server -d -t ws -l 0.0.0.0:5080 -t udp -l 0.0.0.0:5060
```
