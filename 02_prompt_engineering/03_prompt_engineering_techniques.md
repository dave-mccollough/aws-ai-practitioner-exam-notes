# Prompt Engineering Techniques

- Zero Shot Prompting
  - Present a task to the model without examples or explicit training for the task
  - Fully rely on models knowledge
  - The larger and more capable to model, the more likely you'll get better results

- Few Shots Prompting
  - Provide a few examples of a task to guide the models output
  - If you only provide one example, it's called 'one shot' or 'single shot'

- Chain of thought prompting
  - Divide the task into a sequence of reasoning steps - provides more structure and coherence
  - Use sentances like "think step by step"
  - Helpful when solving a problem
  - Can be combined wth zero-shot or few-shot prompting
