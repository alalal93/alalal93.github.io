---
layout: single
title:  "[Spring Boot] @Valid 어노테이션"
categories: springboot
tag: [springboot]
sidebar:
    nav: "counts"
---


**[공지사항]** [밤둘레 블로그 바로가기](https://bamdule.tistory.com/35)

사용법은 정리가 잘되어있는 [밤둘레님 블로그](https://bamdule.tistory.com/35)를 참고!

## `java.validation`의 `@Valid` 어노테이션

[메이븐 리포지토리 바로가기](https://mvnrepository.com/artifact/org.springframework.boot/spring-boot-starter-validation/2.4.4)

Spring Boot 라이브러리에서 기본적으로 탑재된 기능이었지만, <br>
현재는 리포지토리 홈페이지에 들어가 알맞은 버전을 가져와
`pom.xml`에 `Spring Boot Starter Validation`를 따로 주입해줘야 함.

```java
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-validation</artifactId>
    <version>2.4.4</version>
</dependency>

```
