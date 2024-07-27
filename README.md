# Text-Summarisation-and-Extraction

#Text Summarization

Text summarization is the process of condensing a piece of text to a shorter version, retaining the most important information. There are two main types of text summarization:

Extractive Summarization: Selecting important sentences or phrases from the original text and concatenating them to create a summary.
Abstractive Summarization: Generating new sentences that capture the essence of the original text, similar to how a human might summarize.

#Deep Learning for Summarization

Deep learning models, particularly sequence-to-sequence (Seq2Seq) models, are commonly used for summarization tasks. These models typically consist of an encoder and a decoder:

Encoder: Processes the input text and encodes it into a fixed-size context vector.
Decoder: Generates the summary from the context vector.
Attention mechanisms are often incorporated to allow the model to focus on different parts of the input text at each decoding step.

#Workflow

#Data Preparation
Loading Data: The dataset is loaded, containing pairs of original text and corresponding summaries.
Preprocessing: Text is tokenized, and padding is applied to ensure uniform input sizes.

#Model Building

Encoder-Decoder Architecture: The model consists of an encoder to process the input text and a decoder to generate the summary.
Attention Mechanism: Attention layers are added to improve the performance by focusing on relevant parts of the input during decoding.

#Training
The model is trained on the dataset using an loss function i.e. categorical cross-entropy and optimizer Adam.

#Evaluation
The model's performance is evaluated on a validation set to monitor overfitting and generalization.

#Inference
The trained model is used to generate summaries for new, unseen texts.

![Unknown](https://github.com/user-attachments/assets/127e5ed7-317c-4a36-a1f1-57bd1b8ad742)
