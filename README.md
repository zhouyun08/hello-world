# Hello World Spring MVC 项目

本项目为标准的 Spring MVC 工程示例，包含一个简单的 API 接口。

## 目录结构

- `src/main/java`：Java 源代码目录
- `src/main/resources`：资源文件目录
- `src/main/webapp`：Web 资源目录（如 WEB-INF/web.xml）
- `pom.xml`：Maven 构建文件

## 快速开始

1. 使用 IDEA 或 Eclipse 打开本项目。
2. 运行 `mvn clean package` 构建项目。
3. 部署到支持 Servlet 3.0+ 的容器（如 Tomcat）。

## 示例 API

- `GET /api/hello` 返回 `{"message": "Hello, Spring MVC!"}`
