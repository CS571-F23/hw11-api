build
```bash
docker build . -t ctnelson1997/cs571-f23-hw11-api
docker push ctnelson1997/cs571-f23-hw11-api
```

run
```bash
docker pull ctnelson1997/cs571-f23-hw11-api
docker run --name=cs571_f23_hw11_api -d --restart=always -p 38111:38111 -v /cs571/f23/hw11:/cs571 ctnelson1997/cs571-f23-hw11-api
```