# maven-repository
Maven repository

Repository built using information from this website:
http://kwebble.com/blog/2014/02/19/use-github-to-host-your-own-maven-repo

To use this repository you need to add following lines into your pom.xml:

```xml
<repository>
    <id>git-danielmroczka</id>
    <name>daniel mroczka's Git based repo</name>
    <url>https://github.com/danielmroczka/maven-repository/tree/master/</url>
</repository>
```
