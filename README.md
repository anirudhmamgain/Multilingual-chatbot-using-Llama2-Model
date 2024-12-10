# Multilingual-chatbot-using-Llama2-Model
This repository contains the implementation of a multilingual chatbot built by fine-tuning the pre-trained Llama 2 model on the OpenAssistant-Guanaco dataset. The chatbot supports interaction in 35 different languages, making it a versatile tool for global communication.

Features

	•	Fine-Tuned Llama 2: Adapted the base Llama 2 model using a high-quality open-source dataset for enhanced performance.
	•	Parameter-Efficient Fine-Tuning: Leveraged techniques like QLoRA and LoRA for efficient training in low-resource settings.
	•	Custom Dataset Preparation: Preprocessed the OpenAssistant-Guanaco dataset to create a tailored training dataset for the chatbot.
	•	Multilingual Support: The chatbot can seamlessly interact in 35 languages, enabling diverse use cases.
	•	Text Generation Pipeline: Implemented a robust pipeline for real-time text generation and interaction.

Technical Overview

	1.	Model Fine-Tuning
	•	Fine-tuned the pre-trained Llama 2 model on the OpenAssistant-Guanaco dataset.
	•	Used QLoRA (Quantized Low-Rank Adaptation) and LoRA (Low-Rank Adaptation) to optimize resource usage during training.
	2.	Dataset Preparation
	•	Customized the OpenAssistant-Guanaco dataset to align with the project’s requirements.
	•	Ensured the dataset includes multilingual conversational data for diverse language support.
	3.	Multilingual Chatbot Development
	•	Developed a pipeline for text generation using the fine-tuned Llama 2 model.
	•	Enabled the chatbot to support 35 languages for a wide range of conversational needs.

