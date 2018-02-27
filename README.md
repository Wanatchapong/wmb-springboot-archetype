# The archetype descriptor
- An archetype descriptor located in the `src/main/resources/META-INF/maven/` directory
- The metadata about an archetype is stored in the `archetype-metadata.xml` [archetype descriptor reference](https://maven.apache.org/archetype/archetype-models/archetype-descriptor/archetype-descriptor.html)
- The archetype plugin overview [here](https://maven.apache.org/archetype/maven-archetype-plugin/index.html)

# The prototype files and the prototype pom.xml

# Let's start
1. Clone repository to local
2. Install archetype to local repository ```mvn install```
3. Update local catalog ```mvn archetype:update-local-catalog```
4. Generate archetype<br/>
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