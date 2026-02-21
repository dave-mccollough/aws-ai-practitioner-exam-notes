# GenAI Concepts

- Tokenization
  - Converting raw text into a sequence of tokens
    - Word-based tokenization
      - Text is split into individual words
    - Sub-word tokenization
      - Spliting words
      - Helpful for long words
  - Try it out
    - https://platform.openai.com/tokenizer

- Context Window
  - Number of tokens an LLM can consider when generating text
  - The larger the context window, the more information and coherence
  - Large context windows require more memory and processing power
  - **First factor to look at when considering a model**

- Embeddings
  - Create vectors out of text, images, audio
    - Vectors are an array of numerical values
  - Vectors have the ability to capture many features for one input token
    - Semantic meaning
    - Syntactic role
    - Sentiment
  - Embedding models can be used to power search applications
  - Words that have a semantic relationship have simiar embeddings