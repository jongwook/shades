shades
======

This project makes an assembly JAR of the following projects, which often create version conflicts:

* `com.fasterxml.jackson.core`: `jackson-core`, `jackson-databind`, `jackson-annotations`
* `com.fasterxml.jackson.module`: `jackson-module-afterburner`
* `org.hbase`: `asynchbase`
* `org.apache.curator`: `curator-framework`
* `com.ning`: `async-http-client`

## Building

    ./gradlew clean shadowJar

## Publishing

    ./gradlew clean publish


