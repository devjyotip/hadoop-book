Hadoop Book Worked out Code Examples

This repository contains worked out code examples for [Hadoop: The Definitive Guide, Fourth Edition](http://shop.oreilly.com/product/0636920033448.do)

## Building and Running

To build the code, you will need Maven and Java installed on your system. Then type

% mvn package -DskipTests


This will do a full build and create example JAR files in the top-level directory (e.g. 
`hadoop-examples.jar`).

To run the examples from a particular chapter, first install the component 
needed for the chapter (e.g. Hadoop, Pig, Hive, etc), then run the command lines shown 
in the chapter.

Sample datasets are provided in the [input] directory, and the full weather dataset
can be downloaded from <>.

## Hadoop Component Versions

For the precise versions of each component that the code has been tested with, see 
[book/pom.xml](book/pom.xml).
