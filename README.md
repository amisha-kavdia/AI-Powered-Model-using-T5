**Overview**

This project implements an AI-powered grammar error correction model using the T5 Transformer.
The model is trained on a dataset stored in a JSON file containing incorrect sentences, their corrected versions, and explanations.

**Features**

- Uses T5 (Text-to-Text Transfer Transformer) for grammar correction
- Dataset stored in a JSON file (Incorrect sentence, Correct sentence, Explanation)
- Tokenization and model training using Hugging Face Transformers

**Training Process**

The model is trained by tokenizing the incorrect sentence as input and the corrected sentence as output.
The T5 model learns to map incorrect sentences to their correct form.

**Outcome**

Average BLEU Score: 0.8412
Average ROUGE Score: 1.0000
