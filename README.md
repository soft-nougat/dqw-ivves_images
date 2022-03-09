# Welcome to the DQW Image app repository! 🖼️

This repo contains the DQW Images streamlit app code, however, the streamlit apps have been split into 5 for maintenance purposes:

- [Main Streamlit app 📊](https://share.streamlit.io/soft-nougat/dqw-ivves/app.py)
- [Tabular Data Section 🏗️](https://share.streamlit.io/soft-nougat/dqw-ivves_structured/main/app.py)
- [Audio Data Section 🎶](https://share.streamlit.io/soft-nougat/dqw-ivves_audio/main/app.py)
- [Text Data Section 📚](https://share.streamlit.io/soft-nougat/dqw-ivves_text/main/app.py)
- [Image Data Section 🖼️](https://share.streamlit.io/soft-nougat/dqw-ivves_images/main/app.py)


The packages used in the application are in the table below.

| App section                |     Description    |     Visualisation    |     Selection    |     Package             |
|----------------------------|--------------------|----------------------|------------------|-------------------------|
|     Image                  |          x         |           x          |                  |     [Pillow](https://github.com/python-pillow/Pillow)              |


## Unstructured data - images

Key points addressed:
- EDA of images
- Augmentation

## Try it out yourself!

Demo files have been provided in the [/demo_data]() folder. 
Try out the app with them.

## How to run locally

1.	Installation process:

    Create virtual environment and activate it - https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
    
    Clone or download files from this repo
    
    Run pip install -r requirements.txt
    
    Run streamlit app.py to launch app

2.	Software dependencies:

    In requirements.txt

3.	Latest releases

    Use app.py