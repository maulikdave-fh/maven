Maven is a software project lifecyle management tool. It is based on POM (Project Object Model). It follows convention over configuration & follows a pre-defined directory structure.

my-app
|-- pom.xml
 -- target
`-- src
    |-- main
    |   |-- java
    |   |   `-- com
    |   |       `-- mycompany
    |   |           `-- app
    |   |               `-- App.java
    |   `-- resources
    |       `-- application.properties
    `-- test
        |-- java
        |   `-- com
        |       `-- mycompany
        |           `-- app
        |               `-- AppTest.java
        `-- resources
            `-- test.properties

The output can be jar / war and it goes into the target directory.

# pom.xml
## Maven Dependencies

## parent POM
