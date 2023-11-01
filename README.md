# learningpath_chatGPTforDevelopers 
Course: ChatGPT Promt Engineering for Developers

Source or Provider: Coursera

Note: The content here is from the course for me to re-visit without going back to the course.
## Installation required
- !pip install openai

- get openai key
- A note about the backslash: In the course, we are using a backslash \ to make the text fit on the screen without inserting newline '\n' characters. GPT-3 isn't really affected whether you insert newline characters or not. But when working with LLMs in general, you may consider whether newline characters in your prompt may affect the model's performance.
## Guidelines for Prompting
There are two principles: 1) write clear and specific instructions by using i) delimiters, e.g., triple quotes, ; ii) ask for structured output HTML, JSON. 2) Give the model time to think either i) specify the steps to complete a task; ii) instruct the model to work out its own solution before rushing to a conclusion
## How to minimize model limitations 
### Hallucination
the model makes statements that sound plausible but are not true.
To reduce hallucinations: first find relevant information, then answer the question based on the relevant information.
## Iterative Prompt Development
