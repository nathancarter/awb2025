# Using AI in Python through HuggingFace Transformers

This repository contains materials for the AI workshop I delivered at the 2025 Analytics Without Borders conference at Bentley University.

 - [HuggingFace website](https://huggingface.co/)
 - Exercise 1: Browse the [HuggingFace models list](https://huggingface.co/models) and find:
    - at least one model category that you recognize and know what it means
    - at least one model category that you don’t recognize and would like to know what it means
 - Learn about new model categories at [HuggingFace > Docs > Tasks](https://huggingface.co/tasks)
 - Exercise 2: FLUX.1-dev by Black Forest Labs
    - [FLUX.1-dev model card](https://huggingface.co/black-forest-labs/FLUX.1-dev)
    - [Online interface](https://huggingface.co/spaces/black-forest-labs/FLUX.1-dev) (in HuggingFace Spaces)
 - [Colab notebook 1](https://colab.research.google.com/drive/1NAh5OBwutWfFSnW47ANjT0zNdSRLaJ1F?usp=sharing) - Example HuggingFace model (for sentiment analysis) on Colab using Gradio
 - [Colab notebook 2](https://colab.research.google.com/drive/1qpmS-QZEnSdGtYw5ATWIctD08j-ERNq7?usp=sharing) - Example HuggingFace model (for text generation) on Colab using transformers
    - Experiment about what TinyLlama 1.1B knows: [Share your results at this Padlet](https://bentleyu.padlet.org/ncarter80/what-does-tinyllama-1-1b-know-7bw117qecj9f8u04)
    - Example of using TinyLlama-1.1B to output [JSON data into a pandas dataframe](https://colab.research.google.com/drive/1IDQVnBAE21uyH6Nhn8REku3Ir0Tukadh?usp=sharing)
 - Example models of various sizes
    - Tiny Question-Answering model, 81.5M parameters: [deepset/tinyroberta-squad2 on HuggingFace](https://huggingface.co/deepset/tinyroberta-squad2)
    - TinyLlama-1.1B-Chat, 1.1B parameters: [TinyLlama/TinyLlama-1.1B-Chat-v1.0 on HuggingFace](https://huggingface.co/TinyLlama/TinyLlama-1.1B-Chat-v1.0)
    - Many common LLMs have 7B parameter variants, such as: [trillionlabs/Trillion-7B-preview on HuggingFace](https://huggingface.co/trillionlabs/Trillion-7B-preview)
    - Good LLMs in 2025 typically have 70B parameter variants, such as: [Meta's Llama 3.3 (70B Instruct variant, on HuggingFace)](https://huggingface.co/meta-llama/Llama-3.3-70B-Instruct)
    - GPT-3 has 175B parameters, but the model is not freely available (see [Wikipedia](https://en.wikipedia.org/wiki/GPT-3))
    - GPT-4 has an estimated 1.76T parameters, but the model is not freely available (see [Wikipedia](https://en.wikipedia.org/wiki/GPT-4))
 - Links to high-end hardware mentioned in the talk
    - [NVIDIA DGX Station](https://www.nvidia.com/en-us/products/workstations/dgx-station/)
    - [Apple Mac Studio M3 Ultra](https://www.apple.com/newsroom/2025/03/apple-unveils-new-mac-studio-the-most-powerful-mac-ever/)
 - LLM Leaderboards:
    - One example: [Open LLM Leaderboard on HuggingFace Spaces](https://huggingface.co/spaces/open-llm-leaderboard/open_llm_leaderboard#/)
    - One collection: [Clémentine Fourrier's collection of leaderboards](https://huggingface.co/collections/clefourrier/leaderboards-and-benchmarks-64f99d2e11e92ca5568a7cce) (a HuggingFace staff member)
