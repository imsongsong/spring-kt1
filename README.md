## What We Mean by "Spring"
The term "Spring" means different things in different contexts. It can be used to refer to the Spring Framework project itself, which is where it all started. Over time, other Spring projects have been built on top of the Spring Framework. Most often, when people say "Spring", they mean the entire family of projects. This reference documentation focuses on the foundation: the Spring Framework itself.
⽤用于构建企业级应⽤用的轻量量级一站式解决⽅方案

https://spring.io/
https://spring.io/projects

## Hello World
https://start.spring.io/

## Sping-boot
Spring Boot不是什么
不不是应⽤用服务器器
不是Java EE之类的规范 
不是代码生成器器
不是Spring Framework的升级版

## Spring Boot 的特性
⽅便地创建可独立运行的 Spring 应⽤程序 
直接内嵌 Tomcat、Jetty 或 Undertow 
简化了项目的构建配置
为 Spring 及第三方库提供⾃自动配置 
提供生产级特性
无需生成代码或进⾏XML配置

## Spring Boot 的四⼤核心
自动配置 - Auto Configuration 
起步依赖 - Starter Dependency
命令⾏界面 - Spring Boot CLI 
Actuator

# 了解自动配置的实现原理

## 了解⾃自动配置

### 自动配置
基于添加的 JAR 依赖自动对 Spring Boot 应用程序进⾏配置
spring-boot-autoconfiguration

### 开启⾃自动配置
@EnableAutoConfiguration
exclude = Class<?>[] 
@SpringBootApplication


## 自动配置 AutoConfigration

## 起步依赖 Starter Dependency
