# GenerativeAI_AWS
Generative AI with LLM using AWS.

# Learning From This course 

## Week 1:

1.Introduction to Generative AI and Large Language Models (LLMs)
2.Understanding the transformer architecture that powers LLMs
3.Training and fine-tuning LLMs for specific use cases
4.Optimizing the model's objective function across dataset size, compute budget, and inference requirements
5.Exploring the challenges and opportunities of generative AI in businesses

## Week 2:

1.Multitask fine-tuning and its benefits
2.Avoiding catastrophic forgetting during fine-tuning
3.Parameter efficient fine-tuning (PEFT) as an alternative to full fine-tuning
4.Exploring different use cases of large language models
5.Evaluating and choosing the right model size for specific applications

## Week 3:

1.Reinforcement Learning from Human Feedback (RLHF) to align models with human values
2.Using LLMs as reasoning engines and creating agents
3.Responsible AI and the importance of ethical considerations
4.Evaluating model performance and alignment with human preferences
5.Optimizing models for deployment and integrating them into applications
6.Overcoming limitations of LLMs through advanced techniques

# High level Overview of Lab work and learning from Hands-on

## Lab 1:

This lab focuses on summarizing dialogues using the Flan-T5 model.
You will learn how to load the Dialogue Sum dataset and use PyTorch and the Transformers library for training and fine-tuning the model.
The lab provides step-by-step instructions on setting up the environment and installing the necessary libraries.
You will gain hands-on experience with PyTorch data loading and working with large language models.

## Lab 2:

In this lab, you will explore fine-tuning the Flan-T5 model using Parameter-Efficient Fine-Tuning (PEFT) with prompt instructions.
The lab guides you through the process of modifying the weights of the Flan-T5 model for your specific summarization task.
You will learn how to set up the environment using AWS SageMaker and install the required libraries.
The lab covers torchdata and evaluates libraries for PyTorch data loading and calculating the Rouge score.

## Lab 3:

Lab 3 focuses on memory optimization techniques for training large language models.
You will learn about the challenges of memory usage when training LLMs and the need for optimization.
The lab explores quantization as a technique to reduce memory requirements and explains different precision formats.
You will gain insights into the trade-offs between memory and performance when using different precision formats.
