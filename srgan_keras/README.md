## Using SRGANs to Generate Photo-Realistic Images

Keras implementation of "Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network"
Migrate to tensorflow-gpu 2,1 and add argparse

Python 3.6
tensorflow-gpu 2.1

Steps to set up the project:
1. Create a python3 virtual environment and activate it
2. Install dependencies using "pip install -r requirements.txt"
3. Create essential folders like 1. logs 2. results 3. data
4. Download 'img_align_celeba.zip' from "https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg"
5. Train the model by executing "python3 run.py --mode training"
6. "python3 run.py --mode predict"
