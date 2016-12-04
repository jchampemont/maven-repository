# maven-repository
A github pages repository to contain a maven repository of my personal projects

## How to use
### Maven
Add the following repository to your `~/.m2/settings.xml` or project's `pom.xml`:

    <repository>
      <id>jchampemont-maven</id>
      <name>jchampemont's gh-pages maven repository</name>
      <url>https://jchampemont.github.io/maven-repository/maven2/</url>
    </repository>
    
### Gradle
Add the following repository to your `build.gradle`:

    repositories {
      maven {
        url "https://jchampemont.github.io/maven-repository/maven2/"
      }
    }
