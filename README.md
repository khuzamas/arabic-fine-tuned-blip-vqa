# arabic-fine-tuned-blip-vqa

This project fine-tunes the blip-vqa model on a small arabic dataset
Environment: Google Colab T4 GPU runtime

To start, run the following shell commands

```
!pip install git+https://github.com/huggingface/transformers.git@main
```

```
!pip install transformers
```

```
!pip install -q datasets
```
The main code is the arabic-blip2-vqa.py
The images are within the media folder

```
NOTE! ensure importing the media folder within the same project folder. Otherwise, the path for each image in the dataset must be changed accordingly
```
