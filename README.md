### Create a DSE database container with optimized configurations for dev environment

```bash
git clone https://github.com/tobernguyen/dse-server-dev.git
cd dse-server-dev
docker run -e DS_LICENSE=accept -p 9042:9042 --name my-dse -d -v $(pwd)/config:/config datastax/dse-server
```
