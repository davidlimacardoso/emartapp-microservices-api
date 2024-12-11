# emartapp-microservices-api

## Description

This project aims to containerize a microservices application using Docker. The application consists of a web page served by Nginx and APIs developed in Java and Node.js.

## Project Structure

The repository contains the following folders and files:

- `client/` - Frontend application code.
- `javaapi/` - Code for the API developed in Java.
- `nodeapi/` - Code for the API developed in Node.js.
- `nginx/` - Nginx configuration.
- `Dockerfile` - Dockerfile to build the application image.
- `docker-compose.yaml` - Docker Compose configuration file to orchestrate the containers.
- `Jenkinsfile` - Configuration for continuous integration using Jenkins.
- `README.md` - This file.

## Technologies Used

- **Docker**: Containerization of the application.
- **Nginx**: Web server for the frontend application.
- **Java**: Implementation of one of the APIs.
- **Node.js**: Implementation of the other API.
- **TypeScript**: Language used in the frontend.
- **HTML/CSS**: Structure and styling of the frontend.

## How to Run the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/davidlimacardoso/emartapp-microservices-api.git
   cd emartapp-microservices-api

2. Run Docker Compose:
```bash
docker-compose up
```
Access the application in your browser at http://localhost.

## Contribution
Contributions are welcome! Feel free to open issues or pull requests.

## License
This project is licensed under the MIT License.

`Feel free to modify it as needed!
`
## References

devopshydclub
[emartapp](https://github.com/devopshydclub/emartapp)

[DevOps Beginners to Advanced with Projects](https://www.udemy.com/course/decodingdevops/?couponCode=KEEPLEARNINGBR)