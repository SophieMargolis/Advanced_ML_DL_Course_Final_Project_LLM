# Advanced_ML_DL_Course_Final_Project_LLM
By: Raz Graider, Dana Braynin, Sophie Margolis and Ran Asanta

In recent years, the rapid expansion of social media platforms and online communities has not only facilitated greater connectivity and communication but has also revealed a darker side: hate speech and online harassment.

In this project we explored the challenge of detecting hate speech using machine learning, NLP techniques, and LLMs for sentiment analysis.<br>
Our focus was on comparing a Keras neural network model to two advanced Large Language Models (LLMs): **Mistral-7b** and **Llama-2-7b** utilizing libraries such as **Hugging Face 🤗, PyTorch, TensorFlow**, and others.<br> The objective was to classify text as offensive or non-offensive (a binary classification task), leveraging three distinct datasets.

**Keras NN vs. Mistral-7b vs. Llama-2-7b**
Our approach involved training a Keras neural network on the entire dataset, which comprised 140,218 rows of text collected from various sources, including Wikipedia forums. However, **the LLMs were fine-tuned using only 0.08% of the training data, utilizing LoRa** (Low-Rank Adaptation). Additionally, we explored the performance of the LLMs with **prompt engineering**.

The results offer insights into hate speech detection. Through our exploration, we gained a deeper understanding of the challenges, strengths, and limitations of each model or approach for this specific task. 
