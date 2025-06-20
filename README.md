# ViT-GPT2 Vision-Language Image Captioning

This project implements an end-to-end image captioning system using a Vision Transformer (ViT) as the encoder and a GPT2-style Transformer decoder. It is trained on the Flickr8k dataset and leverages Hugging Face's `EncoderDecoderModel` for multimodal learning.

## Key Features
- Vision Transformer (ViT) for extracting visual embeddings from images
- GPT2-based Transformer decoder for generating natural language captions
- EncoderDecoderModel integration from Hugging Face Transformers
- Custom PyTorch Dataset for paired image-caption training using Flickr8k
- Use of ViTFeatureExtractor and AutoTokenizer for preprocessing
- Evaluation via BLEU scores and qualitative caption generation
- Modular code for loading images, encoding captions, and training

## Dataset
- **Flickr8k**: Contains 8,000 images, each annotated with 5 unique captions. Used for training and evaluating caption generation performance.

## Tools & Libraries
- Python, PyTorch
- Hugging Face Transformers
- torchvision, PIL, OpenCV (for image loading and visualization)

## Outcome
The ViT-GPT2 captioning system produces coherent and relevant textual descriptions for natural images, and lays the groundwork for more advanced vision-language applications such as VQA and multimodal dialogue systems.
