---
title: Virtual Try-On Diffusion IEEE Dressify
emoji: 👗
colorFrom: indigo
colorTo: purple
sdk: gradio
sdk_version: 5.6.0
app_file: app.py
pinned: false
short_description: Diffusion-based multi-modal virtual try-on pipeline demo
tags:
    - virtual try-on
    - vton
    - clothing transfer
    - diffusion
    - img2img
    - txt2img
---

# Virtual Try-On Diffusion [VTON-D] by IEEE Dressify

Virtual Try-On Diffusion [VTON-D] by Dressify is a custom diffusion-based pipeline for fast 
and flexible multi-modal virtual try-on. Clothing, avatar and background can be specified by reference images or text 
prompts allowing for clothing transfer, avatar replacement, fashion image generation and other virtual try-on related 
tasks.
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
Create a virtual environment:

bash
Copy code
python -m venv venv
Activate the virtual environment:

Windows:
bash
Copy code
venv\Scripts\activate
macOS/Linux:
bash
Copy code
source venv/bin/activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Run the application:

bash
Copy code
python app.py
Open your browser and navigate to:

arduino
Copy code
http://127.0.0.1:7860


