# mavenweb
maven web project demo

mvn archetype:generate -DgroupId=com.honsoft.demo -DartifactId=mavenweb -DarchetypeArtifactId=maven-archetype-webapp -DinteractiveMode=false

cd mavenweb

mvn eclipse:eclipse

import existing maven project

create folder src/main/java, src/test/java

project properties - project facet - java - runtime - tomcat 추가

project properties - configure build path - libraries - jre system library 를 edit 하여 변경

mvn update project

참고 url

https://howtodoinjava.com/maven/how-to-create-java-source-folders-in-maven-web-application/
