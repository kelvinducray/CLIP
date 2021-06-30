# CLIP

[[OpenAI Blog Post]](https://openai.com/blog/clip/) [[Original Paper]](https://arxiv.org/abs/2103.00020) [[Model Card]](model-card.md)

"CLIP (Contrastive Language-Image Pre-Training) is a neural network trained on a variety of (image, text) pairs. It can be instructed in natural language to predict the most relevant text snippet, given an image, without directly optimizing for the task, similarly to the zero-shot capabilities of GPT-2 and 3. We found CLIP matches the performance of the original ResNet50 on ImageNet “zero-shot” without using any of the original 1.28M labeled examples, overcoming several major challenges in computer vision." - OpenAI 2021

## Approach
![CLIP](images/CLIP.png)

# My Experimentation
- Using CLIP as a way of storage meta-data
- Prompt engineering
- Unlabelled image search