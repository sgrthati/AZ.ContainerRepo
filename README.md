# AZ.ContainerRepo
for learning purpose containers will be uploaded here

to push into github container registry
```
echo YOUR_GITHUB_PAT | docker login ghcr.io -u YOUR_GITHUB_USERNAME --password-stdin
docker build -t my-app:latest .
docker tag my-app:latest ghcr.io/johndoe/my-repo/my-app:latest
```

for hello_world app
```
docker pull ghcr.io/sgrthati/hello_world:v1
for v1: ghcr.io/sgrthati/hello_world:v1
for v2: ghcr.io/sgrthati/hello_world:v2
for v3: ghcr.io/sgrthati/hello_world:v3
docker run -d -p 5000:5000 --name hello_world ghcr.io/sgrthati/hello_world:v1
to access: http://localhost:5000/hello
```
