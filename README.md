# hive-kudu-handler-3

The hive-kudu-handler available for hive 3.x

## Description (English)

This project is a hive-kudu-handler that runs on Hive 3.x.
It is modified from the official Hive 4.x source code to be compatible with the Hive 3.x API, enabling seamless
integration and usage of Kudu storage in Hive 3.x environments.

## 简介（中文）

本项目是一个可运行于 Hive 3.x 的 hive-kudu-handler。
该项目基于 Hive 4.x 的官方源代码进行修改，使其兼容 Hive 3.x 的 API，方便在 Hive 3.x 环境下集成和使用 Kudu 存储。

## Build

Jdk 8 is required to build this project.

Modify the dependency versions in the `pom.xml` file to the versions you need.
Then, you can build the project using Maven:

```bash
mvn clean package -DskipTests
```

## Usage

After building the project, you can copy the hive-kudu-handler-3.1.3.jar to the Hive lib directory.
