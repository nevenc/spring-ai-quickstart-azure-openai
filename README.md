# spring-ai-quickstart-azure-openai

This is an example of a simple Spring AI application that connects to
OpenAI LLMs.

## Requirements
* Azure OpenAI service configured in Azure Portal.
* Model deployed in Azure AI Foundry.
* API keys and endpoints configured in `src/main/resources/application.properties`

## Run the application

```
./mvnw spring-boot:run
```

## Test the application

```
http :8080

HTTP/1.1 200 
Connection: keep-alive
Content-Length: 227
Content-Type: text/plain;charset=UTF-8
Date: Tue, 11 Apr 2025 08:05:00 GMT
Keep-Alive: timeout=60

Hello! I'm OpenAI's ChatGPT, an advanced AI language model designed to assist with
information, answer questions, and provide guidance on a wide range of topics.
Think of me as a helpful virtual assistant or conversational partner.
How can I assist you today? 😊
```

## References

* [Spring AI Azure OpenAI Chat](https://docs.spring.io/spring-ai/reference/api/chat/azure-openai-chat.html)
* [Azure Portal](https://portal.azure.com)
* [Azure AI Foundry](https://ai.azure.com/resource/playground)
* [Azure OpenAI Service models](https://learn.microsoft.com/en-gb/azure/ai-services/openai/concepts/models)
* [Get started with Spring AI and Azure OpenAI](https://nevenc.com/get-started-with-spring-ai-and-azure-openai)
