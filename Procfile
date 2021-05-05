web: echo "HTTP/1.1 200 OK\n\n $(date)\r\n" | nc -q 1 -l 0.0.0.0 $PORT
worker: ./start.sh
