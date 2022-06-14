# kubernetes-study

For download:
```
git clone https://github.com/svdevops07/https://github.com/svdevops07/kubernetes-study.git
```

## Docker Image & Docker Registry
1. Make local Image
```
cd 1.docker-image
docker build -t svdevops07/myk8s_app:v0.1 .
```

2. Login:
```
docker login
```

3. Push into Registry:
```
docker push svdevops07/myk8s_app:v0.1
```

4. Start Docker Image:
```
docker run -d -p 1234:80 svdevops07/myk8s_app:v0.1
```

To pull from Registry:
```
docker pull svdevops07/myk8s_app:v0.1
```
