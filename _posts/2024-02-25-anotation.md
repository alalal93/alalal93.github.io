---
layout: single
title:  "[Spring Boot] @Valid 어노테이션"
categories: springboot
tag: [springboot]
sidebar:
    nav: "counts"
---

**[공지사항]** [밤둘레 블로그 바로가기](https://bamdule.tistory.com/35)

사용법은 정리가 잘되어있는 밤둘레님 블로그를 참고!

## java.validation의 @Valid 어노테이션 사용법 정리

Spring Boot 라이브러리에서 기본적으로 탑재된 기능이었지만, 현재는 pom.xml에 Spring Boot Starter Validation를 따로 주입해줘야함

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-validation</artifactId>
    <version>2.4.4</version>
</dependency>

```
