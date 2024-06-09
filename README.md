# Image-Captioning-with-ViT-GPT2
This project implements an image captioning system using a Vision Transformer (ViT) and GPT-2 model. The model takes an image as input and generates a descriptive caption.

Overview-

Image captioning is a challenging task that combines computer vision and natural language processing. This project utilizes a pre-trained VisionEncoderDecoderModel from Hugging Face's Transformers library, specifically the nlpconnect/vit-gpt2-image-captioning model. The system processes input images, extracts feature using a Vision Transformer (ViT), and generates captions using GPT-2.

Features-

Pre-trained Model: Utilizes a pre-trained ViT-GPT2 model for accurate image captioning.
User Interface: A simple web-based interface built with Gradio for uploading images and viewing captions.
GPU Support: Automatically uses GPU if available for faster processing.

Components-

Model Loading: Loads the pre-trained ViT-GPT2 model, image processor, and tokenizer from Hugging Face.
Device Configuration: Configures the device to use GPU if available.
Prediction Function: Processes the uploaded image, extracts features, and generates a caption.
Gradio Interface: Sets up a web interface for uploading images and viewing captions.

