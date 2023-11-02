# Getting Started

1. 看 nginx 狀態: `sudo systemctl status nginx`

2. 執行設定檔: `sudo nginx -c $(pwd)/nginx.conf`

3. start go http: `go run .`

4. 瀏覽 localhost:8001

# 改 port

listen 8001; 改成 listen 80
