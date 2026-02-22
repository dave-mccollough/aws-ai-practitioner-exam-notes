# Prompt Performance Optimization

- System Prompts
  - How the model should behave and reply
- Temperature
  - 0 or 1
  - Creativity of models output
    - Low (ex. 0.2)
      - Outputs are more conservative, repetative and focused on most likely response
    - High (ex. 0.99)
      - Outputs are more diverse, creative and unpredictable
- Top P
  - 0 or 1
    - Low P (ex. 0.25)
      - Consider 25% of most likely words
      - Will make a more coherent response
    - High P (ex. 0.99)
      - Consider a broad range of words
      - Possibly more creative and diverse output

- Top K
  - Limits the number of probable words
    - Low K (ex. 10)
      - More coherent response
      - Less probable words
    - High K (ex. 500)
      - More probable words
      - More creative and diverse response

- Length
  - Maximum length of answer

- Stop Sequences
  - Tokens that signal the models to stop generating output

- Prompt Latency
  - Latency is how fast the model responds
  - Impacted by:
    - Model size
    - Model type
    - Number of tokens in input
      - Bigger = slower
    - Number of tokens in output
      - Bigger = slower
  - Latency is not impacted by Top K, Top P, or Temperature