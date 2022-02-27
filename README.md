# Sample Spring Boot App 1

# Jar Build
`./gralew clean build`

produces: `./build/libs/sb1.jar`

# Spring Boot Run
`./gradlew bootRun`

# Docker Build
`docker build -t legnoban/sample-sb-app1 .`

# Docker Push
`docker push legnoban/sample-sb-app1`

# Docker Run
`docker run -p 8080:8080 legnoban/sample-sb-app1`

# Access
`localhost:8080`