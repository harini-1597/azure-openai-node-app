# Azure OpenAI Node App

This project aims to demonstrate the integration of Microsoft Azure services, OpenAI's Language Model (LLM), and local development using Azure Copilot to build a REST API for a chatbot application. The application provides a smooth customer experience by integrating plugins, allowing users to interact with various functionalities seamlessly.

## Features

- Integration of Microsoft Azure services for cloud-based functionalities.
- Utilization of OpenAI's Language Model (LLM) for natural language processing.
- Local development using Azure Copilot for rapid iteration and testing.
- Deployment of a REST API backend to handle user requests.
- Integration of plugins to enhance the chatbot's capabilities.

## Setup

To set up the project locally, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/azure-openai-node-app.git
   ```

2. Install dependencies:

   ```bash
   cd azure-openai-node-app
   npm install
   ```

3. Set up Azure services:
   - Obtain necessary Azure API keys and credentials.
   - Configure environment variables or `.env` file with Azure credentials.

4. Deploy Azure Copilot:
   - Follow the instructions provided by Azure Copilot to deploy your application locally.
   - Ensure that the necessary Azure services are provisioned and integrated with the application.

5. Run the application:

   ```bash
   npm start
   ```

## Usage

Once the application is running locally, you can interact with the chatbot using the provided interface or APIs. Users can ask questions, request assistance, or trigger specific functionalities supported by the plugins.

## Integration with OpenAI Schema

The project integrates with OpenAI's schema for defining plugins. The schema defines the structure of the plugins, including parameters, descriptions, and example inputs/outputs. This allows for seamless integration of backend APIs with OpenAI's Language Model (LLM), enabling natural language understanding and response generation.
