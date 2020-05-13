# Apache Camel
    Project Architecture
 		integration-platform
 			--Act as Root/Parent Module and it holds all sub modules like route transform
 			 3rd party Etc.


    <!-- Dont Execute JUST FOR KNOWING -->
        Creating parent pom
            mvn archetype:generate -DarchetypeGroupId=org.codehaus.mojo.archetypes -DarchetypeArtifactId=pom-root -DarchetypeVersion=RELEASE
    
        Create Camel Spring Boot:
        mvn archetype:generate /
        -DarchetypeGroupId=org.apache.camel.archetypes /
        -DarchetypeArtifactId=camel-archetype-spring-boot /
        -DarchetypeVersion=2.16-SNAPSHOT /
        -DarchetypeRepository=https://repository.apache.org/content/groups/snapshots-group