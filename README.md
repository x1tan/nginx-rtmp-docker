git clone <this repo>
docker build -t nginx-rtmp-hls .
docker run -d -p 1935:1935 -p 8080:8080 --name nginx-rtmp-hls -t nginx-rtmp-hls
