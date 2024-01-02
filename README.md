<!-- Project Overview -->
# Fine-tuning BERT for Question Answering

## Overview
BERT (Bidirectional Encoder Representations from Transformers) is a powerful tool for question answering tasks due to its ability to understand contextual information in input text. This project focuses on fine-tuning a BERT model for question answering using a limited dataset for illustration purposes.

## Steps Involved in Fine-tuning
1. **Data Preparation:**
   - Utilized various data annotator tools like Haystack Deepset, Doccano, etc. for larger projects.
   - Handcrafted training data by scraping product descriptions of 12 products using Beautiful Soup.

2. **Define Questions and Answers:**
   - Defined question-answer pairs for each context, ensuring answers are within the context text.

3. **Data Format Conversion:**
   - Transformed training data into the format required by SimpleTransformers for BERT model training.

4. **Setting up Testing Data:**
   - Prepared a separate set of contexts with ground truth question answers for testing.

5. **Training for Fine-tuning:**
   - Installed SimpleTransformers for BERT model fine-tuning.
   - Used the 340M parameter bert-large-uncased BERT model with 25 epochs.

6. **Model Evaluation:**
   - Evaluated the model on the test dataset, achieving satisfactory results.

7. **Model Inference:**
   - Loaded the best model from the training checkpoint.
   - Tested the model with the question "What is the model name of the Samsung smartphone?" and obtained correct results.

<!-- Sources -->
## 🌐 Sources
1. [Hugging Face - Wikipedia](https://en.wikipedia.org/wiki/Hugging_Face)
2. [Build a Smart Question Answering System with Fine-Tuned BERT](https://medium.com/saarthi-ai/build-a-smart-question-answering-system-with-fine-tuned-bert-b586e4cfa5f5)
3. [Fine-Tune Transformer Models For Question Answering On Custom Data](https://towardsdatascience.com/fine-tune-transformer-models-for-question-answering-on-custom-data-513eaac37a80)
</xml>
