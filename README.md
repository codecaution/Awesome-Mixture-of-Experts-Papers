# Awesome-Mixture-of-Experts-Papers 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Awesome-Mixture-of-Experts-Papers is a curated list of Mixture-of-Experts (MoE) papers in recent years. Star this repository, and then you can keep abreast of the latest developments of this booming research field.

Thanks to all the people who made contributions to this project. We strongly encourage the researchers to make pull request (e.g., add missing papers, fix errors) and help the others in this community!

# Contents
- [Awesome-Mixture-of-Experts-Papers](#awesome-mixture-of-experts-papers)
- [Contents](#contents)
- [Paper](#paper)
	- [Algorithm](#algorithm)
		- [2022](#2022)
		- [2021](#2021)
		- [2019](#2019)
		- [2017](#2017)
	- [System](#system)
		- [2022](#2022-1)
		- [2021](#2021-1)
	- [Application](#application)
		- [2021](#2021-2)
		- [2020](#2020)
		- [2018](#2018)
- [Open-Source System](#open-source-system)

# Paper
## Algorithm
### 2022
+	**Unified Scaling Laws for Routed Language Models** [[pdf]](https://arxiv.org/abs/2202.01169) arXiv 2022

	*Aidan Clark, Diego de las Casas, Aurelia Guy, Arthur Mensch, Michela Paganini, Jordan Hoffmann, Bogdan Damoc, Blake Hechtman, Trevor Cai, Sebastian Borgeaud, George van den Driessche, Eliza Rutherford, Tom Hennigan, Matthew Johnson, Katie Millican, Albin Cassirer, Chris Jones, Elena Buchatskaya, David Budden, Laurent Sifre, Simon Osindero, Oriol Vinyals, Jack Rae, Erich Elsen, Koray Kavukcuoglu, Karen Simonyan*

+	**Designing Effective Sparse Expert Models** [[pdf]](https://arxiv.org/abs/2202.08906) arXiv 2022

	*Barret Zoph, Irwan Bello, Sameer Kumar, Nan Du, Yanping Huang, Jeff Dean, Noam Shazeer, William Fedus*

+	**Mixture-of-Experts with Expert Choice Routing** [[pdf]](https://arxiv.org/abs/2202.09368) arXiv 2022

	*Yanqi Zhou, Tao Lei, Hanxiao Liu, Nan Du, Yanping Huang, Vincent Zhao, Andrew Dai, Zhifeng Chen, Quoc Le, James Laudon*

+	**Taming Sparsely Activated Transformer with Stochastic Experts** [[pdf]](https://arxiv.org/abs/2110.04260) ICLR 2022

	*Simiao Zuo, Xiaodong Liu, Jian Jiao, Young Jin Kim, Hany Hassan, Ruofei Zhang, Tuo Zhao, Jianfeng Gao*

+	**Go Wider Instead of Deeper** [[pdf]](https://arxiv.org/abs/2107.11817) AAAI 2022

	*Fuzhao Xue, Ziji Shi, Futao Wei, Yuxuan Lou, Yong Liu, Yang You*

+	**StableMoE: Stable Routing Strategy for Mixture of Experts**[[pdf]](https://arxiv.org/abs/2204.08396) [[code]](https://github.com/Hunter-DDM/stablemoe) ACL 2022

	*Damai Dai, Li Dong, Shuming Ma, Bo Zheng, Zhifang Sui, Baobao Chang, Furu Wei*

+	**A Theoretical View on Sparsely Activated Networks**[[pdf]](https://dynn-icml2022.github.io/spapers/paper_4.pdf) [[poster]](https://dynn-icml2022.github.io/sposters/paper_4.pdf) ICML 2022 Workshop

	*Cenk Baykal, Nishanth Dikkala, Rina Panigrahy, Cyrus Rashtchian, Xin Wang*

+	**Parameter-Efficient Mixture-of-Experts Architecture for Pre-trained Language Models** [[pdf]](https://arxiv.org/abs/2203.01104) arXiv 2022

	*Ze-Feng Gao, Peiyu Liu, Wayne Xin Zhao, Zhong-Yi Lu, Ji-Rong Wen*

+	**Efficient Language Modeling with Sparse all-MLP** [[pdf]](https://arxiv.org/abs/2203.06850) arXiv 2022

	*Ping Yu, Mikel Artetxe, Myle Ott, Sam Shleifer, Hongyu Gong, Ves Stoyanov, Xian Li*

+	**One Student Knows All Experts Know: From Sparse to Dense**[[pdf]](https://arxiv.org/abs/2201.10890) arXiv 2022

	*Fuzhao Xue, Xiaoxin He, Xiaozhe Ren, Yuxuan Lou, Yang You*

+	**MoEC: Mixture of Expert Clusters**[[pdf]](https://arxiv.org/abs/2207.09094) arXiv 2022

	*Yuan Xie, Shaohan Huang, Tianyu Chen, Furu Wei*
	
+	**On the Representation Collapse of Sparse Mixture of Experts** [[pdf]](https://arxiv.org/abs/2204.09179) arXiv 2022

	*Zewen Chi, Li Dong, Shaohan Huang, Damai Dai, Shuming Ma, Barun Patra, Saksham Singhal, Payal Bajaj, Xia Song, Furu Wei*

+	**A Review of Sparse Expert Models in Deep Learning** [[pdf]](https://arxiv.org/abs/2204.09179) arXiv 2022

	*William Fedus, Jeff Dean, Barret Zoph*

### 2021
	
+	**Switch Transformers: Scaling to Trillion Parameter Models with Simple and Efficient Sparsity** [[pdf]](https://arxiv.org/abs/2101.03961) arXiv 2021

	*William Fedus, Barret Zoph, Noam Shazeer*

+	**GShard: Scaling Giant Models with Conditional Computation and Automatic Sharding** [[pdf]](https://openreview.net/pdf?id=qrwe7XHTmYb) ICLR 2021

	*Dmitry Lepikhin, HyoukJoong Lee, Yuanzhong Xu, Dehao Chen, Orhan Firat, Yanping Huang, Maxim Krikun, Noam Shazeer, Zhifeng Chen*

+	**GLaM: Efficient Scaling of Language Models with Mixture-of-Experts** [[pdf](https://arxiv.org/abs/2112.06905)] arXiv 2021

	*Nan Du, Yanping Huang, Andrew M. Dai, Simon Tong, Dmitry Lepikhin, Yuanzhong Xu, Maxim Krikun, Yanqi Zhou, Adams Wei Yu, Orhan Firat, Barret Zoph, Liam Fedus, Maarten Bosma, Zongwei Zhou, Tao Wang, Yu Emma Wang, Kellie Webster, Marie Pellat, Kevin Robinson, Kathy Meier-Hellstern, Toju Duke, Lucas Dixon, Kun Zhang, Quoc V Le, Yonghui Wu, Zhifeng Chen, Claire Cui*

+	**Scaling Vision with Sparse Mixture of Experts.** [[pdf](https://arxiv.org/abs/2101.03961)] NeurIPS 2021

	*Carlos Riquelme, Joan Puigcerver, Basil Mustafa, Maxim Neumann, Rodolphe Jenatton, André Susano Pinto, Daniel Keysers, Neil Houlsby*

+	**Scalable Transfer Learning with Expert Models** [[pdf]](https://openreview.net/forum?id=23ZjUGpjcc) ICLR 2021

	*Joan Puigcerver, Carlos Riquelme Ruiz, Basil Mustafa, Cedric Renggli, André Susano Pinto, Sylvain Gelly, Daniel Keysers, Neil Houlsby*

+	**Efficient Large Scale Language Modeling with Mixtures of Experts** [[pdf]](https://arxiv.org/abs/2112.10684) arXiv 2021

	*Mikel Artetxe, Shruti Bhosale, Naman Goyal, Todor Mihaylov, Myle Ott, Sam Shleifer, Xi Victoria Lin, Jingfei Du, Srinivasan Iyer, Ramakanth Pasunuru, Giri Anantharaman, Xian Li, Shuohui Chen, Halil Akin, Mandeep Baines, Louis Martin, Xing Zhou, Punit Singh Koura, Brian O'Horo, Jeff Wang, Luke Zettlemoyer, Mona Diab, Zornitsa Kozareva, Ves Stoyanov*

+	**DSelect-k: Differentiable Selection in the Mixture of Experts with Applications to Multi-Task Learning** [[pdf](https://arxiv.org/abs/2106.03760)] NeurIPS 2021

	*Hussein Hazimeh, Zhe Zhao, Aakanksha Chowdhery, Maheswaran Sathiamoorthy, Yihua Chen, Rahul Mazumder, Lichan Hong, Ed H. Chi*

+	**Hash Layers For Large Sparse Models** [[pdf](https://openreview.net/pdf?id=lMgDDWb1ULW)] NeurIPS 2021

	*Stephen Roller, Sainbayar Sukhbaatar, Arthur Szlam, Jason Weston*

+	**BASE Layers: Simplifying Training of Large, Sparse Models.** [[pdf](http://proceedings.mlr.press/v139/lewis21a/lewis21a.pdf)] ICML 2021

	*Mike Lewis, Shruti Bhosale, Tim Dettmers, Naman Goyal, Luke Zettlemoyer*
  
+	**M6-T: Exploring Sparse Expert Models and Beyond** [[pdf](https://arxiv.org/abs/2105.15082)] arXiv 2021

	*An Yang, Junyang Lin, Rui Men, Chang Zhou, Le Jiang, Xianyan Jia, Ang Wang, Jie Zhang, Jiamang Wang, Yong Li, Di Zhang, Wei Lin, Lin Qu, Jingren Zhou, Hongxia Yang*

+	**Dense-to-Sparse Gate for Mixture-of-Experts** [[pdf]](https://arxiv.org/abs/2112.14397) arXiv 2021

	*Xiaonan Nie, Shijie Cao, Xupeng Miao, Lingxiao Ma, Jilong Xue, Youshan Miao, Zichao Yang, Zhi Yang, Bin Cui*

+	**Sparse MoEs meet Efficient Ensembles** [[pdf]](https://arxiv.org/abs/2110.03360) arXiv 2021

	*James Urquhart Allingham, Florian Wenzel, Zelda E Mariet, Basil Mustafa, Joan Puigcerver, Neil Houlsby, Ghassen Jerfel, Vincent Fortuin, Balaji Lakshminarayanan, Jasper Snoek, Dustin Tran, Carlos Riquelme Ruiz, Rodolphe Jenatton*

+	**Towards More Effective and Economic Sparsely-Activated Model** [[pdf]](https://arxiv.org/abs/2110.07431) arXiv 2021

	*Hao Jiang, Ke Zhan, Jianwei Qu, Yongkang Wu, Zhaoye Fei, Xinyu Zhang, Lei Chen, Zhicheng Dou, Xipeng Qiu, Zikai Guo, Ruofei Lai, Jiawen Wu, Enrui Hu, Yinxia Zhang, Yantao Jia, Fan Yu, Zhao Cao*

+	**MoEfication: Conditional Computation of Transformer Models for Efficient Inference** [[pdf]](https://arxiv.org/abs/2110.01786) arXiv 2021

	*Zhengyan Zhang, Yankai Lin, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou*
	
+  **Cross-token Modeling with Conditional Computation** [[pdf]](https://arxiv.org/abs/2109.02008) arXiv 2021

	*Yuxuan Lou, Fuzhao Xue, Zangwei Zheng, Yang You*

### 2019
+	**Mixture Models for Diverse Machine Translation: Tricks of the Trade.** [[pdf](https://arxiv.org/abs/1902.07816)] ICML 2019

	*Tianxiao Shen, Myle Ott, Michael Auli, Marc'Aurelio Ranzato*

### 2017
+ **Outrageously Large Neural Networks: The Sparsely-Gated Mixture-of-Experts Layer.** [[pdf](https://arxiv.org/abs/1701.06538)] ICLR 2017
  
   *Noam Shazeer, Azalia Mirhoseini, Krzysztof Maziarz, Andy Davis, Quoc Le, Geoffrey Hinton, Jeff Dean*

## System
### 2022

+   **FasterMoE: modeling and optimizing training of large-scale dynamic pre-trained models.** [[pdf](https://dl.acm.org/doi/abs/10.1145/3503221.3508418)] [[code](https://github.com/laekov/fastermoe-ae)] PPoPP 2022

	*Jiaao He, Jidong Zhai, Tiago Antunes, Haojie Wang, Fuwen Luo, Shangfeng Shi, Qin Li*

+	**DeepSpeed-MoE: Advancing Mixture-of-Experts Inference and Training to Power Next-Generation AI Scale** [[pdf](https://arxiv.org/abs/2201.05596)] arXiv 2022

	*Samyam Rajbhandari, Conglong Li, Zhewei Yao, Minjia Zhang, Reza Yazdani Aminabadi, Ammar Ahmad Awan, Jeff Rasley, Yuxiong He*

+	**Alpa: Automating Inter- and Intra-Operator Parallelism for Distributed Deep Learning** [[pdf]](https://arxiv.org/abs/2201.12023) OSDI 2022
	
	*Lianmin Zheng, Zhuohan Li, Hao Zhang, Yonghao Zhuang, Zhifeng Chen, Yanping Huang, Yida Wang, Yuanzhong Xu, Danyang Zhuo, Joseph E. Gonzalez, Ion Stoica*
	
+	**Pathways: Asynchronous Distributed Dataflow for ML** [[pdf]](https://arxiv.org/abs/2203.12533) MLSys 2022
	
	*Paul Barham, Aakanksha Chowdhery, Jeff Dean, Sanjay Ghemawat, Steven Hand, Dan Hurt, Michael Isard, Hyeontaek Lim, Ruoming Pang, Sudip Roy, Brennan Saeta, Parker Schuh, Ryan Sepassi, Laurent El Shafey, Chandramohan A. Thekkath, Yonghui Wu*

+  **HetuMoE: An Efficient Trillion-scale Mixture-of-Expert Distributed Training System** [[pdf]](https://arxiv.org/abs/2203.14685) arXiv 2022
  
	*Xiaonan Nie, Pinxue Zhao, Xupeng Miao, Tong Zhao, Bin Cui*

+	**Tutel: Adaptive Mixture-of-Experts at Scale** [[pdf]](https://arxiv.org/abs/2206.03382) arXiv 2022

	*Changho Hwang, Wei Cui, Yifan Xiong, Ziyue Yang, Ze Liu, Han Hu, Zilong Wang, Rafael Salas, Jithin Jose, Prabhat Ram, Joe Chau, Peng Cheng, Fan Yang, Mao Yang, Yongqiang Xiong*

### 2021

+	**FastMoE: A Fast Mixture-of-Expert Training System** [[pdf](https://arxiv.org/abs/2103.13262)] arXiv 2021

	*Jiaao He, Jiezhong Qiu, Aohan Zeng, Zhilin Yang, Jidong Zhai, Jie Tang*

## Application

### 2022

+	**Learning Large-scale Universal User Representation with Sparse Mixture of Experts** [[pdf]](https://arxiv.org/abs/2207.04648) ICML 2022

	*Caigao Jiang, Siqiao Xue, James Zhang, Lingyue Liu, Zhibo Zhu, Hongyan Hao*
	
### 2021

+	**Video Recommendation with Multi-gate Mixture of Experts Soft Actor Critic** [[pdf](https://dl.acm.org/doi/abs/10.1145/3397271.3401238)] SIGIR 2021

	*Dingcheng Li, Xu Li, Jun Wang, Ping Li*

+	**Beyond Distillation: Task-level Mixture-of-Experts for Efficient Inference** [[pdf]](https://arxiv.org/abs/2110.03742) EMNLP 2021

	*Sneha Kudugunta, Yanping Huang, Ankur Bapna, Maxim Krikun, Dmitry Lepikhin, Minh-Thang Luong, Orhan Firat*
	
+	**MSSM: A Multiple-level Sparse Sharing Model for Efficient Multi-Task Learning** [[pdf](https://dl.acm.org/doi/10.1145/3404835.3463022)] SIGIR 2021

	*Ke Ding, Xin Dong, Yong He, Lei Cheng, Chilin Fu, Zhaoxin Huan, Hai Li, Tan Yan, Liang Zhang, Xiaolu Zhang, Linjian Mo*
	
+	**DEMix Layers: Disentangling Domains for Modular Language Modeling** [[pdf](https://arxiv.org/abs/2108.05036)] arXiv 2021

    *Suchin Gururangan, Mike Lewis, Ari Holtzman, Noah A. Smith, Luke Zettlemoyer*

### 2020

+	**Multitask Mixture of Sequential Experts for User Activity Streams** [[pdf](https://dl.acm.org/doi/10.1145/3394486.3403359)] SIGKDD 2020

	*Zhen Qin, Yicheng Cheng, Zhe Zhao, Zhe Chen, Donald Metzler, Jingzheng Qin*

+	**Progressive Layered Extraction (PLE): A Novel Multi-Task Learning (MTL) Model for Personalized Recommendations** [[pdf]](https://dl.acm.org/doi/10.1145/3383313.3412236) RecSys 2020

	*Hongyan Tang, Junning Liu, Ming Zhao, Xudong Gong*
	
### 2018

+	**Modeling Task Relationships in Multi-task Learning with Multi-gate Mixture-of-Experts** [[pdf](https://dl.acm.org/doi/10.1145/3219819.3220007)] SIGKDD 2018

	*Jiaqi Ma, Zhe Zhao, Xinyang Yi, Jilin Chen, Lichan Hong, Ed Chi*

# Open-Source System
+ **Tutel: An efficient mixture-of-experts implementation for large DNN model training** [[blog](https://www.microsoft.com/en-us/research/blog/tutel-an-efficient-mixture-of-experts-implementation-for-large-dnn-model-training/)] [[github](https://github.com/microsoft/tutel)] MSRA
+ **Deepspeed-MoE:Advancing Mixture-of-Experts Inference and Training to Power Next-Generation AI Scale** [[github](https://github.com/microsoft/DeepSpeed)] Microsoft DeepSpeed 
+ **FastMoE: A Fast Mixture-of-Expert Training System** [[github](https://github.com/laekov/fastmoe)] Tsinghua University
+ **HetuMoE: An Efficient Trillion-scale Mixture-of-Expert Distributed Training System** [[github](https://github.com/PKU-DAIR/Hetu)] Peking University

Contributed by [Xiaonan Nie](https://github.com/codecaution), [Xupeng Miao](https://github.com/Hsword), Qibin Liu and [Hetu](https://github.com/PKU-DAIR/Hetu) team members.
