# chatgptintegrate

This is a Spring Boot project that integrates ChatGPT in the backend, allowing you to interact with the GPT-3 model using RESTful API endpoints.

## Prerequisites

Before getting started, make sure you have the following prerequisites:

- Java Development Kit (JDK) 17
- Apache Maven
- OpenAI API Key (You can obtain this from OpenAI)

## Getting Started

Clone the repository to your local machine:
git clone https://github.com/abhishektnt/chatgptintegrate.git

## Running the Project
To run the Spring Boot application, use the following command. :rocket: 

**java -jar target/springboot-chatgpt-1.0.0.jar**

## API Usage
You can interact with ChatGPT by sending HTTP POST requests to the following endpoint:
curl --location 'http://localhost:9091/bot/chat?prompt=get%20me%20some%20coffee' \
--header 'Authorization: Bearer YOUR_OPENAI_API_KEY'

