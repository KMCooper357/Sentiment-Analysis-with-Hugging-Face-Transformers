# Sentiment-Analysis-with-Hugging-Face-Transformers

#  Image Caption Generator

A simple beginner-friendly Hugging Face project that generates captions for images using the **BLIP** (Bootstrapping Language-Image Pretraining) model.  
Built with [Transformers](https://huggingface.co/docs/transformers/index), [PyTorch](https://pytorch.org/), and [Gradio](https://gradio.app/).

---

##  Features
- Upload or drag-and-drop any image.
- AI generates a short, human-like description.
- Works locally or can be deployed on **Hugging Face Spaces** for free.
- Uses the pretrained model [`Salesforce/blip-image-captioning-base`](https://huggingface.co/Salesforce/blip-image-captioning-base).

---

##  Installation

1. Clone this repository:
```bash
git clone https://github.com/your-username/image-caption-generator.git
cd image-caption-generator
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
requirements.txt

nginx
Copy
Edit
transformers
torch
pillow
gradio
🖥 Usage
Run the app locally:

bash
Copy
Edit
python app.py
Open the local URL shown in your terminal to use the app in your browser.

 Deploy to Hugging Face Spaces
Create a free account at huggingface.co.

Create a New Space → Select Gradio.

Upload:

app.py

requirements.txt

README.md

Hugging Face will build and host the app for free.



How It Works
Processor: Converts images into model-friendly tensors.

Model: Generates captions from visual features.

Gradio: Creates an interactive drag-and-drop interface.

