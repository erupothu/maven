# maven

#### maven Quick start project

> mvn archetype:generate -DarcheypeArtifactId=maven-archetype-quickstart  
> groupId: com.companyName  
> artifactId: projectName  
> package: com.company.project  
> version: 1.0.0  

#### maven Quarkus project

> mvn io.quarkus.platform:quarkus-maven-plugin:3.0.3.Final:create  
> groupId: com.companyName  
> artifactId: projectName  
> package: com.company.project  
> version: 1.0.0 

#### maven Qurakus kotlin project

> mvn io.quarkus.platform:quarkus-maven-plugin:3.0.0.Final:create -Dextensions=kotlin,resteasy-reactive-jackson  
> groupId: com.companyName  
> artifactId: projectName  
> package: com.company.project  
> version: 1.0.0 

#### Gradle Qurakus Project

> mvn io.quarkus.platform:quarkus-maven-plugin:3.0.3.Final:create -DbuildTool=gradle
> groupId: com.companyName  
> artifactId: projectName  
> package: com.company.project  
> version: 1.0.0 

#### Gradle Quarkus Kotlin project
> mvn io.quarkus.platform:quarkus-maven-plugin:3.0.0.Final:create -Dextensions=kotlin,resteasy-reactive-jackson -DbuildTool=gradle
> groupId: com.companyName  
> artifactId: projectName  
> package: com.company.project  
> version: 1.0.0 

#### Maven Springboot Project

> mvn archetype:generate -DarcheypeArtifactId=maven-archetype-web  
> groupId: com.companyName  
> artifactId: projectName  
> package: com.company.project  
> version: 1.0.0  

```xml
<parent> 
  <groupId>org.springframework.boot</groupId> 
  <artifactId>spring-boot-starter-parent</artifactId> 
  <version>1.3.5.RELEASE</version> 
  <relativePath /> <!-- lookup parent from repository --> 
</parent>
<dependencies>
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
</dependencies>
<build>
    <plugins>
        <plugin>
            <groupId>org.springframework.boot</groupId>
            <artifactId>spring-boot-maven-plugin</artifactId>
        </plugin>
    </plugins>
</build>
```

