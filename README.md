# Quickstart
- `docker build -t dav -t dav:latest -f Dockerfile.linux.arm64 .`
- `docker run -d -it --name dav --net host -v /mnt/export:/mnt dav`
- `docker exec -it dav htdigest -c /etc/apache/users/passwd DAVFS myuser`
(enter password) 


