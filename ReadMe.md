## Демо-приложение быстрого поиска изоморфных подграфов

В данном репозитории размещен пример подключения алгоритма быстрого поиска подграфов изоморфных
заданному паттерну с помощью минимального отсечения. Более подробное описание можно прочитать 
[на хабре](https://habr.com/ru/post/723328/)

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
