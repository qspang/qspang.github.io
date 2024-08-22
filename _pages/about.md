---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- ## About Me -->
I am a undergrad student at [South China University of Technology](https://www.scut.edu.cn/new/), [School of Computer Science and Engineering](https://www2.scut.edu.cn/cs/).

I am generally interested in natural language processing and machine learning .

## 📝 Publications


**Chimera: A Lossless Decoding Method for Accelerating Large Language Models Inference by Fusing all Tokens**

Ziqian Zeng, Jiahong Yu, *<ins>Qianshi Pang</ins>*, Zihao Wang, Huiping Zhuang, Cen Chen


<p><a href="https://arxiv.org/abs/2402.15758"><strong>Paper</strong></a> | <a href="https://github.com/kafkayu/Chimera"><strong>Github</strong></a></p>


- **Abstract**: Large language models (LLMs) have demonstrated remarkable capabilities across various tasks. However, their widespread application is hindered by the resource-intensive decoding process. To address this challenge, current approaches have incorporated additional decoding heads to enable parallel prediction of multiple subsequent tokens, thereby achieving inference acceleration. Nevertheless, the accuracy of these decoding heads falls short of the auto-regressive decoding approach.
In light of these limitations, we propose Chimera, a novel framework specifically designed for speculative sampling. Within this framework, we introduce a lightweight draft model that effectively utilizes previously generated tokens to predict subsequent words. To ensure both accuracy and efficiency, we present two strategies within the lightweight draft model. Firstly, we focus on capturing short-range dependencies at the bottom layer. Secondly, we leverage the readily available representations from the original LLM.Through empirical evaluation on the Vicuna and LlaMA-2 series, Chimera demonstrates impressive results, achieving an average latency speedup ratio of 2.7x compared to the vanilla auto-regressive decoding approach. This highlights the potential of our proposed framework in significantly improving the efficiency of large language models during the decoding process. 

**OpenScan: A Benchmark for Generalized Open-Vocabulary 3D Scene Understanding**

Youjun Zhao1, Jiaying Lin1, Shuquan Ye1, *<ins>Qianshi Pang2*, Rynson W.H. Lau1, 

<p><a href="https://arxiv.org/abs/2408.11030"><strong>Paper</strong></a> | <a href="https://github.com/YoujunZhao/OpenScan"><strong>Github</strong></a></p>


- **Abstract**: Open-vocabulary 3D scene understanding (OV-3D) aims to localize and classify novel objects beyond the closed object classes. However, existing approaches and benchmarks primarily focus on the open vocabulary problem within the context of object classes, which is insufficient to provide a holistic evaluation to what extent a model understands the 3D scene. In this paper, we introduce a more challenging task called Generalized Open-Vocabulary 3D Scene Understanding (GOV-3D) to explore the open vocabulary problem beyond object classes. It encompasses an open and diverse set of generalized knowledge, expressed as linguistic queries of fine-grained and object-specific attributes. To this end, we contribute a new benchmark named OpenScan, which consists of 3D object attributes across eight representative linguistic aspects, including affordance, property, material, and more. We further evaluate state-of-the-art OV-3D methods on our OpenScan benchmark, and discover that these methods struggle to comprehend the abstract vocabularies of the GOV-3D task, a challenge that cannot be addressed by simply scaling up object classes during training. We highlight the limitations of existing methodologies and explore a promising direction to overcome the identified shortcomings. 



## 🎖 Awards

- *2022.12* University Scholarship
 
## 📖 Education

- *2021.09* Undergraduate, Computer Science and Technology, [South China University of Technology](https://www.scut.edu.cn/new/), GuangZhou, China.
