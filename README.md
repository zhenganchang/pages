# development-notes

> 开发笔记

### Maven Wrapper 腾讯镜像地址

```properties
distributionUrl=https://mirrors.cloud.tencent.com/apache/maven/maven-3/3.9.15/binaries/apache-maven-3.9.15-bin.zip
```

### Maven 腾讯镜像仓库配置

```xml
<repositories>
    <repository>
        <id>tencent</id>
        <url>https://mirrors.cloud.tencent.com/nexus/repository/maven-public/</url>
    </repository>
</repositories>
<pluginRepositories>
    <pluginRepository>
        <id>tencent</id>
        <url>https://mirrors.cloud.tencent.com/nexus/repository/maven-public/</url>
    </pluginRepository>
</pluginRepositories>
```

### Gradle Wrapper 腾讯镜像地址

```properties
distributionUrl=https\://mirrors.cloud.tencent.com/gradle/gradle-9.4.1-bin.zip
```

### Gradle 腾讯镜像仓库配置

```groovy
maven { url 'https://mirrors.cloud.tencent.com/nexus/repository/maven-public/' }
```
