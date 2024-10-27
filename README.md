# LLM Finetuning Labs

!!! This repo is under active development, many expected features are not there yet but should be here soon !!!


## Introduction to LLM Fine-Tuning: Why fine-tune ?

The rise of Large Language Models (LLMs) in the 2020s has been one of the most exciting transformations in artificial intelligence. Just a few years ago, machine learning was mostly about handling specific tasks like image recognition, with limited applications beyond that. But the introduction of the Transformer architecture, along with unprecedented computing power and vast datasets, changed everything. Suddenly, we could build models with billions of parameters that could process and generate human-like text on an enormous scale—ushering in a new era for AI.

With these powerful LLMs, the potential of generative AI was unlocked. Models could summarize articles, translate languages, generate creative content, and offer insights across different fields. Businesses and developers quickly saw the possibilities, and LLMs became central to a huge range of applications, from customer service chatbots to software development assistants and even creative writing aids.

Despite their immense power, however, foundation models are still generalists. They aren’t tailored to specific domains or specialized fields, and they require enormous data and computing resources to train from scratch. That’s where fine-tuning comes in, allowing us to take these general models and adapt them for specific needs, with far fewer resources and in much less time.

Fine-tuning addresses several key challenges with foundation models:

1. Resource Efficiency: Fine-tuning only requires a fraction of the resources needed to train a new model from scratch, often working effectively on a single GPU.

2. Domain Adaptation: Fine-tuning helps models adapt to specialized topics and language style, like finance, healthcare, or legal language, making them much more accurate in those fields.

3. Evolving with Organizational Knowledge: Fine-tuned models can continuously adapt to new data, keeping them aligned with evolving business knowledge and reducing issues from data drift over time.

While fine-tuning opens up powerful possibilities, it also comes with some risks or questions. The main risk is overfitting (or catastrophic forgetting). On the other hand, there are many questions:

1. What model to choose ? Do I need a big model (~ 70b) or a rather small one (~ 7b) ?

2. What fine-tuning method to choose ? There are so many different ones.

3. What hyper parameters should I choose ? How important is that choice ?

4. (and probably a thousand more)

With a balanced and scientific approach, however, fine-tuning allows us to harness the power of LLMs effectively. The goal of this series of labs is to help everyone (beginners, people experimenting at home or professionals) to get a better understanding of fine-tuning.


## How to

First of all, the labs in this repo focus mainly on LLMs, but some methods should be transferrable to other fields of AI. Therefore, whether you're passionate about LLMs or simply an AI enthusiast, we hope you have something to learn and to enjoy here.

There are many ways to work here and you should use this repo how you see fit. I'd recommend you take time to read all the text in the notebooks (maybe because it took me a lot of time to write it), but if you prefer to simply practice and fill-in-the-gaps, you should do this instead !

All the notebooks are meant to be runnable both locally and on colab. I strongly recommend you use a GPU though, as LLMs are quite compute-intensive. 




