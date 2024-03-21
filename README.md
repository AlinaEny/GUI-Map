# GUI-Map
Please check readme.md first.

You could find excutable JAR in ./target, read README.MD to get details to build the project. 

Since JavaFX is removed from JDK since JDK11. 

You need  "java --module-path YOURPATH\javafx-sdk-20\lib --add-modules javafx.controls,javafx.graphics,javafx.base -jar .\target\WesternMap-with-dependencies.jar"

I also upload a seperate JAR with all dependencies except JavaFX 20. 

Please ignore 'WesternMap-1.0-SNAPSHOT.jar' since it is build without dependencies

The changes after Acceptance Testing: 

The Edit mode works now, you can add some POIs.
