# Backend Ecommerce.JAR 
#fala qual imagem vamos usar
FROM openjdk:17.0.2-jdk
#cria a pasta dentro da imagem - no momento de criação da imagem
WORKDIR /ecommerce
# adiciono o .jar do meu projeto na imagem do Docker
ADD ecommerce.jar /ecommerce
#comando especial para fazer o java rodar meu projeto no momento que o container é criado
ENTRYPOINT ["java", "-jar", "ecommerce.jar"]

# # Backend Database MySQL
# FROM mysql:latest
 
# LABEL maintainer="cypherbold"
 
# EXPOSE 3306
 
# ENV MYSQL_ROOT_PASSWORD="ColocarSenhaDoRoot"
# ENV MYSQL_DATABASE=ecommerce
# # ENV MYSQL_USER=user
# # ENV MYSQL_PASSWORD=passworduser
 
# VOLUME [ "/var/lib/mysql" ]
