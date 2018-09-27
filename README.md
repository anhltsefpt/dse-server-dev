# Create a DSE database container with optimized settings for dev environment
```bash
docker run -e DS_LICENSE=accept -p 9042:9042 --name my-dse -d -v $(pwd)/config:/config datastax/dse-server
```
