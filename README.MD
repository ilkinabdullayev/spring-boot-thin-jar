# Create thin jar from Spring boot

```sh
./gradlew build -Pthin=true
cd build/thin/root/   
java -Dthin.root=. -Dthin.offline=true -jar spring-boot-thin-jar-0.0.1-SNAPSHOT.jar   
```
