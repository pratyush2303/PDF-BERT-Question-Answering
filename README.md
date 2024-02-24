# Readme Question Answering BERT model

## (A) Project Overview

This project implements a Question-Answering (QA) system utilizing a BERT model to extract answers from small-sized PDF documents. The BERT model processes the input document and question to generate relevant answers. The system leverages pre-trained models like BERT, T5, and similar architectures available from Hugging Face.

## (B) Goal of the Project

This project falls under the category of Natural Language Processing (NLP) and specifically addresses the task of question-answering. It utilizes machine learning techniques and pre-trained language models to understand and extract information from textual documents.

## (C) Working

1) PDF Text Extraction: Extracts text from a PDF document.
2) Question-Answering with BERT: Uses the BERT model for question-answering tasks.
3) Model Initialization and Tokenization: Initializes the BERT model and tokenizer.
4) Answer Extraction: Predicts start and end positions of the answer within the text and extracts the complete sentence containing the answer.
5) Presentation of Answer: Presents the extracted answer to the user.

## (D) Limitations

1) Token Limitation: Due to the token limitations of BERT and similar models, only a restricted amount of text can be processed at a time, posing constraints on the size of the input document.

2) Pre-trained Model Dependency: The reliance on pre-trained models necessitates fine-tuning for specific tasks like question-answering, which demands additional computational resources and labeled datasets.

3) Context Understanding: The models used, including BERT, T5, etc., may struggle with understanding context effectively without fine-tuning, impacting the accuracy of responses.

4) Compute Power and GPU Requirement: Effective utilization of these models requires substantial computational resources, including GPU capabilities.

5) Data Quality and Availability: The availability of high-quality datasets for fine-tuning and evaluation purposes can pose challenges, limiting the system's performance and generalizability.

## (E) Future Solutions

1) Utilization of Large Language Models (LLMs): Advanced models like ChatGPT 3.5, 4, Bard, and Claude offer improved context understanding and can handle larger input token sizes, potentially enhancing the accuracy and precision of the QA system.

2) Techniques for Context Understanding: Employing techniques such as Chain of Thought prompting, zero-shot, one-shot, and few-shot learning, along with instructing fine-tuning, can enhance the model's ability to grasp contextual nuances and deliver more accurate responses.

3) Exploring Alternative Models: Exploring alternative models such as Llama, which offers superior contextual understanding compared to BERT, could provide better performance in question-answering tasks. We could also use Knowledge Distillation if we do not have access to Large Language Models.

4) Integration of Vision-Language Models (VLMs): Utilizing Vision-Language Models like Llava and DALLE for tasks such as image captioning and image generation can extend the capabilities of the system, allowing for multimodal inputs and common-sense reasoning.

5) Video Question-Answering: Extending the system to handle video inputs, similar to the capabilities demonstrated by REKA.ai, can broaden its applicability and utility in real-world scenarios.
