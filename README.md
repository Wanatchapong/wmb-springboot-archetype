# The archetype descriptor
- An archetype descriptor located in the `src/main/resources/META-INF/maven/` directory
- The metadata about an archetype is stored in the `archetype-metadata.xml` [archetype descriptor reference](https://maven.apache.org/archetype/archetype-models/archetype-descriptor/archetype-descriptor.html)

# The prototype files and the prototype pom.xml

```
mvn archetype:generate \
-DarchetypeCatalog=local \
-DarchetypeGroupId=com.wmb.maven.archetypes \
-DarchetypeArtifactId=wmb-springboot-archetype \
-DarchetypeVersion=1.0.0 \
-DgroupId=com.example \
-DartifactId=example-app
```

Credit links<br/>
https://maven.apache.org/guides/mini/guide-creating-archetypes.html<br/>
http://maven.apache.org/archetype/maven-archetype-plugin/index.html<br/>
https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet<br/>