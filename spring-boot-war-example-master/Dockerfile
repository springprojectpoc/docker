FROM openjdk:8
EXPOSE 8282
#ADD source_folder destination_source_folder
ADD target/war-name.war .
ENTRYPOINT ["java","-jar","war-name.war"]