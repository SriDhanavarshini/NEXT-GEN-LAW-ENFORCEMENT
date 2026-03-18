# NEXT-GEN-LAW-ENFORCEMENT
#  GAN-Based Image Generation System

##  Overview
This project implements a **Generative Adversarial Network (GAN)** to generate realistic images. It includes modules for dataset handling, model training, perceptual loss, and image generation.

---

##  Project Structure
```
project/

├── data/                # Dataset folder
├── dataset.py           # Dataset loading and preprocessing
├── gan_model.py         # Generator and Discriminator models
├── generate.py          # Script to generate images
├── perceptual_loss.py   # Perceptual loss implementation
├── text_encoder.py      # Text encoding (for conditional GAN)
├── train.py             # Training script
├── requirements.txt     # Dependencies
```

---

##  Installation

1. Clone the repository:
```bash
git clone <your-repo-link>
cd <project-folder>
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

---

##  Dataset

- Place your dataset inside the `data/` folder.
- Supported formats: `.jpg`, `.png`
- Ensure images are properly resized (if required by the model).

---

##  Training the Model

Run the following command:

```bash
python train.py
```

This will:
- Load dataset  
- Train Generator and Discriminator  
- Save trained model weights  

---

##  Generate Images

After training, run:

```bash
python generate.py
```

This will generate new images using the trained GAN model.

---

## Model Details

- **Generator**: Converts random noise into realistic images  
- **Discriminator**: Classifies images as real or fake  
- **Loss Function**: Combines adversarial loss with perceptual loss  

---

##  Requirements

Example libraries used:

```
torch
torchvision
numpy
matplotlib
Pillow
```

Install all dependencies using:
```bash
pip install -r requirements.txt
```

---

##  Features

- GAN-based image generation  
- Modular and clean code structure  
- Custom dataset support  
- Improved image quality using perceptual loss  

---

##  Future Improvements

- Add web interface using Flask  
- Improve model performance  
- Implement advanced GAN architectures  
- Real-time image generation  

---

##  Author
**Sri Dhanavarshini**
