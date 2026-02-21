# Pricing

- On Demand
  - Pay as you go
  - Text Models
    - Charged for every input/output token processed
  - Embedding models
    - Charged for every input token processed
  - Image models
    - Charged for every image generated
  - Works with base models only

- Batch
  - Multiple predictions at a time
    - Output is single file in S3
  - Can provide discount up to 50%

- Provisioned Throughput
  - Purchase model units for a certain time
  - Throughput
    - Max number of input/output tokens processed per minute
  - Works with base, fine tuned and custom models

- Tips to improve model costs
  - Prompt Engineering
    - No model training needed
  - RAG
    - Uses external knowledge - model doesn't need to know everything
    - No foundational model changes
  - Instruction Based Fine Tuning
    - Foundation model is fine tuned with custom instructions
    - Requires additional computation
  - Domain Adaption Fine Tuning
    - Model is trained on domain specific dataset

- Cost details
  - On Demand
    - Unpredictable workloads
    - No long term commitment
  - Batch
    - Up to 50% discount
  - Provisioned Throughput
    - Usually not a cost savings measure
    - Great for reserving capacity
  - Temperature - Top K, Top P
    - No impact on pricing
  - Model Size 
    - Smaller models are usually cheaper
  - Number of input/output tokens
    - Main driver of cost