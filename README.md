__mini-jdbc__  - Small and efficient JDBC wrapper.

[![Build Status](https://travis-ci.org/mfursov/mini-jdbc.svg?branch=master)]	(https://travis-ci.org/mfursov/mini-jdbc)

## Building

```
mvn -DskipTests=true clean package install
```

## Usage

Documentation is under development. Please check [unit tests](https://github.com/mfursov/mini-jdbc/blob/master/src/test/java/mini/jdbc/test/SamplesTest.java) to see API in action.

You may find useful to see the recommended way of writing [SQL query interfaces](https://github.com/mfursov/mini-jdbc/blob/master/src/test/java/mini/jdbc/test/asset/UserSql.java) and
[transactions](https://github.com/mfursov/mini-jdbc/blob/master/src/test/java/mini/jdbc/test/asset/dbi/SampleDbi.java) in tests.

### Requirements

Java8+


### License

This project available under Apache License 2.0.