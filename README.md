##docker-websockify

Docker Image for Websockify WebSocket to TCP proxy/bridge

For more information on Websockify, see the official project page: https://github.com/kanaka/websockify/

### Example
```shell
# Expose local port 5900 through WebSocket on port 8080
docker run --net=host -u nobody siboulet/websockify 8080 localhost:5900
```
