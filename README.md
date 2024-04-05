# 샘플용 자바17 스프링부트2 프로젝트
> port: 8080

# 로컬 빌드 & 실행
## build
```shell
./gradlew clean build
```

## run jar
```shell
java -jar build/libs/sample-spring-boot-2-java17-gradle-0.0.1-SNAPSHOT.jar
```

# 도커 빌드 & 실행
## build
```shell
docker build -t sample-project .
```

## run
```shell
docker run --rm -d -p 8080:8080 --name sample-project sample-project
```
