# face_restoration_deploy_flask

## Intrduction

I have developed a Flask application for **GFP-GAN** and run it on flask-ngrok. **GFP-GAN** is AI practical algorithm for real-world face restoration. It can be used to restore your old photos or enhance AI-generated faces. It leverages rich and diverse priors encapsulated in a pre-trained faces *GAN* (Generative Adversarial Network) for blind face restoration.

Source: <a href="https://github.com/TencentARC/GFPGAN">Official Link</a>


## Installation

First, you need to **clone the repo**.
```
git clone https://github.com/JafirDon/face_restoration_deploy_flask.git
cd face_restoration_deploy_flask
```


Install dependent packages. run the following command

```
pip install basicsr
pip install facexlib

pip install -r requirements.txt

python setup.py develop

pip install realesrgan
```

If you run on the **Flask-Ngrok**, run the following command.

```
pip install pyngrok==4.1.1
pip install flask_ngrok

ngrok authtoken <your_auth_token>
```


## Getting Started

First, download the pre-trained model
```
wget https://github.com/TencentARC/GFPGAN/releases/download/v1.3.0/GFPGANv1.3.pth -P experiments/pretrained_models
```

To run the code
```
python run.py
```

## Tutorial
- Google-colab-tutorial: <a href="https://github.com/JafirDon/face_restoration_deploy_flask/blob/main/GFPGAN_Deploy_on_Flask.ipynb">Colab Notebook Link</a>
- Blog: Coming Soon

## License
MIT License
<br>
<br>

### Thank you
