## Using MongoDB's Queryable Encryption on GraalVM

This is a demo of based on the 
[ClientSideEncryptionAutoEncryptionSettingsTour](https://github.com/mongodb/mongo-java-driver/blob/master/driver-sync/src/examples/tour/ClientSideEncryptionAutoEncryptionSettingsTour.java). 
using GraalVM to run the code.

### Requirements

  - osx
  - Graalvm 21
  - MongoDB running on `mongodb://localhost:27107`
  - `mongocryptd` on the path

### Running

```shell
# To compile
./gradlew nativeCompile

# To compile and run
./gradlew nativeRun

# To run just the executable 
./app/build/native/nativeCompile/app
```

### Special thanks to:

 * https://graalvm.github.io/native-build-tools/latest/gradle-plugin-quickstart.html
 * https://github.com/oracle/graalvm-reachability-metadata/