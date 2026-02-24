# Amazon Transcribe

- Convert speech to text
- Uses deep learning process called automatic speech recognition (ASR)
- Automatically removes PII
- Supports automatic language identification for multi-lingual audio
- Use cases
  - Transcribe customer service calls
  - Generate closed captioning and subtitles
  - Generate metadata for media assets

- Improving Transcribe Accuracy
  - Allow Transcribe to capture domain specific or non-standard terms (jargon)
  - Custom Vocabularies (for words)
    - Add specific words, phrases, domain specific terms
      - Brand names, acronyms
    - Improve new word recognition by providing hints
  - Custom lanaguage models (for context)
    - Train Transcribe model on your own domain specific text data
      - Good for transcribing large volumes of domain specific speech
    - Learn the context associated with a given word

- Toxicity Detection
  - ML powered, voice based toxicity detection capability
  - Leverages speech cues, tone, pitch and text based cues
  - Toxicity categories
    - Sexual harrasement
    - Hate speech
    - Threat abuse
    - Profanity
    - Insult
    - Graphic
