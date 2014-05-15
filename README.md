# Spark Word Count

## how to build

Spark version 0.9 is already on Maven central, so modify the `pom.xml`
to match the latest version, e.g.

```xml
        <dependency>
            <groupId>org.apache.spark</groupId>
            <artifactId>spark-core_2.10</artifactId>
            <version>0.9.1</version>
        </dependency>
```

and run:

```
$ mvn package
```

For Spark 1.0 you can add the jar to your local Maven repository e.g.:

```
./add-mvn-pkg /usr/share/spark/lib/spark-assembly-1.0.0-hadoop1.0.4.jar
```
