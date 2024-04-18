# Spring Boot Kafka Project on CloudKarafka 🌩️

This project utilizes Kafka hosted on [CloudKarafka](https://api.cloudkarafka.com/) to implement a cloud-based Kafka connection system. It includes a producer capable of sending messages directly to the cloud and a consumer capable of consuming messages in a microservice.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine.
2. Create an account on CloudKarafka.
3. Create a new instance with the free "Developer Duck" plan on Amazon Web Services.
4. Define the following environment variables as described in `application.yml`:

   - `KAFKA_BOOTSTRAP_SERVERS`: The bootstrap server(s) provided by CloudKarafka.
   - `KAFKA_USERNAME`: Your CloudKarafka username.
   - `KAFKA_PASSWORD`: Your CloudKarafka password.
   - (Add any other required environment variables)

5. Run the project and test the connection to CloudKarafka.

## Usage

Once the environment is set up and the project is running, you can start producing and consuming messages using Kafka in the cloud.
