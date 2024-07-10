# Library ${artifactId}

![CI](https://github.com/enr/${artifactId}/workflows/CI/badge.svg)

[![](https://jitpack.io/v/enr/${artifactId}.svg)](https://jitpack.io/#enr/${artifactId})

Java library

## Development

Build:

```
mvn install
```

Full check (test and formatting):

```
mvn -Pci
```

Repair formatting:

```
mvn -Pfmt
```

Fast build (skip any check and file generation):

```
mvn -Pfast
```

## Usage

To get this project into your build:

Add the JitPack repository to your build file

```xml
<repositories>
  <repository>
      <id>jitpack.io</id>
      <url>https://jitpack.io</url>
  </repository>
</repositories>
```

Add the dependency

```xml
<dependency>
  <groupId>${groupId}</groupId>
  <artifactId>${artifactId}</artifactId>
  <version>${version}</version>
</dependency>
```
