# Model Evaluation

- Automatic Evaluation
  - Evaluate a model for quality control
  - Built in task types
    - Text Summarization
    - Q & A
    - Text Classificatiobn
    - Open ended text generation
  - Bring your own prompt dataset or use built in prompt dataset
  - Scores are calculated automatically
  - Model scores are calculated using various statiscal methods
    - BERTScore

- Benchmark Datasets
  - Collections of data designed specifically for evaluating the performance of a language model
  - Wide range of topics, complexities, linguistic phenomenon
  - Helpful to measure speed, efficiency, accuracy and scalability
  - Some benchmark datasets allow you to detect bias/discrimination against a group of people
  - You can create your own benchmark dataset specific to your business or use case

- Human Evaluation
  - Choose a work team to evaluate
    - Employees
    - Subject matter experts
  - Define metrics and evaluation criteria
    - Thumbs up/thumbs down
    - Ranking
  - Choose from built in tasks or create a custom task

- Automated Metrics
  - ROUGE  
    - Recall Oriented Understudy for Gristing Evaluation
      - Evaluating automatic summurization and machine translation systems
        - ROUGE-N
          - Measure the number of matching n-grams between reference and generated text
        - ROUGE-L
          - Longest common subsesquence between reference and generated text
  - BLEU
    - Bilingual Evaluation Understudy
      - Evaluate the quality of generated text for translations
      - Considers both precision and penalizes too much brevity
      - Looks for a combination of n-grams (1,2,3,4)
  - BERTScore
    - Bi-directional Encoder Representations from Transformers
    - Semantic similaraties between generated text
    - Uses prertained BERT Scores to compare the contextualized embeddings of both texts and computes the cosine similarity between them
    - Capable of capturing more nuance between the texts

- Business Metics for model evaluation
  - User Satisifaction
    - User feedback on model responses
  - Average Revenue Per User
    - Average revenue per user attributed to your GenAI app
  - Cross Domain Performance
    - Measure models ability to perform across different domain tasks
  - Conversion Rate
    - Meausre desired outcomes - purchases
  - Efficiency
    - Evaluate the models performance 