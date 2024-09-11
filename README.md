# Log4j2 and GraalVM bug

Before building the binary, you need to install GraalVM 22 and set that as the active JDK

Oracle link: https://docs.oracle.com/en/graalvm/jdk/22/

Run `mvn -Pnative package -DskipTests` to build the native binary

Run `./target/log4j2-test` to run the binary

The bug will show up in the logs after running this command.
