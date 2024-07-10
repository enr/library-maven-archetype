
# Java library Maven archetype

Opinionated Maven archetype to generate Java libraries.

Install archetype locally:

```
mvn install
```

Generate project:

```
mvn archetype:generate -B \
    -DarchetypeGroupId=com.github.enr \
    -DarchetypeArtifactId=library-archetype \
    -DarchetypeVersion=0.0.2 \
    -DgroupId=com.example \
    -DartifactId=mylibrary \
    -Dpackage=com.example.library \
    -Dversion=0.0.0
```
