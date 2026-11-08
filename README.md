# Preface

Large language models (LLMs) are taking over the world. Students use them to study, professionals use them to write and analyze, and many people now turn to them for advice about their health, their money, and their relationships. Yet most of us have little idea how these systems actually work. That gap leads some people to trust them far too much and others to dismiss them entirely.

This book is about closing that gap. Its goal is AI literacy: readers should get a practical understanding how to use these tools well, to know when to trust them and when not to, and to think about what they mean for society. It is not a technical book. There are no equations or code, and no background in computer science is assumed. Instead, each chapter builds a simple mental model of one aspect of how LLMs work and then draws out what that means for you as a user.

The central idea, introduced in Chapter 1 and returned to throughout, is that an LLM is a very good guesser. It produces text by predicting one plausible word after another, not by looking up facts or understanding meaning. Once you understand that, many of the puzzling behaviors of these systems (confident fabrications, flattering agreement, forgetfulness) become clear.

This book is not pro- or anti-AI.  It’s simply an explanation of how they work and how they fail.  

AI disclosure: I produced this by first recording lectures from my ATMO 215 class from Fall of 2025 and then asking AI to convert transcripts of the class into a textbook.  I then edited the files by hand to fix errors and smooth out rough spots.  I also added some new material and deleted other sections that I decided were not germane.

## What's in this book

- **Chapter 1: Stochastic parrots.** Explains that LLMs are sophisticated autocomplete engines that build a response by repeatedly sampling the next word from a probability distribution, and describes how pre-training, fine-tuning, and human feedback turn a raw text predictor into a helpful chatbot.
- **Chapter 2: Hallucinations.** Shows why LLMs sometimes state falsehoods with complete confidence, why this is a built-in consequence of how they work rather than a fixable bug, and which kinds of claims (dates, statistics, citations, niche facts) you should always verify.
- **Chapter 3: Personality mirroring and the illusion of understanding.** Explains how chatbots echo your tone and drift toward agreeing with you, and why this statistical mirroring can feel like empathy and understanding when there is none.
- **Chapter 4: Reasoning models.** Describes how "thinking" models work through a problem on a hidden scratchpad and check their own work before answering, why that helps on math, coding, and logic, and how to decide how much thinking a question deserves.
- **Chapter 5: Agentic AI.** Introduces AI agents, which go beyond answering questions to take actions in the world, and explains the risks that come with that power, including the alignment problem: an agent may do exactly what you said rather than what you meant.
- **Chapter 6: The context window and memory.** Explains that an LLM has no memory of its own and simply rereads the entire conversation each time it responds, what happens when a conversation outgrows the context window, and how memory features and custom instructions work.
- **Chapter 7: Retrieval-Augmented Generation.** Explains how RAG systems ground an LLM's answers in a collection of documents you supply, reducing hallucinations and giving you citations you can check.
- **Chapter 8: Ethics — bias, privacy, and intellectual property.** Examines the biases LLMs absorb from human text, what happens to the information you type into them, and the unresolved copyright battles over training data. It also discusses the environmental issues of AI.

If you have any questions or comments, please email me at adessler@tamu.edu.

Andrew Dessler
College Station, TX

## License

© 2026 Andrew Dessler. This work is licensed under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/) (CC BY 4.0). See [LICENSE](LICENSE) for the full text.
