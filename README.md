# CLIP Experimentation

## Model Infomation
[[OpenAI Blog Post]](https://openai.com/blog/clip/) [[Original Paper]](https://arxiv.org/abs/2103.00020)

"CLIP (Contrastive Language-Image Pre-Training) is a neural network trained on a variety of (image, text) pairs. It can be instructed in natural language to predict the most relevant text snippet, given an image, without directly optimizing for the task, similarly to the zero-shot capabilities of GPT-2 and 3. We found CLIP matches the performance of the original ResNet50 on ImageNet “zero-shot” without using any of the original 1.28M labeled examples, overcoming several major challenges in computer vision." - OpenAI 2021

### Approach
![CLIP](presentation_images/CLIP.png)

## My Experimentation
1. Using CLIP as a way of storage meta-data
2. Prompt engineering to annotate scenes
3. Unlabelled image search
4. Exploration dimensionality reduction

Please explote the notebooks for further explaination.

## Setup
- Clone this repository:
  - ```git clone https://github.com/kelvinducray/CLIP-experimentation.git && cd CLIP-experimentation```
- Clone this repository for the sample ImageNet images:
  - ```git clone https://github.com/EliSchwartz/imagenet-sample-images.git ./data/imagenet_sample```
- Create a new conda environment with the required dependencies and activate it:
  - ```conda env create -f environment.yml```
- Then run:
  - ```conda activate clip && jupyter notebook```
