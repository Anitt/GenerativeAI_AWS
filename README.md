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

In Lab 1, you will work with a dataset of conversations and learn how to summarize dialogues using the Flan-T5 model.
You will use PyTorch and the Transformers library to load the dataset and perform the summarization task.
The lab provides step-by-step instructions on how to install the necessary libraries and load the dataset.
You will learn about the Dialogue Sum dataset and how to use it for training and fine-tuning the Flan-T5 model.
The lab also covers the basics of PyTorch data loading and introduces you to the Transformers library for working with large language models.

## Lab 2:

Lab 2 focuses on fine-tuning the Flan-T5 model using Parameter-Efficient Fine-Tuning (PEFT) with prompt instructions.
You will learn how to further tune the Flan-T5 model by providing specific prompts for your summarization task.
The lab provides instructions on setting up the environment using AWS SageMaker and installing the necessary libraries.
You will explore the torchdata library for PyTorch data loading and the evaluates library for calculating the Rouge score.
The lab guides you through the process of fine-tuning the Flan-T5 model and modifying its weights for your specific summarization task.

## Lab 3:

In Lab 3, you will learn about memory optimization techniques for training large language models.
The lab covers the challenges of running out of memory when training LLMs and the need for memory optimization.
You will explore quantization as a technique to reduce the memory required to store and train LLMs.
The lab explains the concept of quantization and its impact on model precision and memory footprint.
You will learn about different precision formats such as FP32, FP16, and BFLOAT16, and their trade-offs in terms of memory and performance.
These labs provide hands-on experience with training and fine-tuning large language models, as well as optimizing memory usage. They offer practical insights into working with LLMs and applying them to real-world tasks
