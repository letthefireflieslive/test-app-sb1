# Sample Spring Boot App 1

# Jar Build
`./gralew clean build`

produces: `./build/libs/sb1.jar`

# Spring Boot Run
`./gradlew bootRun`

# Docker Build
`docker build -t legnoban/sample-sb-app1:$VERSION .`

# Docker Push
`docker push legnoban/sample-sb-app1:$VERSION`

# Docker Run
`docker run -p 8090:8080 legnoban/sample-sb-app1:$VERSION`

# Access
`localhost:8090`