# Amazon Comprehend

- Used for natural language processing
- Fully managed and serverless
- Uses machine learning to find insights in and relationships in text
  - Language of the text
  - Extracts key phrases, places, people, brands or events
  - Understands positive and negative text
  - Analyzes text using tokenization and parts of speech
  - Automatically organizes a collection of text files by topic
- Use cases
  - Analyze customer interactions (email)
  - Create and group articles by topics

- Custom Classification
  - Organize documents into categories/classes you define
  - Supports different document types
  - Real time analysis
    - Single document
    - Synchronous
  - Async Analysis
    - Multiple documents (batch)
    - Asyncronous

- Named Entity Recognition (NER)
  - Extract predefined, general purpose entities like people, places, organizations, dates and other standard categories from text

- Custom Entity Recognition
  - Analyze text for specific terms and noun-based phrases
  - Extract terms
    - Policy numbers
    - Phrases
    - Business specifc nomenclature
  - Train model with custom data such as lists of entities and documents that contain them
  - Real time or async analysis