# InsuranceAgent

![Insurance Agent Demo](image.png)

An intelligent AI assistant for an insurance tech company (Insurellm) that leverages a knowledge base to provide accurate and context-aware responses about company employees, products, and other information.

## Features

- Contextually-aware AI responses using OpenAI's GPT models
- Knowledge base integration with dynamic content retrieval
- Interactive Gradio interface for easy interaction
- Automatic context identification based on user queries
- Support for retrieving information about:
  - Employees (HR records, performance history, etc.)
  - Insurance products (Rellm, Markellm, Homellm, Carllm)
  - Company information

## How It Works

1. **Knowledge Base Organization**: The system uses a structured knowledge base organized into different categories:
   - `/knowledge-base/products/` - Information about insurance products
   - `/knowledge-base/employees/` - Employee profiles and HR records
   - `/knowledge-base/contracts/` - Contract information
   - `/knowledge-base/company/` - General company information

2. **Context Retrieval**: When a user asks a question, the system scans the query for keywords that match available knowledge contexts.

3. **Response Generation**: The system uses OpenAI's models (specifically GPT-4o-mini) to generate accurate responses based on the retrieved context.

