## Using SRGANs to Generate Photo-Realistic Images

This project is a repository that transferred https://github.com/PacktPublishing/Generative-Adversarial-Networks-Projects/Chapter05 from CPU run to GPU

Keras implementation of "Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network"

Python 3.6

Steps to set up the project:
1. Create a python3 virtual environment and activate it
2. Install Shapely==1.6.4.post2 & keras-contrib==2.0.8 (01/13/20: these are not installed properly by pip cmd)
```
python -m pip install Shapely-1.6.4.post2-cp36-cp36m-win_amd64.whl 
git clone https://www.github.com/keras-team/keras-contrib.git
cd keras-contrib
python setup.py install
``` 
3. Install dependencies using "pip install -r requirements.txt"
4. Download 'img_align_celeba.zip' from "https://drive.google.com/drive/folders/0B7EVK8r0v71pTUZsaXdaSnZBZzg"
5. create 'data' folder and unzip 'img_align_celeba.zip' then hierarchy is'data/img_align_celeba'
6. Train the model by executing "python3 run.py"
