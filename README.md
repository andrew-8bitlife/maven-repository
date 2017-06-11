# 8bit.life Maven Repository
---

## Available modules


| Name                         | Group Id      | Artifact ID                   | Latest version | Type    | Source |
|------------------------------|---------------|-------------------------------|----------------|---------|--------|
|Dependent Library Demo        | eightbit-life | dependent-library-demo        | 1.1            | Private | [Repository](https://github.com/andrew-8bitlife/dependent-library-demo) |

## Repository management

### Maven

Add the following to your `pom.xml' to add this Maven repository:

```
<repository>
    <id>eightbit-life-releases</id>
    <name>eightbit-life-releases</name>
    <url>https://github.com/andrew-8bitlife/maven-repository/raw/master/releases/</url>
</repository>
```

### Gradle

Add the following to the build.gradle in the correct section:

```
repositories {
    mavenCentral()
    maven {
        url 'https://github.com/andrew-8bitlife/maven-repository/raw/master/releases/'
    }
}
```

For more info read [this](http://www.gradle.org/docs/current/userguide/artifact_dependencies_tutorial.html).
