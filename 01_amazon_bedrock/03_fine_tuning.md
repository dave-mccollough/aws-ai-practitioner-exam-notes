# Fine Tuning

- Adapt a copy of a foundation model with your own data
- Fine tuning will change the weights of the base foundation model
- Training data must
  - Adhere to a specific format
  - Be stored in S3
- Not all models can be fine tuned

- Supervised fine tuning
  - Improves model performance for specific tasks
  - Foundation model is further trained on a particular field or area of knowledge
  - Supervised fine tuning uses labeled examples that are input/output pairs

- Reinforcement Fine Tuning
  - Improves foundation model by using feedback based learning
  - You provide the training data 
    - Inputs 
    - Promptes
  - You define the reward function to evaluate responses and judge which responses are good
    - Objective Tasks -> Use AWS Lambda (Python)
    - Subjective Tasks -> Use another model to judge by providing evaluation instructions
  - Model learns iteratively from reward function output scores and will try to achieve higher scores over time

- Distillation
  - Making models smaller and faster
  - Up to 75% less expensive than original models
  - Decrease in accuracy, but may be acceptable
  - Larger models transfer knowledge to smaller models
  - You provide input data (prompts)
  - Produces a lighter model with similar behavior to the original
  - Focuses on efficiency, speed, and cost reduction

- Use Cases
  - Chatbot with specific tone, persona or geared to a specific task
  - Training with more up to date data than the orignal model was trained with
  - Training with exclussive data
    - Email
    - Messages
  - Targeted use cases
    - Categorization
    - Assessing Accuracy

- Notes
  - Retraining a foundation model requires a higher budget
  - Supervised fine tuning is usually cheaper
    - Computations are less intense
    - Less data is required
  - Requires experienced ML engineers to complete the task
  - Data must be prepared
  - Running a fine tuned model is more expensive
    - Run the custom model on demand
    - Purchase provisioned throughput