FROM java:8  
#COPY . /var/www/java  
COPY /project/src/. /var/www/java  
#COPY *.java /var/www/java
WORKDIR /var/www/java
RUN javac Hello.java
CMD ["java", "Hello"]
