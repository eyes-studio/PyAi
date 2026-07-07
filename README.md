# PyAi

PyAi is a Python library for creating AI systems and neural networks using simple commands.

## About

PyAi is a library designed to make AI development easier and more accessible. It allows users to create, train, and experiment with neural networks without writing complex code.

With PyAi, you can build everything from small AI models to large-scale LLMs. The library provides simple tools for creating neural networks, processing data, and training AI models.

## Developers

***Eyes Studio***

Eyes Studio is an independent, unofficial company with a small team of developers focused on creating AI tools and open-source projects.

## Features

- Create neural networks with just a few commands
- Fast and simple tokenizer for AI models
- Train neural networks on custom information
- Build and experiment with different AI architectures
- Easy-to-use tools for AI development

## example of ai

```bash
from pyai import Network

Net = Network(2,1,1,2)#input neoron,layers,neoron on 1 layer,output neoron
test_list=[1,2]
answer = Net.forward(test_list)

print(answer)
