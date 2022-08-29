# scala-cli-bloop-sbt-spring-activemq-string-hello-world

## Description
A POC for active mq in springframework.
Sends and receives a string on a single
queue `SampleQueue`.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- scala
- active mq
- bloop-sbt

## Docker stack
- eed3si9n/sbt

## To run
`sudo ./install.sh -u`
- ActiveMQ console available at http://localhost:8161
- Login with admin/admin

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credits
- https://simplesassim.wordpress.com/2014/01/10/how-to-send-a-message-to-an-apache-activemq-topic-with-kotlin/
- https://examples.javacodegeeks.com/enterprise-java/jms/jms-messagelistener-example/
