# 🖼️ Image Captioning using CLIP Model

## 📌 Project Overview

This project demonstrates an AI-based image captioning system using the CLIP (Contrastive Language-Image Pretraining) model from the Sentence Transformers library. The model encodes both images and text into a shared embedding space and compares their similarity to determine the most suitable caption for an image.

Instead of generating captions from scratch, the system selects the caption that best matches the uploaded image from a list of predefined text descriptions.

---

## 🚀 Features

- Image and text embedding using CLIP
- Similarity comparison between image and captions
- Displays the uploaded image
- Predicts the best matching caption
- Easy to understand and beginner-friendly implementation

---

## 🛠️ Technologies Used

- Python
- Sentence Transformers
- CLIP (clip-ViT-B-32)
- NumPy
- Pillow (PIL)
- Matplotlib
- Jupyter Notebook

---

## 📂 Project Structure

```
Image-Captioning/
│
├── image_captioning.ipynb
├── images/
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/your-username/Image-Captioning.git
```

Move to the project folder

```bash
cd Image-Captioning
```

Install the required libraries

```bash
pip install sentence-transformers pillow matplotlib numpy
```

---

## ▶️ How It Works

1. Load the pre-trained CLIP model.
2. Load an input image.
3. Create embeddings for the image and candidate text captions.
4. Compute cosine similarity (or dot product similarity).
5. Select the caption with the highest similarity score.
6. Display the image along with the predicted caption.

---

## 📸 Sample Output

**Input Image:** Peacock

**Predicted Caption:**
> "A beautiful peacock"

---

## 📈 Future Improvements

- Generate captions instead of selecting predefined ones.
- Support custom user-uploaded images.
- Build a web interface using Streamlit or Flask.
- Improve caption accuracy using BLIP or GPT-based image captioning models.
- Add multilingual caption support.

---

Akshaar pandey

---

## 📄 License

This project is for educational and learning purposes.
