# Techniques

## Zero-Shot Prompting
- Present a task to the model without providing examples or explicit training for that specific task
- You fully rely on the model’s general knowledge
- The larger and more capable the FM, the more likely you’ll get good results
## Few-Shots Prompting or Single-shot
- Provide examples of a task to the model to guide its output
- We provide a “few shots” to the model to perform the task
## Chain of Thought Prompting
- Divide the task into a sequence of reasoning steps, leading to more structure and coherence
- Using a sentence like “Think step by step” helps
- Helpful when solving a problem as a human usually requires several steps
- Can be combined with Zero-Shot or Few-Shots Prompting