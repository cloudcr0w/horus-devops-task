# Horus DevOps Recruitment Task

This project was created as part of a technical task for a DevOps position.

It includes:
- a simple Spring Boot application with a `/hello` endpoint,
- unit test for the controller,
- a GitHub Actions workflow to build and test the project,
- a Dockerfile to containerize the app,
- and a published image on DockerHub.

## How to run the application

### Locally (Java 17 required)

```bash
./mvnw spring-boot:run
# or
./mvnw clean package
java -jar target/horus-app-0.0.1-SNAPSHOT.jar
```

Open: [http://localhost:8080/hello](http://localhost:8080/hello)

### 🐳 Using Docker

```bash 
docker pull cloudcr0w/horus-app
docker run -p 8080:8080 cloudcr0w/horus-app
```
Open: [http://localhost:8080/hello](http://localhost:8080/hello)


## 📂 Project Structure

```bash
|-- src/
|-- Dockerfile
|-- .github/workflows/build.yml
|-- README.md
```

## 🔗 Links

- [GitHub Actions – CI pipeline](https://github.com/cloudcr0w/horus-devops-task/actions)  
- [DockerHub – cloudcr0w/horus-app](https://hub.docker.com/r/cloudcr0w/horus-app) 

## 👤 Author

Adam Wrona – [LinkedIn Profile](https://www.linkedin.com/in/adam-wrona-111ba728b/)
adamwronowy@gmail.com