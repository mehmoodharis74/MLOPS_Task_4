# Running a ML model using Docker

This guide will walk you through building a Docker image using `docker build` and running it with `docker run`.

## Building Docker Image

To build the Docker image, follow these steps:

1. Make sure you have Docker installed on your system. If not, you can download and install Docker from [Docker's official website](https://www.docker.com/get-started).

2. Clone or download this repository to your local machine.

3. Navigate to the root directory of the project where the Dockerfile is located.

4. Open your terminal or command prompt and run the following command to build the Docker image:

   ```bash
   docker build -t <image-name> .

5. Use this command to run the docker image:

   ```bash
   docker run -d -p 8081:8081 <image-name>
