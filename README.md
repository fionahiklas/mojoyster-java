## Overview


## Creating Template

I used the maven archetype plugin to create the skeleton for this project running the following command

```
mvn archetype:generate 
   -DarchetypeGroupId=org.apache.maven.archetypes 
   -DarchetypeArtifactId=maven-archetype-quickstart 
   -DarchetypeVersion=1.1 
   -DinteractiveMode=false 
   -DgroupId=com.hiklas.mucking.around 
   -DartifactId=mojoyster
```

Annoyingly this creates a directory called 'mojoyster' and I can't find any 
setting [here](https://maven.apache.org/archetype/maven-archetype-plugin/generate-mojo.html) to fix that.  
Maven is a pain in the neck sometimes/always!