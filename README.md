# AZ.ContainerRepo
for learning purpose containers will be uploaded here

to push into github container registry
```
echo YOUR_GITHUB_PAT | docker login ghcr.io -u YOUR_GITHUB_USERNAME --password-stdin
docker build -t my-app:latest .
docker tag my-app:latest ghcr.io/johndoe/my-repo/my-app:latest
```

for hello_world:v1
```
ghcr.io/sgrthati/hello_world:v1
```
