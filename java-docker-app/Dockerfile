FROM openjdk:16.0.2 
COPY . /var/www/java  
WORKDIR /var/www/java  
RUN javac Add.java  
ENTRYPOINT ["java", "Add"]
CMD [ "5", "10"  ]