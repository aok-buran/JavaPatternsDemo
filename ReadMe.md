## Демо-приложение быстрого поиска изоморфных подграфов

Чтобы подключить библиотеку, нужно добавить репозиторий в файл `pom.xml`: 

```xml
   <repositories>
        <repository>
            <id>buran-center</id>
            <url>https://mvn.buran.center/releases</url>
        </repository>
    </repositories>
```

Также необходимо подключить саму зависимость:

```xml
    <dependencies>
        <dependency>
            <groupId>center.buran.fast</groupId>
            <artifactId>patterns</artifactId>
            <version>1.0-SNAPSHOT</version>
        </dependency>
    </dependencies>
```
