# mtest-dep

small fake java dependency to be built with maven.

```
mvn test
mvn package
mvn install
```


this fake library has been generated using this maven archetype :
```bash
mvn archetype:generate \
     -DgroupId=mtestdep \
     -DartifactId=mtest-dep \
     -DarchetypeArtifactId=maven-archetype-quickstart \
     -DinteractiveMode=false \

```
