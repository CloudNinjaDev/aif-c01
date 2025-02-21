# Prompt Performance Optimization

- **System Prompts** - How the model should behave and reply
- **Temparature(0-1)** - creativity of the model's output
    - Low (ex: 0.2) - outputs are more conservative, repetitive, focused on most likely reponses
    - High (ex: 1.0) - outputs are more diverese, creative and unpredictable, maybe less coherent
- **Top P (0-1)** - no. of words considered
    - Low (ex: 0.25) - consider the 25% most likely words, will make a more coherent response
    - High (ex: 0.99) - consider a broad range of possible words, possibly more creative and diverse output.
- **Top K** - limits the number of probable words i.e. next word
    - Low (ex: 10) - more coherent response, less probable words
    - High (ex: 1.0) - more probable words, more diverse and creative
- **Length** - maximum length of the answer
- **Stop Sequence** - tokens that signal the model to stop generating output.