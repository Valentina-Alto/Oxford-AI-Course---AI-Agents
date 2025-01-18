
# Climbing Store AI Assistant

This notebook demonstrates the use of the LangChain library with Azure OpenAI to create a conversational agent capable of assisting customers of a climbing e-commerce. 

## Business scenario

We are the owners of a climbing e-store, and we want to enhance our customer experience by creating an AI assistant. This assistant leverages the Azure OpenAI service to provide real-time, intelligent support to our customers, helping them with various tasks such as product inquiries, order tracking, and language translation.

### Key Features
1. Product Inquiries: The AI assistant can answer questions about different climbing products, including hiking recommendation for specific routes sponsored by the climbing store.

2. Hyper personalisation:

Customers can benefit from a personalised experience, since the AI assistant will get access to their purchase history and make relevant recommendations.

3. Conversational user interface

Customers can benefit from a conversational, chat experience that can improve the overall experience and increase engagement, differentiating the store in the market of e-commerce.

## Prerequisites
Before running this notebook, ensure you have the following prerequisites:

1. Python 3.8+: Make sure you have Python 3.8 or higher installed on your system.

2. Azure OpenAI Service: You need access to the Azure OpenAI service. Ensure you have the following details:
- AZURE_OPENAI_API_VERSION: The API version of the Azure OpenAI service.
- AZURE_OPENAI_ENDPOINT: The endpoint URL for the Azure OpenAI service.
- AZURE_OPENAI_API_KEY: The API key for accessing the Azure OpenAI service.
- AZURE_OPENAI_CHAT_DEPLOYMENT_NAME: The deployment name for the Azure OpenAI chat model.
Required Python Packages: Install the necessary Python packages by running the following command:

```python
pip install langchain-openai langchain-core
```

**Note**: you can use other LLMs of your choice to run this notebook. If you are using a model different from the Azure OpenAI series, make sure to adjust the environment variables and the client library.

## Running the notebook
1. Clonte the repository:
```python
git clone <repository-url>
cd <repository-directory>
```
2. Install Dependencies
```python
pip install -r requirements.txt
```
3. Set environment variables
```python
os.environ["AZURE_OPENAI_API_VERSION"] = "<your-api-version>"
os.environ["AZURE_OPENAI_ENDPOINT"] = "<your-endpoint>"
os.environ["AZURE_OPENAI_API_KEY"] = "<your-api-key>"
os.environ["AZURE_OPENAI_CHAT_DEPLOYMENT_NAME"] = "<your-deployment-name>"
```




