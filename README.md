fork form https://github.com/wenhao/jpa-spec

update jdk -> 17

```xml
<dependency>
    <groupId>com.solan</groupId>
    <artifactId>jpa-spec-solan</artifactId>
    <version>1.0.0</version>
</dependency>
```

```xml
<repositories>
    <repository>
        <id>maven-public</id>
        <name>maven-public</name>
        <url>https://nexus.fatpanda.space/repository/maven-public/</url>
        <snapshots>
            <updatePolicy>always</updatePolicy>
        </snapshots>
    </repository>
</repositories>
```