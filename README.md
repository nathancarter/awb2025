# Using AI in Python through HuggingFace Transformers

This repository contains materials for the AI workshop [Nathan Carter](https://faculty.bentley.edu/profile/ncarter) delivered at the 2025 [Analytics Without Borders conference](https://www.bentley.edu/centers/cads/dart/analytics-without-borders) at [Bentley University](http://www.bentley.edu).

## :bulb: Big Idea #1: AI is just functions.

### Exercise 1: Model categories

 - On the [HuggingFace website](https://huggingface.co/), browse the [models list](https://huggingface.co/models).
 - Find at least one model category that you recognize and know what it means.
 - Find at least one model category that you don’t recognize and would like to know what it means.

You can learn about new model categories at [HuggingFace > Docs > Tasks](https://huggingface.co/tasks)

### Colab notebook 1: Sentiment analysis

 - [A sentiment analysis displayed using Gradio](https://colab.research.google.com/drive/1yIQfGr0T6kL3bEZ7tWTGNMKboLGvpLtm?usp=sharing)

### Colab notebook 2: Question answering

 - [Calling a Question-Answering model in a loop for feature engineering](https://colab.research.google.com/drive/1S2RyyNRR_7lJGv8i_aRWrbVMl86G8Deo?usp=sharing)

## :bulb: Big Idea #2: Model + Interface = Product

### Exercise 2: An inference endpoint for image generation

 - Visit the [FLUX.1-dev model card](https://huggingface.co/black-forest-labs/FLUX.1-dev).
 - Open [the first "space" for interacting with it](https://huggingface.co/spaces/black-forest-labs/FLUX.1-dev).
 - Create any image.

## :bulb: Big Idea #3: Training data matters

### Colab notebook 3: Text generation

 - [A small chatbot loaded into Colab answering a freeform question](https://colab.research.google.com/drive/1V1wRIb2cSqsWIzX1_auAYr3hFO5nAie2?usp=sharing)
 - Warning: This code will probably execute quite slowly.

### Experiment: What can a small chatbot do?

 - Use Colab notebook 3 to ask a question to TinyLlama 1.1B Chat v1.0.
 - [Use this Padlet](https://bentleyu.padlet.org/ncarter80/what-does-tinyllama-1-1b-know-7bw117qecj9f8u04) to share whether it knew the answer to your question not.

### Colab notebook 3 Revisited: JSON generation

 - [The same small chatbot from above, now answering a structured question](https://colab.research.google.com/drive/1lOgtBLx_U7T37T0-wZrZNteQI4LA-_Q3?usp=sharing)
 - Warning: This code will probably execute quite slowly.

## :arrow_right_hook: Digression...

### Exercise 3: How can we use Kokoro from Python?

 - Investigate [the hexgrad/Kokoro-82M text-to-speech model card](https://huggingface.co/hexgrad/Kokoro-82M).
 - It does not use the HuggingFace Transformers library, so it's not as easy to access from Python.
 - Can you find instructions for how to do so?
 - Do those instructions work if you try them in Google Colab?

### Colab notebook 4: Kokoro

 - [This notebook is the solution to the exercise given above.](https://colab.research.google.com/drive/15BftVIs9GS4n_glHA2jI16jJabxu3AgA?usp=sharing)

## :bulb: Big Idea #4: There is not one right answer.

### Example models of various sizes

 - GPT-4 has an estimated 1.76T parameters, but the model is not freely available (see [Wikipedia](https://en.wikipedia.org/wiki/GPT-4))
 - GPT-3 has 175B parameters, but the model is not freely available (see [Wikipedia](https://en.wikipedia.org/wiki/GPT-3))
 - Good LLMs in 2025 typically have 70B parameter variants, such as: [Meta's Llama 3.3 (70B Instruct variant, on HuggingFace)](https://huggingface.co/meta-llama/Llama-3.3-70B-Instruct)
 - Many common LLMs have 7B parameter variants, such as: [trillionlabs/Trillion-7B-preview on HuggingFace](https://huggingface.co/trillionlabs/Trillion-7B-preview)
 - TinyLlama-1.1B-Chat, 1.1B parameters: [TinyLlama/TinyLlama-1.1B-Chat-v1.0 on HuggingFace](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
 - Tiny Question-Answering model, 81.5M parameters: [deepset/tinyroberta-squad2 on HuggingFace](https://huggingface.co/deepset/tinyroberta-squad2)

### High-end hardware mentioned in the talk

 - [NVIDIA DGX Station](https://www.nvidia.com/en-us/products/workstations/dgx-station/)
 - [Apple Mac Studio M3 Ultra](https://www.apple.com/newsroom/2025/03/apple-unveils-new-mac-studio-the-most-powerful-mac-ever/)

### LLM Leaderboards mentioned in the talk

 - [Example leaderboard: Open LLM Leaderboard on HuggingFace Spaces](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard#/)
 - [Example collection: Clémentine Fourrier's collection of leaderboards](https://huggingface.co/collections/clefourrier/leaderboards-and-benchmarks-64f99d2e11e92ca5568a7cce) (a HuggingFace staff member)

### Colab notebook 5: Gemini API

 - Before you use the notebook, you'll need a Gemini API key: [Get one from Google here.](https://aistudio.google.com/app/apikey)
 - [Notebook demonstrating how to call the Gemini API](https://colab.research.google.com/drive/1m_w1X2_ePX6sfgaDcL1omNrrIdybfaZL?usp=sharing)
 - [Prompt Engineering for Developers Course on deeplearning.ai](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/), by Isa Fulford and Andrew Ng, teaches how to use OpenAI's API and how to prompt smartly
