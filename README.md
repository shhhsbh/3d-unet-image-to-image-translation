# 3D U-Net for MRI to CT Translation
Master’s project on 3D U-Net for iMRI to CT translation

This repository contains the implementation of a **3D U-Net** model for translating MRI scans into CT scans.  
The project was trained and evaluated on the **SynthRAD2023** public dataset.

---

Links :
[SynthRAD2023 Dataset](https://zenodo.org/records/7260705)   
[![Hugging Face](https://img.shields.io/badge/Demo-HuggingFace-yellow.svg)](https://huggingface.co/spaces/jihane12/ct-mri_translation)


## 📂 Repository Structure
- `3D_UNet_MRI_CT_Translation.ipynb` → Main training and evaluation code notebook  
- `models/` → Saved model checkpoints (`.pt` files)  
- `results/` → Evaluation metrics and visual results  
- `HUGGINGFACE_LINK.txt` → Direct link to interactive demo and project files on Hugging Face  
- `README.md` → Project description  

---

## 📊 Results
- **Test Loss (MAE):** `0.0355 ± 0.0092`  
- **PSNR:** `27.92 ± 2.23 dB`  
- **SSIM:** `0.9221 ± 0.0380`  

---

## 🚀 Hugging Face Space
An interactive demo and project files are available on **Hugging Face Spaces**:  

👉 See `HUGGINGFACE_LINK.txt` in this repository.  

On Hugging Face, you will find:  
- **`app.py`** → Inference script for running the model  
- **Model weights** (`epoch_9.pt`, `epoch_10.pt`)  
- **Utilities** (`unet3d.py`, `utils.py`)  
- **`requirements.txt`** → Dependencies for the demo  
- **Interactive interface** → Try MRI → CT translation online  

---

## 📦 Requirements
Install the dependencies with:
```bash
pip install -r requirements.txt
