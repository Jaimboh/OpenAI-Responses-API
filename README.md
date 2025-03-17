# OpenAI Responses API

## What we will cover

1. Introduction
2. Text prompting
3. Conversation states
4. Function calling
5. Structured output
6. Web search
7. Reasoning
8. File search

## Most important things to know

1. **Backward Compatibility**: The Responses API is a superset of Chat Completions - everything you can do with Chat Completions can be done with Responses API, plus additional features.



2. **Key New Features**:
   - Simplified interface for different interaction types
   - Native support for web search capabilities
   - A new `developer` role you can use
   - Improved support for reasoning models
   - Built-in file/vector search functionality
   - Simplified conversation state management

3. **Available Tools**:
   - **Web search**: Include data from the Internet in model response generation
   - **File search**: Search the contents of uploaded files for context when generating a response
   - **Computer use**: Create agentic workflows that enable a model to control a computer interface
   - **Function calling**: Enable the model to call custom code that you define, giving it access to additional data and capabilities


4. **Implementation Considerations**:
   - API structure changes but core AI engineering principles remain the same
   - Features that previously required multiple API calls can now be done in single calls
   - The fundamental patterns of retrieval, tools, and memory management still apply

5. **New Agent SDK**: OpenAI has released a new Agent SDK that will replace [Swarm](https://github.com/openai/swarm/tree/main). This provides a standardized way to build AI agents with the Responses API. Learn more at: https://platform.openai.com/docs/guides/agents

6. **Documentation Resources**:
   - Official OpenAI documentation: https://platform.openai.com/docs/api-reference/responses
