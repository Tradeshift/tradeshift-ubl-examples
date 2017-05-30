OASIS Universal Business Language
=================================

UBL is designed to provide a universally understood and recognized commercial syntax for legally binding business documents and to operate within a standard business framework such as ISO 15000 (ebXML) to provide a complete, standards-based  infrastructure that can extend the benefits of existing EDI systems to businesses of all sizes. UBL is freely available to everyone without legal encumbrance or licensing fees.

Please refer to the official [open-oasis.org](http://oasis-open.org/) site for the full documentation for [UBL v2.0](http://docs.oasis-open.org/ubl/os-UBL-2.0/UBL-2.0.html) and [UBL v2.1](http://docs.oasis-open.org/ubl/os-UBL-2.1/UBL-2.1.html)

## UBL 2.1 XML and JSON examples
The artifact contains the examples included in the official packaged version of UBL for both the XML canonical and JSON alternative representation.

## Getting started
In order to you to include this software in your own project, you must first specify the dependency on the artifact. The most current version is `2.1.0` and it is backwards compatible with `2.0.0`.

### Using the UBL XML/JSON examples with Maven

```xml
  <dependency>
    <groupId>com.tradeshift</groupId>
    <artifactId>tradeshift-ubl-xamples</artifactId>
    <version>2.1.0</version>
  </dependency>
```

### Using the UBL XML/JSON examples with SBT
```sbt
libraryDependencies +=
  "com.tradeshift" %% "tradeshift-ubl-examples" % "2.1.0"
```

### Using the UBL XML/JSON examples with Gradle
```gradle
dependencies {
  compile 'com.tradeshift:tradeshift-ubl-examples:2.1.0'
}
```

## What is included?
The artifact only contains the XML and JSON examples of the Universal Business Language standard.


