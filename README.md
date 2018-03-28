# DemoGradle
Setting up and Basic Programs

running gradle file in cmd for build.gradle : gradle task_name

running gradle file in cmd for other.gradle : gradle -b other.gradle task_name

to download jar from nexus
mvn org.apache.maven.plugins:maven-dependency-plugin:2.4:get -Dtransitive=false -Dartifact=org.sunil.com:jarname:1.0.0-SNAPSHOT:jar -DremoteRepositories=http://localhost:8081/repository/maven-public/ -Ddest=jarname.jar -U
