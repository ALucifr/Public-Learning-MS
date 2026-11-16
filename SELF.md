###Questions###

##Section 1 - Tokens and Vocabulary##

What is a token, and why do LLMs use tokens instead of whole words?
Why might “unbelievable” be split into more than one token?
Why is each token assigned a unique ID number?
Why does the same word, like “a” in “I heard a dog bark loudly at a cat”, get one token ID but appear at different positions?
Roughly how large are the vocabularies of the latest LLMs?

##Section 2 - Tokens and Vocabulary##
What is an embedding, and how is it different from the initial random vector for a token?
What does a transformer’s encoder produce, and what does its decoder produce?
In your own words, what does the attention layer do? Use “I heard a dog bark” as your example.
Why is multi-head attention used instead of a single attention pass?
What is positional encoding, and what would go wrong without it?
Why do “dog” and “puppy” have embeddings pointing in similar directions, but “dog” and “skateboard” don’t?
What does cosine similarity measure, and what range of values can it take?
What is masked attention, and why is it used when training the decoder?

##Section 3 - Tokens and Vocabulary##
Describe step by step how a model completes “When my dog was a...”.
Why is an LLM compared to a cellphone’s predictive text, and where does that comparison break down?
What is the difference between a system prompt and a user prompt? Give an example of each.
Why do chat apps resend the conversation history with every new prompt?
What is a context window, and what happens when a conversation grows beyond it?
Give four ways to improve a prompt, and rewrite “tell me about networks” using all of them.

##Section 4 - Tokens and Vocabulary##
What is a hallucination, and why does it happen given how LLMs generate text?
How does RAG reduce hallucinations? Walk through the travel-expenses example.
What are the three parts of an AI agent? Give one example of a knowledge tool and one action tool.
How is an agent different from a plain chatbot?
What is a multi-agent system, and when would it beat a single agent?

##Section 5 - Tokens and Vocabulary##
Write a Python function cosine_similarity(a, b) without using libraries. Test it on “dog” [10, 3, 2], “puppy” [5, 3, 2], and “car” [-2, -2, 1].
Imagine a tool that answers questions about your college rules. Which parts would use RAG and which would be the LLM alone? What could go wrong?
Name a NOC task, such as checking logs or alerts, that an agent could help with. What tools would it need, and what should it not be allowed to do?
Explain to a classmate in under 100 words how ChatGPT-style models “know” things.



###Answers###

##Section1##

1.token, LLMs use of tokens instead of whole words.

-> 