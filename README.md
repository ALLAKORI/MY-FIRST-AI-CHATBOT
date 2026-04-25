# Local LLM and Chatbot Experiments

This repository collects my early experiments with conversational AI using local language models, Chainlit, and LangChain.

It is a learning-oriented project focused on understanding how to build a chatbot step by step: prompt design, streaming responses, conversation memory, and simple web interfaces for chat interactions.

## What Is Inside

- Basic text generation with `ctransformers`
- Prompt engineering examples
- Streaming chatbot responses with `Chainlit`
- Conversation memory examples
- Small `LangChain` demos using a local model

## Main Technologies

- Python
- Chainlit
- LangChain
- CTransformers
- Local GGUF language models

## Project Structure

```text
solutions/
  simple_completion.py
  stream_answer.py
  chainlit_hello_world.py
  chainlit_stream.py
  chainlit_conversational_memory.py
  conversational_memory.py
  langchain/
```

## Getting Started

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run a simple local model example:

```bash
python solutions/simple_completion.py
```

Run the Chainlit streaming demo:

```bash
chainlit run solutions/chainlit_stream.py
```

## Notes

- Some scripts download or load a local GGUF model through Hugging Face and `ctransformers`.
- This repository is intended as an experimentation space rather than a production-ready chatbot application.
