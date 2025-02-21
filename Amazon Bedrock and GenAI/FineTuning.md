# Fine Tuning a Model
- Adapt a copy of a foundation model with your own data
- Fine-tuning will change the weights of the
base foundation model
- Training data must:
    - Adhere to a specific format
    - Be stored in Amazon S3
- You must use “Provisioned Throughput”
to use a fine-tuned model
- Note: not all models can be fine-tuned

## Instruction Based Fine Tuning
- Improves the performance of a pre-trained FM on domain specific taskss
- = further trained on a particular field or area of knowledge
- Instruction based fine tuning uses **labeled exampless** that are **prompt-responses pairs.**

### Single-Turrn Messaging
- Part of instruction-based fine-tuning
- system (optional) : context for the conversation.
- messages : An array of message objects, each containing:
    - role : Either user or assistant
    - content : The text content of the message

### Multi Turn Messaging

- To provide instructionbased fine tuning for a conversation (vs SingleTurn Messaging)
- Chatbots = multi-turn environment
- You must alternate between “user” and “assistant” roles

## Continued Pre-training
- Provide **unlabeled data** to continue the training of an FM.
- Alsso called **domain-adaptation fine-tuning**, to make a model expert in a specific domain
- For example: feeding the entire AWS doc to a model to make it an expert on AWS
- Good to feed industry-specific terminology into a model.
- Can continue to train the model as more data becomes available.


## Good to know
- Re-training an FM requires a higher budget
- **Instruction-based fine-tuning is usually cheaper as computations are
less intense and the amount of data required usually less**
- It also requires experienced ML engineers to perform the task
- You must prepare the data, do the fine-tuning, evaluate the model
- Running a fine-tuned model is also more expensive (provisioned
throughput)

## Transfer Learning
– the broader concept of reusing a pre-trained model to adapt it to a new related task
- Widely used for image classification
- And for NLP (models like BERT and GPT)
- Can appear in the exam as a general ML concept
- Fine-tuning is a specific kind of transfer learning


