# requirements
- java 8 jdk
- rabbitmq server (if you have docker installed use "docker-compose up" command in root directory)

# build (JAVA 8)
javac -cp amqp-client-5.16.0.jar Send.java

# run
java -cp ".;amqp-client-5.16.0.jar;slf4j-api-1.7.36.jar;slf4j-simple-1.7.36.jar" Send