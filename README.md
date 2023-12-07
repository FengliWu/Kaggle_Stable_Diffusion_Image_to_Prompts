# Kaggle_Stable_Diffusion_Image_to_Prompts

## Description
This project is for Kaggle - Stable Diffusion - Image to Prompts competition.

## Key Features
- Utilized open-source pre-trained language model to generate prompt texts for Stable Diffusion imaging
- Filtered prompt text data based on similarity of text vectors
- Froze layers of ConvNext-XXLarge pre-trained model in OpenCLIP for model training

## Tech Stack
- Data Processing: Python - Pandas, Numpy
- Modeling: Python - PyTorch, OpenCLIP, Transformer

## Project Structure
```
Kaggle - Stable Diffusion - Image to Prompts
├── src/
|   ├── gpu_pipeline.ipynb
|   ├── prompts_generation_pipeline.ipynb
|   ├── stable_diffusion_littleboat_infer_script.ipynb
|   ├── stable_diffusion_prompts_sim_filter_on_faiss.ipynb
|   └── train_convnext_xxlarge_littleboat_on3000k_size512.py
├── requirements.txt
├── README.md
└── LICENSE
```

Feel free to open issues and pull requests to contribute!
