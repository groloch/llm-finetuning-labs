# LLM Finetuning Labs

## Overview

Have you ever wanted to fine-tune a LLM, not knowing where to start ? 
Or maybe you just want to get into LLM fine-tuning ?
Or are you passionate about NLP, AI, LLMs, ... ?
Perhaps simply curious ?

This repo is made for you !

This repo contains labs to help you understand LLM fine-tuning, its potential and its limits. 

Each chapter is made of one example notebook, with implementation and explanation of a fine-tuning method, and one do-it-yourself notebook so that you can implement the method by yourself. Some chapters even include some insightful documents !

To begin, take a look at the [introduction](chapters/1.%20Introduction/finetuning_introduction.ipynb) !

## Chapters



## Why fine-tune ?

The 2020s have been a game-changer for artificial intelligence, thanks to the rise of Large Language Models (LLMs). Not long ago, machine learning was mostly about specific tasks like recognizing images, with limited use outside that. But everything changed with the introduction of the Transformer architecture, more powerful computers, and huge datasets. Suddenly, we had models with billions of parameters that could understand and generate human-like text on a massive scale. This shift launched a whole new era for AI.

With these supercharged LLMs, generative AI’s potential was unlocked. Models could now summarize articles, translate languages, create original content, and provide insights in all kinds of fields. Businesses and developers were quick to catch on, and LLMs became the backbone of everything from customer service chatbots to software development tools and even creative writing assistants.

But as powerful as they are, foundation models are still "generalists." They’re not designed for specific fields like law or medicine, and training one from scratch takes enormous amounts of data and computing power. That’s where fine-tuning comes in. It’s a way to customize a general LLM for a specific purpose — and it takes way less time, data, and computing power than training a whole new model from scratch.

Here’s how fine-tuning tackles some big challenges with foundation models:

    Resource Efficiency: Training a new model from scratch needs a ton of resources, but fine-tuning? It can be done on a single GPU.
    Domain Adaptation: Need a model that "speaks" finance, law, or healthcare lingo? Fine-tuning makes models fluent in specialized fields, so they’re more accurate and useful.
    Keeping Up with Change: As your organization learns and grows, fine-tuned models can be updated with new data. This keeps them aligned with your latest knowledge and reduces the risk of "data drift" over time.

Of course, fine-tuning isn’t without its challenges. The biggest risk? Overfitting (when a model gets too focused on the fine-tuning data and "forgets" how to generalize). But beyond that, you’re bound to have a bunch of questions like:

    Which model should I choose? Do I go big (~70B parameters), medium (~7B), or small (<3B)? Am I crazy for even considering tiny models?
    Which fine-tuning method should I use? There are so many options—it’s hard to know which is best.
    How do I pick the right hyperparameters? And seriously, how much does it matter?
    (And about 1,000 other questions that’ll pop up along the way.)

The good news? With the right strategy, fine-tuning lets us get the most out of LLMs. The goal of this lab series is to guide everyone — from curious beginners to home experimenters to seasoned professionals — in mastering the art and science of fine-tuning. Let’s demystify it together! 


## How to

First of all, the labs in this repo focus mainly on LLMs, but some methods should be transferrable to other fields of AI. Therefore, whether you're passionate about AI or simply curious, we hope you have something to learn and to enjoy here.

If I were you, I would pick a notebook (start by the beginning!) and try my best to complete it using information found online. I would then compare my result with the correction. But you're free to do the way you want! I'd still recommend you take time to read all the text in the notebooks (maybe because it took me a lot of time to write it).

All the notebooks are meant to be runnable both locally and on colab. I strongly recommend you use a GPU though, as LLMs are quite compute-intensive. 




