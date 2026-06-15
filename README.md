# AI Fashion Store Assistant


An AI-powered fashion shopping assistant built using Python, Gradio, and Large Language Models (LLMs). The chatbot simulates a virtual sales assistant that helps customers discover products, answer shopping-related questions, and receive personalized recommendations.

Features

* Interactive chat-based shopping experience
* Conversation memory through chat history
* Product recommendations based on customer queries
* Support for fashion-related items such as:
    * Shirts
    * T-Shirts
    * Jeans
    * Jackets
    * Shoes
    * Sneakers
    * Hats and Caps
    * Accessories
* Context-aware responses using system prompts
* Product availability restrictions
* Real-time streaming responses
* User-friendly Gradio interface

Business Rules

The assistant is designed to operate within a fashion retail environment.

* Only fashion-related products are supported.
* If customers request unavailable items, the chatbot politely informs them and suggests available alternatives.
* Non-fashion requests such as food, beverages, groceries, or restaurant items are not supported.
* The chatbot redirects users toward relevant products available in the store.

Example Conversations

Product Recommendation

User: I need shoes for daily use.

Assistant: I recommend our casual sneakers and lightweight running shoes. They provide comfort for everyday wear and pair well with jeans and t-shirts.

Unavailable Product

User: Do you sell pizza?

Assistant: We currently specialize in fashion products and accessories, so pizza is not available. You may be interested in our sneakers, jackets, hats, or casual wear collections.

Alternative Suggestion

User: Do you have belts?

Assistant: Belts are currently unavailable. However, you can explore our collection of shoes, hats, jackets, and other fashion accessories.

Technologies Used

* Python
* Gradio
* Ollama / OpenAI-Compatible API
* Large Language Models (LLMs)

Project Architecture

1. User enters a query through the Gradio interface.
2. Chat history is maintained for contextual conversations.
3. A system prompt defines store policies and available products.
4. The selected LLM processes the request.
5. The chatbot generates recommendations and responses based on store rules.
6. Responses are streamed back to the user in real time.

Learning Outcomes

This project demonstrates:

* Prompt engineering
* Conversational AI development
* LLM integration with Python
* Chat history management
* Retail assistant chatbot design
* Real-time response streaming using Gradio

Future Enhancements

* Product catalog integration
* Vector database and RAG support
* User authentication
* Shopping cart functionality
* Order tracking
* Personalized recommendations based on customer preferences
