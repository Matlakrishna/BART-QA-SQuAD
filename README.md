# BART-QA-SQuAD
BART Q/A Model – A fine-tuned facebook/bart-large model on SQuAD v1.1 for extractive and abstractive question answering. Uses Hugging Face Transformers, PyTorch, and NLP preprocessing for generating accurate answers from given context.

Features:
Fine-Tuned BART Model – Uses SQuAD v1.1 for high-accuracy Q&A.
Extractive & Abstractive QA – Provides both direct extractions and paraphrased answers.
Hugging Face Integration – Uses Transformers API for seamless model deployment.
Preprocessing Pipeline – Tokenization, padding, and dataset preparation.
Interactive Inference – Query the model with custom questions.

Tech Stack:
Language: Python 
Libraries: PyTorch, Hugging Face Transformers, NumPy, Pandas, Tokenizers
Dataset: SQuAD v1.1 (Stanford Question Answering Dataset)

Model Workflow:
Load Dataset – Download and preprocess SQuAD v1.1.
Fine-Tune BART – Train using Hugging Face Transformers and PyTorch.
Evaluate Performance – Compute metrics like exact match (EM) and F1-score.
Inference – Ask custom questions and receive generated answers.

