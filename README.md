# docker-wrapper

#### 项目介绍
docker-wrapper

1. include wrapper-v3.5.39
2. support single and tomcat
3. support alpine and centos
4. usage: 
   - docker run -it --rm --name wrapper-single-1.0.0-alpine -p 18080:8080 -p 10001:10001 -p 10002:10002 registry.cn-hangzhou.aliyuncs.com/rancococ/wrapper:wrapper-3.5.39.1-single-1.0.0-alpine
   - docker run -it --rm --name wrapper-single-1.0.0-centos -p 18080:8080 -p 10001:10001 -p 10002:10002 registry.cn-hangzhou.aliyuncs.com/rancococ/wrapper:wrapper-3.5.39.1-single-1.0.0-centos
   - docker run -it --rm --name wrapper-tomcat-1.0.0-alpine -p 18080:8080 -p 10001:10001 -p 10002:10002 registry.cn-hangzhou.aliyuncs.com/rancococ/wrapper:wrapper-3.5.39.1-tomcat-8.5.40-alpine
   - docker run -it --rm --name wrapper-tomcat-1.0.0-centos -p 18080:8080 -p 10001:10001 -p 10002:10002 registry.cn-hangzhou.aliyuncs.com/rancococ/wrapper:wrapper-3.5.39.1-tomcat-8.5.40-centos
