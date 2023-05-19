---
title: "Utilizing Large Language Models for the Classification of Security Vulnerabilities in Solidity Code"
excerpt: "A smart contract is a self-executing contract with the terms of the agreement between buyer and seller being directly written into lines of code. The code is stored on a blockchain across a distributed, decentralized blockchain network. The code controls the execution, and transactions are trackable and irreversible. Because the smart contract is irreversible, we must audit the written program to ensure it is secure. <br/><img src='/images/Smart-Contract-Security-2.jpg' width='700' height='400'>"
collection: portfolio
---

## Motivation 
Large Language Models (LLMs), with their expansive training on a variety of datasets, have acquired a remarkable capability known as zero-shot learning. This ability enables LLMs to extrapolate from their learned knowledge and make predictions for tasks they have not specifically been trained on. For instance, a text classification model trained on movie and book reviews might be able to classify music reviews, despite not having any labeled music reviews for training. This is possible if the model has developed a sound understanding of what constitutes a 'review' and can infer the characteristics of music reviews from associated metadata.

Furthermore, LLMs can be adapted to more specific tasks via a process called fine-tuning, which showcases their few-shot learning ability. Here, the model learns from a handful of examples of a new task, allowing it to generalize and perform this new task. An illustrative example would be asking the model to classify a piece of text into categories it hasn't encountered during training, such as "sports," "politics," or "science". Given a brief explanation of these categories, the model should be able to perform this task well, thanks to its understanding of the underlying concepts these categories represent. [3](https://arxiv.org/abs/2005.14165)

These abilities of LLMs, from zero-shot to few-shot learning, open up a wide range of applications across various domains. This research proposal, in particular, aims to leverage the power of LLMs for the task of analyzing and classifying vulnerabilities in Solidity code.

## Hypothesis

The central hypothesis of this research is that LLMs, when fine-tuned using few-shot learning on a dataset of Solidity code, can be trained to classify security vulnerabilities effectively, such as reentrancy, in smart contracts.

The objective is to adapt the LLM to recognize and classify different types of vulnerabilities in Solidity code. The model would be fine-tuned using a dataset of code snippets labeled with their respective vulnerability classes. Although this dataset is small compared to the corpus the model was initially trained on, it's expected that the model will be able to generalize from this dataset and accurately classify new, unseen code snippets.

Consider a scenario where we have a set of Solidity contract code snippets, each labeled with a respective vulnerability type like "reentrance," "arithmetic overflow," or "unprotected selfdestruct." During the fine-tuning process, the LLM is exposed to these examples in a supervised manner, learning to associate specific code patterns with each vulnerability type.


## Feasibility and Potential Challenges

While promising, the proposed project comes with several potential risks, unknowns, and challenges that need to be carefully considered.

The first concern lies in the quality and quantity of the training data. Fine-tuning a large language model is significantly dependent on the availability of a well-curated dataset. For this project, it is critical to have a robust collection of Solidity code snippets, each labeled with its respective vulnerability type. The accuracy of these labels and the diversity of the code samples will be crucial for effective learning. However, assembling and curating such a dataset may prove to be a challenging and time-consuming task.

Secondly, the computational requirements for fine-tuning large language models are considerable. Depending on the size of the model and the dataset, the process may take from several days to weeks even on high-performance hardware. This factor could potentially increase the cost and extend the timeline of the project.

Finally, the ability of the model to generalize from the fine-tuning dataset to unseen code snippets is not guaranteed. This capability will need to be empirically validated. There's a risk that the model might overfit to the training data and fail to generalize to new instances, especially if the training data lacks sufficient diversity.

## Related Work

Notable studies in this field include:

**Transformer-Based Language Models for Software Vulnerability Detection:** In this study, the authors successfully employed large transformer-based models to detect vulnerabilities in C/C++ source code. They developed a comprehensive framework that integrated source code translation, model preparation, and inference to effectively identify software vulnerabilities. Their empirical results demonstrated the robust performance of these models in vulnerability detection, surpassing contemporary models such as bidirectional long short term memory and bidirectional gated recurrent units in certain performance metrics. [2](https://arxiv.org/abs/2204.03214)

**Examining Zero-Shot Vulnerability Repair with Large Language Models by Hammond Pearce et al.:** This recent study extends the application of LLMs to not only detection but also the repair of software vulnerabilities in a zero-shot manner. In this context, "zero-shot" means that the models are not specifically trained for this task but are expected to perform it based on their general knowledge of programming languages and code. The authors conducted a large-scale study on commercially available, black-box LLMs and a locally trained model. Their findings indicate that LLMs show promise in repairing security vulnerabilities, although the reliability of LLMs in generating repairs remains an open question. [1](https://arxiv.org/abs/2112.02125)
## Potential Research Value

This project could contribute to several research areas:

1.  **Novel Application of LLMs:** This project aims to investigate a relatively unexplored application of LLMs, specifically in the field of smart contract vulnerability detection. It would contribute to the expanding body of knowledge on how to employ LLMs for specialized tasks, a topic of growing interest across diverse fields.
2.  **Few-Shot Learning:** This project also provides an opportunity to contribute to the understanding of few-shot learning, a rapidly evolving area of machine learning. Using few-shot learning to train an LLM for a highly specialized task like this could yield valuable insights into the capabilities and limitations of this approach.
3.  **Source Code Translation and Model Preparation:** An integral part of the proposed framework involves transforming the source code into a format that can be processed by the LLM. A potential area of contribution could be the development of a robust method for translating Solidity source code into a form that maintains its structural and semantic information while being suitable for LLM processing. Additionally, investigating how different translation approaches impact the model's performance could also be a valuable contribution to the field.
