# requirements
- java 8 jdk
- rabbitmq server (if you have docker installed use "docker-compose up" command in root directory where 'docker-compose.yaml' exists)

# build command for windows operating system (JAVA 8)
javac -cp ".;lib/*" Send.java

# run
java -cp ".;lib/*" Send