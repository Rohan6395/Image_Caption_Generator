# Image_Caption_Generator
This is Machine Learning Project.

This code is designed to generate captions for images using a pre-trained VisionEncoderDecoderModel from the transformers library. The specific model used here is nlpconnect/vit-gpt2-image-captioning, which combines a Vision Transformer (ViT) for image encoding and GPT-2 for text generation.

I have used Flask to build a web application where users can upload an image, and the caption is displayed on the same page.

Since Colab doesn't expose ports to the internet, so I have used ngrok to tunnel my local server and make it publicly accessible.

ngrok generates a public URL to share but url changes once we refresh our project file. It will again generate new url on running project again.
