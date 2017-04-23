# simple java webapp 

To run this, add the following to the POM:
```xml
  <build>
    <finalName>simple-java-webapp</finalName>
    <plugins>
      <plugin>
        <groupId>org.apache.tomcat.maven</groupId>
        <artifactId>tomcat7-maven-plugin</artifactId>
        <version>2.2</version>
        <configuration>
          <path>/myProject</path>
        </configuration>
      </plugin>
    </plugins>
  </build>
```
In Intellij, hit 'Edit Configuration', hit the + sign and click on Maven.
On the command line of the run configuration, enter 'tomcat7:run'
