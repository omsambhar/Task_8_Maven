# Hello Java Maven - Jenkins CI Build

This is a simple Java HelloWorld project built using Maven, and the build is triggered via Jenkins.

## Files
- `HelloWorld.java` – Main Java class
- `pom.xml` – Maven config
- `README.md` – Task description

## How to Run
1. Build using Maven: `mvn clean package`
2. Run: `java -cp target/hello-1.0.jar HelloWorld`

## Jenkins Setup
- Freestyle project
- Build step: Invoke top-level Maven targets
- Goal: `clean package`
# Task_8_Maven
