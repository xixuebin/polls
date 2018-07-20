https://www.callicoder.com/spring-boot-spring-security-jwt-mysql-react-app-part-1/


Source Code
https://github.com/callicoder/spring-security-react-ant-design-polls-app

```SQL
INSERT INTO roles(name) VALUES('ROLE_USER');
INSERT INTO roles(name) VALUES('ROLE_ADMIN');
```


Post http://localhost:5000/api/auth/signup
{
    "name": "kevin.xi",
    "username": "xixuebin",
    "email": "xixuebin@163.com",
    "password": "12354"
}


## Spring Boot 默认属性
https://docs.spring.io/spring-boot/docs/current/reference/html/common-application-properties.html

## Spring Boot 自定义属性配置读取
https://my.oschina.net/magicalSam/blog/1420550