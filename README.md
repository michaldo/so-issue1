# so-issue1

steps to reproduce

1. clone

2. mvn package

3. java -Dspring.profiles.include=B -jar target/boot-active-include-0.0.1-SNAPSHOT.jar

Expected : The following profiles are active: B

Actual: No active profile set, falling back to default profiles: default
