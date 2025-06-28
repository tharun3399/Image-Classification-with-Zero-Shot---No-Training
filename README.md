# Image-Classification-with-Zero-Shot---No-Training
A Jupyter Notebook demonstrating zero-shot image classification using OpenAI's CLIP model with custom text prompts.

🧠 CLIP Image Classification with Zero-Shot Learning
This Jupyter Notebook demonstrates how to use OpenAI's CLIP (Contrastive Language–Image Pre-training) model for zero-shot image classification. Instead of relying on traditional supervised learning with labeled datasets, CLIP leverages natural language to perform classification — making it incredibly flexible and useful for a wide range of real-world applications.

📌 Features:
Utilizes a pre-trained CLIP model from openai/clip-vit-base-patch32

Supports zero-shot predictions using a list of class names (text prompts)

Visualizes input images and displays prediction results

No model training required — plug and play classification

🔧 Requirements:

processors, model

torch

PIL

matplotlib

📸 Example Use Case:
Upload an image and classify it into custom categories such as:

["a photo of a cat", "a photo of a dog", "a photo of a zebra crossing", "a photo of a bus"]

The model will rank the text prompts based on the image content.
