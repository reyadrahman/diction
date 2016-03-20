`Use the following commands to install the RiTa-Wordnet JAR files into your local maven repo`

```
mvn install:install-file -Dfile=RiTaWN.jar -DgroupId=wordnet -DartifactId=wordnet-rita -Dversion=0.0.1 -Dpackaging=jar
mvn install:install-file -Dfile=supportWN.jar -DgroupId=wordnet -DartifactId=wordnet-support -Dversion=0.0.1 -Dpackaging=jar
```