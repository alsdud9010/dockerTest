# Docker build
```
git clone https://github.com/alsdud9010/dockerTest.git
cd C:\\kitri\\dockerTest
docker build --rm -t my9010/ut:2 .
docker images
```

# Docker run
```
docker run -it --name ut -v C:\\kitri\\dockerTest:/df --rm my9010/ut:2
```
