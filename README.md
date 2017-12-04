# Mixing thymeleaf and jsp files in Spring Boot and GCloud
Spring, Thymeleaf is used as template engine.

## Quick start

1. Log in using gcloud SDK (`gcloud auth login` in command line)

1. Set your current project using `gcloud config set project PROJECT_ID`

1. Compile using Maven: `mvn install -DskipTests` in command line from your base project directory

1. Run `mvn spring-boot:run`

1. Visit `http://localhost:8080`

1. Deploy to Gcloud `mvn appengine:deploy`

1. Visit `http://YOUR_PROJECT.appspot.com`.


## Links ##
 - [Source code](https://github.com/Spring-Squad/jsp-thymeleaf-config)
 - [Thymeleaf + Spring](http://www.thymeleaf.org/doc/tutorials/2.1/thymeleafspring.html)
