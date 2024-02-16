## Using MongoDB's Queryable Encryption on GraalVM

This is just a demo of based on the 
[ClientSideEncryptionAutoEncryptionSettingsTour](https://github.com/mongodb/mongo-java-driver/blob/master/driver-sync/src/examples/tour/ClientSideEncryptionAutoEncryptionSettingsTour.java).


### Requirements

  - Graalvm 21
  - MongoDB running on `mongodb://localhost:27107`
  - `mongocryptd` on the path

### Running

```shell
# To compile and run
./gradlew nativeRun


# To run again
./app/build/native/nativeCompile/appMain

```