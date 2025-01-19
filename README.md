# CYX Parent

这是一个Maven父项目，用于统一管理所有子项目的依赖版本。

## 使用方法

在你的子项目的 `pom.xml` 中添加以下parent配置：

```xml
<parent>
    <groupId>com.cyx</groupId>
    <artifactId>cyx-parent</artifactId>
    <version>1.0.0-SNAPSHOT</version>
    <relativePath/>
</parent>
```

## 主要特性

- 统一的依赖版本管理
- 预配置常用依赖
- Java 17
- Spring Boot 3.2.3
- Spring Cloud 2023.0.0
- Spring Cloud Alibaba 2022.0.0.0

## 包含的主要依赖

- Spring Boot/Cloud 全家桶
- MyBatis Plus
- MySQL
- Druid
- Hutool
- Lombok
- MapStruct
- Knife4j

## 版本说明

当前版本：1.0.0-SNAPSHOT

## 许可证

MIT 