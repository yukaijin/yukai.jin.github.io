---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I joined VMware SH in 2016 after receiving my Master's degree of Software Engineering, Nanjing University. As a member in developing and maintaining the Central Test Platform of VMware, I needed to collaborate with product testers to review test reports. It's a time-consuming task, and I hoped to leverage some methods to either categorize or classify test reports in facilitating this work. During my experience of learning and applying language models (LSTM, Transformers, BERT, Megatron, etc) on handling test reports, I gain certain level of understanding and very strong interests. Exploring new features and possibility always excite me a lot. As a result, I hope I can be fully immersed in the development and investigation in the area.

# Paper

[The Decodable Sentence-BERT (2023)](https://yukaijin.github.io/files/2024-The_Decodable_Sentence_BERT_trained_for_VMware_Info-Retrieval_System(5pages).pdf)

* In this paper, we present the Decodable Sentence-BERT, a modification in both model architecture and training tasks to further extend the model’s ability. We add Decoder Transformers stacks on top of the Sentence-BERT and derive the original sentences through the Decoder stacks from the last hidden states of Sentence-BERT. It not only keeps all the ability of the Sentence-BERT but also enables the model to recover the original sentence from the sentence embedding - we can drop the original sentences after embedding. What’s more, we can use the accuracy of recovering sentences to indicate the confidence of classification tasks during inference, which is more reliable than the traditional confidence we used.

[Fault Aggregation and Exploring System Based on Sentence-BERT (2023)](https://yukaijin.github.io/files/2024-vectorizing_your_logs_supports_failure_triage_in_many_ways(5pages).pdf)

* In this paper, we propose a new approach called “vectorizing” including processing, saving, and using logs to support failure triage. Logs will be transformed into semantic vectors by a state- of-the-art language model, saved into a vector database, and utilized in many ways. We describe the design, the solution, the use cases, and we evaluate the performance. At last, we share the plan for future works which can benefit most of our R&D engineers.

[BERT-based Live Log Classification System (2022)](https://yukaijin.github.io/files/2023-live-assistant-paper.pdf)

* In this paper, I would like to propose and introduce a deep-learning-based first-hand auto-triaging solution that reviews all failure logs, helps to make categories, do similarity clustering, and apply automated operations(rerun for example) for some intermittent failed cases.

[GPU As A Service (2022)](https://yukaijin.github.io/files/2023-GPU-as-a-Service.pdf)

* In this paper, we describe how we can overcome these limitations by pooling the already procured GPUs and sharing them across Business Groups by leveraging the vGPU features in VMware vSphere. We show how GPU-as-a-Service is more than 14x cheaper than AWS by comparing the machine costs for GPU-as-a-Service with VMware’s actual spend in AWS for equivalent GPU machines during a 60-day period. And by sharing GPUs across users, teams and use cases to maintain higher average utilization levels, we can make owning GPUs a more economical and viable option for VMware.

[vBERT in Production: LogBundle Error Classification (2021)](https://yukaijin.github.io/files/2021-NimbusErrorClassification_v20200127_final_edition.pdf)

* In this paper, we demonstrate an NLP-based system capable of detecting deployment failures, extracting support bundles, determining the top-n candidate ERROR lines, preprocessing those error lines with vNLP, and use a fine-tuned vBERT model achieving an F-Score of 0.9788 to classify the Category and Component for trend tracking and automatic ticket filing in Bugzilla.

[vBERT: From Pretraining to Production (2020)](https://yukaijin.github.io/files/2020-vBERT_From_Pretraining_to_Production.pdf)

* In this paper, we demonstrate the plug-and-play pipeline covering the pretraining, fine-tuning, and serving for vBERT 2020. It turns out vBERT 2020 outperforms its elder counterpart vBERT 2018 in terms of accuracy and F1 scores for specified downstream NLP tasks

[Machine Learning As A Service (2018)](https://yukaijin.github.io/files/2018-MachineLearningAsAService.pdf)

* In this paper, We present a service of machine learning over container cloud of Kubernetes on infrastructure of VMware internal cloud with CPU and GPU support. The service has user-friendly interface and consists of several micro services to launch TensorFlow container to train models. It aims to manage large computing resources in a center place to reduce company costs; it saves time for developers and data scientists to configure distributed machine learning platform. We present experiments on the performance comparison between CPU, GPU, multiple CPUs on our service.

# Reading Materials
[[1] Neural machine translation by jointly learning to align and translate](https://arxiv.org/abs/1409.0473)\
[[2] Attention Is All You Need](https://arxiv.org/abs/1706.03762)\
[[3] BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805)\
[[4] Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks](https://arxiv.org/abs/1908.10084)\
[[5] RoBERTa: A Robustly Optimized BERT Pretraining Approach](https://arxiv.org/abs/1907.11692)\
[[6] Distilling the knowledge in a neural network](https://arxiv.org/abs/1503.02531)\
[[7] DistilBERT, a distilled version of BERT: smaller, faster, cheaper and lighter](https://arxiv.org/abs/1910.01108)\
[[8] Attention is not Explaination](https://aclanthology.org/N19-1357)\
[[9] Attention is not not Explaination](https://arxiv.org/abs/1908.04626)\
[[10] CausaLM: Causal Model Explanation Through Counterfactual Language Models](https://arxiv.org/abs/2005.13407)\
[[11] Megatron-LM: Training Multi-Billion Parameter Language Models Using Model Parallelism](https://arxiv.org/abs/1909.08053)\
[[12] LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971)\
[[13] Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361)
