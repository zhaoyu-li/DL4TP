# Deep Learning for Theorem Proving (DL4TP)

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](./LICENSE) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-green)](https://github.com/zhaoyu-li/DL4TP/pulls) [![GitHub last commit (branch)](https://img.shields.io/github/last-commit/zhaoyu-li/DL4TP/main?logo=github&color=green)](https://github.com/zhaoyu-li/DL4TP)

Welcome to our repository! This is a curated collection of resources related to deep learning for theorem proving.

We categorize papers primarily based on the applications of deep learning models, organizing them into five task-specific categories and two dataset categories. A single paper may appear in multiple categories due to its relevance to different tasks or datasets. Additionally, each paper is labeled with the used theorem prover/proof calculus/problem domain to help users quickly find the resources that best match their interests or needs. For example, papers using/generating theorems/proofs in natural language are labelled with [NL].

For more details, please refer to our survey paper: [A Survey on Deep Learning for Theorem Proving](https://arxiv.org/pdf/2404.09939.pdf).

## Table of Contents

- [Surveys](#surveys)
- [Tutorials](#tutorials)
- [Tasks](#tasks)
  - [Autoformalization](#autoformalization)
  - [Premise Selection](#premise-selection)
  - [Proofstep Generation](#proofstep-generation)
  - [Proof Search](#proof-search)
  - [Other Tasks](#other-tasks)
- [Datasets](#datasets)
  - [Data Collection](#data-collection)
  - [Data Generation](#data-generation)
- [Related Surveys](#related-surveys)
- [Citation](#citation)

## Surveys
1. **Towards the Automatic Mathematician** `CADE 2021` [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-79876-5_2)

   *Rabe, Markus N and Szegedy, Christian*

1. **Learning Guided Automated Reasoning: A Brief Survey** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2403.04017.pdf)

   *Blaauwbroek, Lasse and Cerna, David and Gauthier, Thibault and Jakubův, Jan and Kaliszyk, Cezary and Suda, Martin and Urban, Josef*

1. **A Survey on Deep Learning for Theorem Proving** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2404.09939.pdf)

   *Li, Zhaoyu and Sun, Jialiang and Murphy, Logan and Su, Qidong and Li, Zenan and Zhang, Xian and Yang, Kaiyu and Si, Xujie* 

## Tutorials

1. **Tutorial on Machine Learning for Theorem Proving** `NeurIPS 2023 Tutorial` [[link]](https://machine-learning-for-theorem-proving.github.io/) [Coq, Isabelle, Lean]

   *First, Emily and Jiang, Albert and Yang, Kaiyu*

## Tasks

### Autoformalization

1. **First Experiments with Neural Translation of Informal to Formal Mathematics** `CICM 2018` [[paper]](https://arxiv.org/pdf/1805.06502.pdf) [NL, Mizar]

   *Wang, Qingxiang and Kaliszyk, Cezary and Urban, Josef*

1. **Exploration of Neural Machine Translation in Autoformalization of Mathematics in Mizar** `CPP 2020` [[paper]](https://arxiv.org/pdf/1912.02636.pdf) [NL, Mizar]

   *Wang, Qingxiang and Brown, Chad and Kaliszyk, Cezary and Urban, Josef*

1. **Learning Alignment between Formal \& Informal Mathematics** `AITP 2020` [[paper]](https://aitp-conference.org/2020/abstract/paper_33.pdf) [NL, HOL Light]

   *Bansal, Kshitij and Szegedy, Christian*

1. **A Promising Path Towards Autoformalization and General Artificial Intelligence** `CICM 2020` [[paper]](https://leanprover.zulipchat.com/user_uploads/3121/lWKHE1MCcJ1ZwiF2poPoJckC/Autoformalization.pdf)

   *Szegedy, Christian*

1. **Autoformalization with Large Language Models** `NeurIPS 2022` [[paper]](https://arxiv.org/pdf/2205.12615.pdf) [NL, Isabelle]

   *Wu, Yuhuai and Jiang, Albert Qiaochu and Li, Wenda and Rabe, Markus and Staats, Charles and Jamnik, Mateja and Szegedy, Christian*

1. **Towards Autoformalization of Mathematics and Code Correctness: Experiments with Elementary Proofs** `EMNLP 2022 MathNLP Workshop` [[paper]](https://arxiv.org/pdf/2301.02195.pdf) [NL, Coq]

   *Cunningham, Garett and Bunescu, Razvan C and Juedes, David*

1. **Towards a Mathematics Formalisation Assistant using Large Language Models** `arXiv 2022` [[paper]](https://arxiv.org/pdf/2211.07524.pdf) [NL, Lean]

   *Agrawal, Ayush and Gadgil, Siddhartha and Goyal, Navin and Narayanan, Ashvni and Tadipatri, Anand*

1. **Towards Automating Formalisation of Theorem Statements using Large Language Models** `NeurIPS 2022 MATH-AI Workshop` [[paper]](https://mathai2022.github.io/papers/17.pdf) [NL, Lean]

   *Gadgil, Siddhartha and Tadipatri, Anand Rao and Agrawal, Ayush and Narayanan, Ashvni and Goyal, Navin*

1. **Draft, Sketch, and Prove: Guiding Formal Theorem Provers with Informal Proofs** `ICLR 2023` [[paper]](https://arxiv.org/pdf/2210.12283.pdf) [NL, Isabelle]

   *Jiang, Albert Q and Welleck, Sean and Zhou, Jin Peng and Li, Wenda and Liu, Jiacheng and Jamnik, Mateja and Lacroix, Timothée and Wu, Yuhuai and Lample, Guillaume*

1. **Logic-LM: Empowering Large Language Models with Symbolic Solvers for Faithful Logical Reasoning** `EMNLP 2023 Findings` [[paper]](https://arxiv.org/pdf/2305.12295.pdf) [NL, Prover9, Z3]

   *Pan, Liangming and Albalak, Alon and Wang, Xinyi and Wang, William Yang*

1. **LINC: A Neurosymbolic Approach for Logical Reasoning by Combining Language Models with First-Order Logic Provers** `EMNLP 2023` [[paper]](https://arxiv.org/pdf/2310.15164.pdf) [NL, Prover9]

   *Olausson, Theo X and Gu, Alex and Lipkin, Benjamin and Zhang, Cedegao E and Solar-Lezama, Armando and Tenenbaum, Joshua B and Levy, Roger*

1. **SATLM: Satisfiability-Aided Language Models Using Declarative Prompting** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2305.09656.pdf) [NL, Z3]

   *Ye, Xi and Chen, Qiaochu and Dillig, Isil and Durrett, Greg*

1. **FIMO: A Challenge Formal Dataset for Automated Theorem Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2309.04295.pdf) [NL, Lean]

   *Liu, Chengwu and Shen, Jianhao and Xin, Huajian and Liu, Zhengying and Yuan, Ye and Wang, Haiming and Ju, Wei and Zheng, Chuanyang and Yin, Yichun and Li, Lin and Zhang, Ming Zhang and Liu, Qun*

1. **Decomposing the Enigma: Subgoal-based Demonstration Learning for Formal Theorem Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2305.16366.pdf) [NL, Isabelle]

   *Zhao, Xueliang and Li, Wenda and Kong, Lingpeng*

1. **ProofNet: Autoformalizing and Formally Proving Undergraduate-Level Mathematics** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2302.12433.pdf) [NL, Lean]

   *Azerbayev, Zhangir and Piotrowski, Bartosz and Schoelkopf, Hailey and Ayers, Edward W and Radev, Dragomir and Avigad, Jeremy*

1. **Multilingual Mathematical Autoformalization** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2311.03755.pdf) [NL, Isabelle, Lean]

   *Jiang, Albert Q and Li, Wenda and Jamnik, Mateja*

1. **Lyra: Orchestrating Dual Correction in Automated Theorem Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2309.15806.pdf) [NL, Isabelle]

   *Zheng, Chuanyang and Wang, Haiming and Xie, Enze and Liu, Zhengying and Sun, Jiankai and Xin, Huajian and Shen, Jianhao and Li, Zhenguo and Li, Yu*

1. **A New Approach Towards Autoformalization** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2310.07957.pdf) [NL, Lean]

   *Patel, Nilay and Flanigan, Jeffrey and Saha, Rahul*

1. **MUSTARD: Mastering Uniform Synthesis of Theorem and Proof Data** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2402.08957.pdf) [NL, Lean]

   *Huang, Yinya and Lin, Xiaohan and Liu, Zhengying and Cao, Qingxing and Xin, Huajian and Wang, Haiming and Li, Zhenguo and Song, Linqi and Liang, Xiaodan*

1. **Don't Trust: Verify - Grounding LLM Quantitative Reasoning with Autoformalization** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2403.18120.pdf) [NL, Isabelle]

   *Zhou, Jin Peng and Staats, Charles E and Li, Wenda and Szegedy, Christian and Weinberger, Kilian Q and Wu, Yuhuai*

1. **LEGO-Prover: Neural Theorem Proving with Growing Libraries** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.00656.pdf) [NL, Isabelle]

   *Wang, Haiming and Xin, Huajian and Zheng, Chuanyang and Li, Lin and Liu, Zhengying and Cao, Qingxing and Huang, Yinya and Xiong, Jing and Shi, Han and Xie, Enze and Yin, Jian and Li, Zhenguo and Liao, Heng and Liang, Xiaodan*

1. **Llemma: An Open Language Model for Mathematics** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.10631.pdf) [NL, Isabelle, Lean]

   *Azerbayev, Zhangir and Schoelkopf, Hailey and Paster, Keiran and Santos, Marco Dos and McAleer, Stephen and Jiang, Albert Q and Deng, Jia and Biderman, Stella and Welleck, Sean*

1. **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.03300.pdf) [NL, Isabelle]

   *Shao, Zhihong and Wang, Peiyi and Zhu, Qihao and Xu, Runxin and Song, Junxiao and Zhang, Mingchuan and Li, YK and Wu, Y and Guo, Daya*

1. **InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.06332.pdf) [NL, Lean]

   *Ying, Huaiyuan and Zhang, Shuo and Li, Linyang and Zhou, Zhejian and Shao, Yunfan and Fei, Zhaoye and Ma, Yichuan and Hong, Jiawei and Liu, Kuikun and Wang, Ziyi and Wang, Yudong and Wu, Zijian and Li, Shuaibin and Zhou, Fengzhe and Liu, Hongwei and Zhang, Songyang and Zhang, Wenwei and Yan, Hang and Qiu, Xipeng and Wang, Jiayu and Chen, Kai and Lin, Dahua*

### Premise Selection

1. **Deepmath - Deep Sequence Models for Premise Selection** `NeurIPS 2016` [[paper]](https://arxiv.org/pdf/1606.04442.pdf) [Mizar]

   *Irving, Geoffrey and Szegedy, Christian and Alemi, Alexander A and Eén, Niklas and Chollet, François and Urban, Josef*

1. **HolStep: A Machine Learning Dataset for Higher-Order Logic Theorem Proving** `ICLR 2017` [[paper]](https://arxiv.org/pdf/1703.00426.pdf) [HOL Light]

   *Kaliszyk, Cezary and Chollet, François and Szegedy, Christian*

1. **Tree-structure CNN for Automated Theorem Proving** `ICONIP 2017` [[paper]](https://link.springer.com/chapter/10.1007/978-3-319-70096-0_1) [HOL Light]

   *Peng, Kebin and Ma, Dianfu*

1. **Premise Selection for Theorem Proving by Deep Graph Embedding** `NeurIPS 2017` [[paper]](https://arxiv.org/pdf/1709.09994.pdf) [HOL Light]

   *Wang, Mingzhe and Tang, Yihe and Wang, Jian and Deng, Jia*

1. **Premise Selection with Neural Networks and Distributed Representation of Features** `arXiv 2018` [[paper]](https://arxiv.org/pdf/1807.10268.pdf) [Mizar]

   *Kucik, Andrzej Stanisław and Korovin, Konstantin*

1. **HOList: An Environment for Machine Learning of Higher-Order Logic Theorem Proving** `ICML 2019` [[paper]](https://arxiv.org/pdf/1904.03241.pdf) [HOL Light]

   *Kshitij Bansal and Sarah M. Loos and Markus Norman Rabe and Christian Szegedy and Stewart Wilcox*

1. **Learning Representations of Logical Formulae using Graph Neural Networks** `NeurIPS 2019 GRL Workshop` [[paper]](https://grlearning.github.io/papers/58.pdf) [Mizar]

   *Glorot, Xavier and Anand, Ankit and Aygun, Eser and Mourad, Shibl and Kohli, Pushmeet and Precup, Doina*

1. **Property Invariant Embedding for Automated Reasoning** `ECAI 2019` [[paper]](https://arxiv.org/pdf/1911.12073.pdf) [Mizar]

   *Olšák, Miroslav and Kaliszyk, Cezary and Urban, Josef*

1. **Usefulness of Lemmas via Graph Neural Networks** `AITP 2019` [[paper]](http://aitp-conference.org/2019/abstract/AITP_2019_paper_32.pdf) [Mizar]

   *Goertzel, Zarathustra and Urban, Josef*

1. **Improving Graph Neural Network Representations of Logical Formulae with Subgraph Pooling** `arXiv 2019` [[paper]](https://arxiv.org/pdf/1911.06904.pdf) [Mizar, HOL Light]

   *Crouse, Maxwell and Abdelaziz, Ibrahim and Cornelio, Cristina and Thost, Veronika and Wu, Lingfei and Forbus, Kenneth and Fokoue, Achille*

1. **Directed Graph Networks for Logical Reasoning (Extended Abstract)** `PAAR 2020` [[paper]](https://ceur-ws.org/Vol-2752/paper8.pdf) [Mizar]

   *Rawson, Michael and Reger, Giles*

1. **Stateful Premise Selection by Recurrent Neural Networks** `LPAR 2020` [[paper]](https://arxiv.org/pdf/2004.08212.pdf) [Mizar]

   *Piotrowski, Bartosz and Urban, Josef*

1. **Premise Selection in Natural Language Mathematical Texts** `ACL 2020` [[paper]](https://aclanthology.org/2020.acl-main.657.pdf) [NL]

   *Ferreira, Deborah and Freitas, André*

1. **Natural Language Premise Selection: Finding Supporting Statements for Mathematical Text** `LREC 2020` [[paper]](https://arxiv.org/pdf/2004.14959.pdf) [NL]

   *Ferreira, Deborah and Freitas, André*

1. **TextGraphs 2022 Shared Task on Natural Language Premise Selection** `TextGraphs 2020` [[paper]](https://aclanthology.org/2022.textgraphs-1.11.pdf) [NL]

   *Valentino, Marco and Ferreira, Deborah and Thayaparan, Mokanarangan and Freitas, André and Ustalov, Dmitry*

1. **IJS at TextGraphs-16 Natural Language Premise Selection Task: Will Contextual Information Improve Natural Language Premise Selection?** `TextGraphs 2020` [[paper]](https://aclanthology.org/2022.textgraphs-1.12.pdf) [NL]

   *Tran, Thi Hong Hanh and Martinc, Matej and Doucet, Antoine and Pollak, Senja*

1. **UNLPS at TextGraphs-16 Natural Language Premise Selection Task: Unsupervised Natural Language Premise Selection in Mathematical Text using Sentence-MPNet** `TextGraphs 2020` [[paper]](https://aclanthology.org/2022.textgraphs-1.13.pdf) [NL]

   *Trust, Paul and Kadusabe, Provia and Younis, Haseeb and Minghim, Rosane and Milios, Evangelos and Zahran, Ahmed*

1. **Keyword-based Natural Language Premise Selection for an Automatic Mathematical Statement Proving** `TextGraphs 2020` [[paper]](https://aclanthology.org/2022.textgraphs-1.14.pdf) [NL]

   *Dastgheib, Doratossadat and Asgari, Ehsaneddin*

1. **TextGraphs-16 Natural Language Premise Selection Task: Zero-Shot Premise Selection with Prompting Generative Language Models** `TextGraphs 2020` [[paper]](https://aclanthology.org/2022.textgraphs-1.15.pdf) [NL]

   *Kovriguina, Liubov and Teucher, Roman and Wardenga, Robert*

1. **Attention Recurrent Cross-Graph Neural Network for Selecting Premises** `IJMLC 2021` [[paper]](https://link.springer.com/article/10.1007/s13042-021-01448-9) [Mizar]

   *Liu, Qinghua and Xu, Yang and He, Xingxing*

1. **Graph Representations for Higher-Order Logic and Theorem Proving** `AAAI 2020` [[paper]](https://arxiv.org/pdf/1905.10006.pdf) [HOL Light]

   *Paliwal, Aditya and Loos, Sarah and Rabe, Markus and Bansal, Kshitij and Szegedy, Christian*

1. **Improving Stateful Premise Selection with Transformers** `CICM 2021` [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-81097-9_6) [Mizar]

   *Proroković, Krsto and Wand, Michael and Schmidhuber, Jürgen*

1. **Contrastive Graph Representations for Logical Formulas Embedding** `TKDE 2021` [[paper]](https://ieeexplore.ieee.org/document/9667296) [Mizar]

   *Lin, Qika and Liu, Jun and Zhang, Lingling and Pan, Yudai and Hu, Xin and Xu, Fangzhi and Zeng, Hongwei*

1. **Graph Contrastive Pre-training for Effective Theorem Reasoning** `ICML 2021 SSL Workshop` [[paper]](https://arxiv.org/pdf/2108.10821.pdf) [Coq]

   *Li, Zhaoyu and Chen, Binghong and Si, Xujie*

1. **NaturalProofs: Mathematical Theorem Proving in Natural Language** `NeurIPS 2021` [[paper]](https://arxiv.org/pdf/2104.01112.pdf) [NL]

   *Welleck, Sean and Liu, Jiacheng and Bras, Ronan Le and Hajishirzi, Hannaneh and Choi, Yejin and Cho, Kyunghyun*

1. **Contrastive Finetuning of Generative Language Models for Informal Premise Selection** `AITP 2021` [[paper]](http://aitp-conference.org/2021/abstract/paper_21.pdf) [NL]

   *Han, Jesse Michael and Xu, Tao and Polu, Stanislas and Neelakantan, Arvind and Radford, Alec*

1. **STAR: Cross-modal [STA]tement [R]epresentation for Selecting Relevant Mathematical Premises** `EACL 2021` [[paper]](https://aclanthology.org/2021.eacl-main.282.pdf) [NL]

   *Ferreira, Deborah and Freitas, André*

1. **A Study of Continuous Vector Representations for Theorem Proving** `Journal of Logic and Computation 2021` [[paper]](https://arxiv.org/pdf/2101.09142.pdf) [Mizar]

   *Purgał, Stanisław and Parsert, Julian and Kaliszyk, Cezary*

1. **Proof Artifact Co-Training for Theorem Proving with Language Models** `ICLR 2022` [[paper]](https://arxiv.org/pdf/2102.06203.pdf) [Lean]

   *Han, Jesse Michael and Rute, Jason and Wu, Yuhuai and Ayers, Edward W and Polu, Stanislas*

1. **The Isabelle ENIGMA** `ITP 2022` [[paper]](https://arxiv.org/pdf/2205.01981.pdf) [Isabelle]

   *Han, Jesse Michael and Rute, Jason and Wu, Yuhuai and Ayers, Edward W and Polu, Stanislas*

1. **Formal Premise Selection with Language Models** `AITP 2022` [[paper]](http://aitp-conference.org/2022/abstract/AITP_2022_paper_32.pdf) [Isabelle]

   *Tworkowski, Szymon and Mikuła, Maciej and Odrzygóżdż, Tomasz and Czechowski, Konrad and Antoniak, Szymon and Jiang, Albert and Szegedy, Christian and Kuciński, Łukasz and Miłoś, Piotr and Wu, Yuhuai*

1. **MizAR 60 for Mizar 50** `ITP 2023` [[paper]](https://arxiv.org/pdf/2303.06686.pdf) [Mizar]

   *Jakubův, Jan and Chvalovský, Karel and Goertzel, Zarathustra and Kaliszyk, Cezary and Olšák, Mirek and Piotrowski, Bartosz and Schulz, Stephan and Suda, Martin and Urban, Josef*

1. **Graph Sequence Learning for Premise Selection** `AITP 2023` [[paper]](https://arxiv.org/pdf/2303.15642.pdf) [Mizar]

   *Holden, Edvard K and Korovin, Konstantin*

1. **CoProver: A Recommender System for Proof Construction** `CICM 2023` [[paper]](https://arxiv.org/pdf/2304.10486.pdf) [PVS]

   *Yeh, Eric and Hitaj, Briland and Owre, Sam and Quemener, Maena and Shankar, Natarajan*

1. **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2306.15626.pdf) [Lean]

   *Yang, Kaiyu and Swope, Aidan and Gu, Alex and Chalamala, Rahul and Song, Peiyang and Yu, Shixing and Godil, Saad and Prenger, Ryan and Anandkumar, Anima*

1. **MLFMF: Data Sets for Machine Learning for Mathematical Formalization** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2310.16005.pdf) [Agda, Lean]

   *Bauer, Andrej and Petković, Matej and Todorovski, Ljupco*

1. **Magnushammer: A Transformer-Based Approach to Premise Selection** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2303.04488.pdf) [Isabelle]

   *Mikuła, Maciej and Antoniak, Szymon and Tworkowski, Szymon and Jiang, Albert Qiaochu and Zhou, Jin Peng and Szegedy, Christian and Kuciński, Łukasz and Miłos, Piotr and Wu, Yuhuai*

### Proofstep Generation

1. **Holophrasm: A Neural Automated Theorem Prover for Higher-Order Logic** `arXiv 2016` [[paper]](https://arxiv.org/pdf/1608.02644.pdf) [Metamath]

   *Whalen, Daniel*

1. **GamePad: A Learning Environment for Theorem Proving** `ICLR 2019` [[paper]](https://arxiv.org/pdf/1806.00608.pdf) [Coq]

   *Huang, Daniel and Dhariwal, Prafulla and Song, Dawn and Sutskever, Ilya*

1. **HOList: An Environment for Machine Learning of Higher-Order Logic Theorem Proving** `ICML 2019` [[paper]](https://arxiv.org/pdf/1904.03241.pdf) [HOL Light]

   *Kshitij Bansal and Sarah M. Loos and Markus Norman Rabe and Christian Szegedy and Stewart Wilcox*

1. **Learning to Prove Theorems via Interacting with Proof Assistants** `ICML 2019` [[paper]](https://arxiv.org/pdf/1905.09381.pdf) [Coq]

   *Yang, Kaiyu and Deng, Jia*

1. **Graph Representations for Higher-Order Logic and Theorem Proving** `AAAI 2020` [[paper]](https://arxiv.org/pdf/1905.10006.pdf) [HOL Light]

   *Paliwal, Aditya and Loos, Sarah and Rabe, Markus and Bansal, Kshitij and Szegedy, Christian*

1. **Learning to Prove Theorems by Learning to Generate Theorems** `NeurIPS 2020` [[paper]](https://arxiv.org/pdf/2002.07019.pdf) [Metamath]

   *Wang, Mingzhe and Deng, Jia*

1. **Generating Correctness Proofs with Neural Networks** `MAPL 2020` [[paper]](https://arxiv.org/pdf/1907.07794.pdf) [Coq]

   *Sanchez-Stern, Alex and Alhessi, Yousef and Saul, Lawrence and Lerner, Sorin*

1. **TacTok: Semantics-Aware Proof Synthesis** `OOPSLA 2020` [[paper]](https://people.cs.umass.edu/~brun/pubs/pubs/First20oopsla.pdf) [Coq]

   *First, Emily and Brun, Yuriy and Guha, Arjun*

1. **Automated Theorem Proving via Interacting with Proof Assistants by Dynamic Strategies** `BigCom 2020` [[paper]](https://ieeexplore.ieee.org/document/9160473) [Coq]

   *Mo, Guangshuai and Xiong, Yan and Huang, Wenchao and Ma, Lu*

1. **Generative Language Modeling for Automated Theorem Proving** `arXiv 2020` [[paper]](https://arxiv.org/pdf/2009.03393.pdf) [Metamath]

   *Polu, Stanislas and Sutskever, Ilya*

1. **INT: An Inequality Benchmark for Evaluating Generalization in Theorem Proving** `ICLR 2021` [[paper]](https://arxiv.org/pdf/2007.02924.pdf) [inequality]

   *Wu, Yuhuai and Jiang, Albert Qiaochu and Ba, Jimmy and Grosse, Roger*

1. **TacticZero: Learning to Prove Theorems from Scratch with Deep Reinforcement Learning** `NeurIPS 2021` [[paper]](https://arxiv.org/pdf/2102.09756.pdf) [HOL4]

   *Wu, Minchao and Norrish, Michael and Walder, Christian and Dezfouli, Amir*

1. **LISA: Language Models of Isabelle Proofs** `AITP 2021` [[paper]](https://aitp-conference.org/2021/abstract/paper_17.pdf) [Isabelle]

   *Jiang, Albert Qiaochu and Li, Wenda and Han, Jesse Michael and Wu, Yuhuai*

1. **Retrieval-Augmented Proof Step Synthesis** `AITP 2021` [[paper]](https://aitp-conference.org/2021/abstract/paper_18.pdf) [HOL Light]

   *Szegedy, Christian and Rabe, Markus and Michalewski, Henryk*

1. **Proof Artifact Co-Training for Theorem Proving with Language Models** `ICLR 2022` [[paper]](https://arxiv.org/pdf/2102.06203.pdf) [Lean]

   *Han, Jesse Michael and Rute, Jason and Wu, Yuhuai and Ayers, Edward W and Polu, Stanislas*

1. **UniGeo: Unifying Geometry Logical Reasoning via Reformulating Mathematical Expression** `EMNLP 2022` [[paper]](https://arxiv.org/pdf/2212.02746.pdf) [geometry]

   *Chen, Jiaqi and Li, Tong and Qin, Jinghui and Lu, Pan and Lin, Liang and Chen, Chongyu and Liang, Xiaodan*

1. **Towards Autoformalization of Mathematics and Code Correctness: Experiments with Elementary Proofs** `EMNLP 2022 MathNLP Workshop` [[paper]](https://arxiv.org/pdf/2301.02195.pdf) [NL, Coq]

   *Cunningham, Garett and Bunescu, Razvan C and Juedes, David*

1. **HyperTree Proof Search for Neural Theorem Proving** `NeurIPS 2022` [[paper]](https://arxiv.org/pdf/2205.11491.pdf) [Metamath, Lean]

   *Lample, Guillaume and Lacroix, Timothee and Lachaux, Marie-Anne and Rodriguez, Aurelien and Hayat, Amaury and Lavril, Thibaut and Ebner, Gabriel and Martinet, Xavier*

1. **NaturalProver: Grounded Mathematical Proof Generation with Language Models** `NeurIPS 2022` [[paper]](https://arxiv.org/pdf/2205.12910.pdf) [NL]

   *Welleck, Sean and Liu, Jiacheng and Lu, Ximing and Hajishirzi, Hannaneh and Choi, Yejin*

1. **Thor: Wielding Hammers to Integrate Language Models and Automated Theorem Provers** `NeurIPS 2022` [[paper]](https://arxiv.org/pdf/2205.10893.pdf) [Isabelle]

   *Jiang, Albert Qiaochu and Li, Wenda and Tworkowski, Szymon and Czechowski, Konrad and Odrzygóżdż, Tomasz and Miłos, Piotr and Wu, Yuhuai and Jamnik, Mateja*

1. **Diversity-Driven Automated Formal Verification** `ICSE 2022` [[paper]](https://people.cs.umass.edu/~brun/pubs/pubs/First22icse.pdf) [Coq]

   *First, Emily and Brun, Yuriy*

1. **Formal Premise Selection with Language Models** `AITP 2022` [[paper]](http://aitp-conference.org/2022/abstract/AITP_2022_paper_32.pdf) [Isabelle]

   *Tworkowski, Szymon and Mikuła, Maciej and Odrzygóżdż, Tomasz and Czechowski, Konrad and Antoniak, Szymon and Jiang, Albert and Szegedy, Christian and Kuciński, Łukasz and Miłoś, Piotr and Wu, Yuhuai*

1. **Passport: Improving Automated Formal Verification Using Identifiers** `TOPLAS 2023` [[paper]](https://arxiv.org/pdf/2204.10370.pdf) [Coq]

   *Sanchez-Stern, Alex and First, Emily and Zhou, Timothy and Kaufman, Zhanna and Brun, Yuriy and Ringer, Talia*

1. **Draft, Sketch, and Prove: Guiding Formal Theorem Provers with Informal Proofs** `ICLR 2023` [[paper]](https://arxiv.org/pdf/2210.12283.pdf) [NL, Isabelle]

   *Jiang, Albert Q and Welleck, Sean and Zhou, Jin Peng and Li, Wenda and Liu, Jiacheng and Jamnik, Mateja and Lacroix, Timothée and Wu, Yuhuai and Lample, Guillaume*

1. **Formal Mathematics Statement Curriculum Learning** `ICLR 2023` [[paper]](https://arxiv.org/pdf/2202.01344.pdf) [Lean]

   *Polu, Stanislas and Han, Jesse Michael and Zheng, Kunhao and Baksys, Mantas and Babuschkin, Igor and Sutskever, Ilya*

1. **Decomposing the Enigma: Subgoal-based Demonstration Learning for Formal Theorem Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2305.16366.pdf) [NL, Isabelle]

   *Zhao, Xueliang and Li, Wenda and Kong, Lingpeng*

1. **CoProver: A Recommender System for Proof Construction** `CICM 2023` [[paper]](https://arxiv.org/pdf/2304.10486.pdf) [PVS]

   *Yeh, Eric and Hitaj, Briland and Owre, Sam and Quemener, Maena and Shankar, Natarajan*

1. **Baldur: Whole-Proof Generation and Repair with Large Language Models** `ESEC/FSE 2023` [[paper]](https://arxiv.org/pdf/2303.04910.pdf) [Isabelle]

   *First, Emily and Rabe, Markus and Ringer, Talia and Brun, Yuriy*

1. **Peano: Learning Formal Mathematical Reasoning** `Philosophical Transactions of the Royal Society A 2023` [[paper]](https://arxiv.org/pdf/2303.04910.pdf) [Peano]

   *Poesia, Gabriel and Goodman, Noah D*

1. **Mathematical Capabilities of ChatGPT** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2301.13867.pdf) [NL]

   *Simon Frieder and Luca Pinchetti and Alexis Chevalier and Ryan-Rhys Griffiths and Tommaso Salvatori and Thomas Lukasiewicz and Philipp Christian Petersen and Julius Berner*

1. **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2306.15626.pdf) [Lean]

   *Yang, Kaiyu and Swope, Aidan and Gu, Alex and Chalamala, Rahul and Song, Peiyang and Yu, Shixing and Godil, Saad and Prenger, Ryan and Anandkumar, Anima*

1. **LLM vs ITP** `NeurIPS 2023 MATH-AI Workshop` [[paper]](https://mathai2023.github.io/papers/19.pdf) [NL]

   *Frieder, Simon and Trimmel, Martin and Alawadhi, Rashid and Gy, Klaus*

1. **LLMSTEP: LLM Proofstep Suggestions in Lean** `NeurIPS 2023 MATH-AI Workshop` [[paper]](https://arxiv.org/pdf/2310.18457.pdf) [Lean]

   *Welleck, Sean and Saha, Rahul*

1. **Towards Large Language Models as Copilots for Theorem Proving in Lean** `NeurIPS 2023 MATH-AI Workshop` [[paper]](https://mathai2023.github.io/papers/4.pdf) [Lean]

   *Song, Peiyang and Yang, Kaiyu and Anandkumar, Anima*

1. **Temperature-Scaled Large Language Models for Lean Proofstep Prediction** `NeurIPS 2023 MATH-AI Workshop` [[paper]](https://mathai2023.github.io/papers/25.pdf) [Lean]

   *Gloeckle, Fabian and Roziere, Baptiste and Hayat, Amaury and Synnaeve, Gabriel*

1. **DT-Solver: Automated Theorem Proving with Dynamic-Tree Sampling Guided by Proof-Level Value Function** `ACL 2023` [[paper]](https://aclanthology.org/2023.acl-long.706.pdf) [Isabelle, Lean]

   *Wang, Haiming and Yuan, Ye and Liu, Zhengying and Shen, Jianhao and Yin, Yichun and Xiong, Jing and Xie, Enze and Shi, Han and Li, Yujun and Li, Lin and Yin, Jian and Li, Zhenguo and Liang, Xiaodan*

1. **Getting More out of Large Language Models for Proofs** `AITP 2023` [[paper]](https://arxiv.org/pdf/2305.04369.pdf) [Coq]

   *Zhang, Shizhuo Dylan and Ringer, Talia and First, Emily*

1. **UniMath: A Foundational and Multimodal Mathematical Reasoner** `EMNLP 2023` [[paper]](https://aclanthology.org/2023.emnlp-main.440.pdf) [geometry]

   *Liang, Zhenwen and Yang, Tianyu and Zhang, Jipeng and Zhang, Xiangliang*

1. **TRIGO: Benchmarking Formal Mathematical Proof Reduction for Generative Language Models** `EMNLP 2023` [[paper]](https://arxiv.org/pdf/2310.10180.pdf) [Lean]

   *Xiong, Jing and Shen, Jianhao and Yuan, Ye and Wang, Haiming and Yin, Yichun and Liu, Zhengying and Li, Lin and Guo, Zhijiang and Cao, Qingxing and Huang, Yinya and Zheng, Chuanyang and Liang, Xiaodan and Zhang, Ming and Liu, Qun*

1. **Learning Proof Transformations and Its Applications in Interactive Theorem Proving** `FroCoS 2023` [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-43369-6_13) [Coq]

   *Zhang, Liao and Blaauwbroek, Lasse and Kaliszyk, Cezary and Urban, Josef*

1. **Evaluating Language Models for Mathematics through Interactions** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2306.01694.pdf) [NL]

   *Collins, Katherine M and Jiang, Albert Q and Frieder, Simon and Wong, Lionel and Zilka, Miri and Bhatt, Umang and Lukasiewicz, Thomas and Wu, Yuhuai and Tenenbaum, Joshua B and Hart, William and Gowers, Timothy and Li, Wenda and Weller, Adrian and Jamnik, Mateja*

1. **Large Language Models for Mathematicians** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2312.04556.pdf) [NL]

   *Scheidt, Gregor vom*

1. **Experimental Results from Applying GPT-4 to An Unpublished Formal Language** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2305.12196.pdf) [Axiotome]

   *Scheidt, Gregor vom*

1. **Large Language Models' Understanding of Math: Source Criticism and Extrapolation** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2311.07618.pdf) [Lean]

   *Yousefzadeh, Roozbeh and Cao, Xuenan*

1. **Lyra: Orchestrating Dual Correction in Automated Theorem Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2309.15806.pdf) [NL, Isabelle]

   *Zheng, Chuanyang and Wang, Haiming and Xie, Enze and Liu, Zhengying and Sun, Jiankai and Xin, Huajian and Shen, Jianhao and Li, Zhenguo and Li, Yu*

1. **Enhancing Neural Theorem Proving through Data Augmentation and Dynamic Sampling Method** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2312.14188.pdf) [Lean]

   *Vishwakarma, Rahul and Mishra, Subhankar*

1. **An In-Context Learning Agent for Formal Theorem-Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2310.04353.pdf) [Lean, Coq]

   *Thakur, Amitayush and Wen, Yeming and Chaudhuri, Swarat*

1. **LEGO-Prover: Neural Theorem Proving with Growing Libraries** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.00656.pdf) [NL, Isabelle]

   *Wang, Haiming and Xin, Huajian and Zheng, Chuanyang and Li, Lin and Liu, Zhengying and Cao, Qingxing and Huang, Yinya and Xiong, Jing and Shi, Han and Xie, Enze and Yin, Jian and Li, Zhenguo and Liao, Heng and Liang, Xiaodan*

1. **Llemma: An Open Language Model for Mathematics** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.10631.pdf) [NL, Isabelle, Lean]

   *Azerbayev, Zhangir and Schoelkopf, Hailey and Paster, Keiran and Santos, Marco Dos and McAleer, Stephen and Jiang, Albert Q and Deng, Jia and Biderman, Stella and Welleck, Sean*

1. **Solving Proof Block Problems Using Large Language Models** `SIGCSE 2024` [[paper]](https://dl.acm.org/doi/pdf/10.1145/3626252.3630928) [NL]

   *Poulsen, Seth and Sarsa, Sami and Prather, James and Leinonen, Juho and Becker, Brett A and Hellas, Arto and Denny, Paul and Reeves, Brent N*

1. **Solving Olympiad Geometry without Human Demonstrations** `Nature 2024` [[paper]](https://www.nature.com/articles/s41586-023-06747-5) [geometry]

   *Trinh, Trieu H and Wu, Yuhuai and Le, Quoc V and He, He and Luong, Thang*

1. **Graph2Tac: Learning Hierarchical Representations of Math Concepts in Theorem proving** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2401.02949.pdf) [Coq]

   *Rute, Jason and Olšák, Miroslav and Blaauwbroek, Lasse and Massolo, Fidel Ivan Schaposnik and Piepenbrock, Jelle and Pestun, Vasily*

1. **FGeo-TP: A Language Model-Enhanced Solver for Geometry Problems** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.09047.pdf) [geometry]

   *He, Yiming and Zou, Jia and Zhang, Xiaokai and Zhu, Na and Leng, Tuo*

1. **Selene: Pioneering Automated Proof in Software Verification** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2401.07663.pdf) [Isabelle]

   *Zhang, Lichen and Lu, Shuai and Duan, Nan*

1. **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.03300.pdf) [NL, Isabelle]

   *Shao, Zhihong and Wang, Peiyi and Zhu, Qihao and Xu, Runxin and Song, Junxiao and Zhang, Mingchuan and Li, YK and Wu, Y and Guo, Daya*

1. **InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.06332.pdf) [NL, Lean]

   *Ying, Huaiyuan and Zhang, Shuo and Li, Linyang and Zhou, Zhejian and Shao, Yunfan and Fei, Zhaoye and Ma, Yichuan and Hong, Jiawei and Liu, Kuikun and Wang, Ziyi and Wang, Yudong and Wu, Zijian and Li, Shuaibin and Zhou, Fengzhe and Liu, Hongwei and Zhang, Songyang and Zhang, Wenwei and Yan, Hang and Qiu, Xipeng and Wang, Jiayu and Chen, Kai and Lin, Dahua*

1. **Verified Multi-Step Synthesis using Large Language Models and Monte Carlo Tree Search** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.08147.pdf) [Dafny, Coq, Lean]

   *Brandfonbrener, David and Raja, Sibi and Prasad, Tarun and Loughridge, Chloe and Yang, Jianang and Henniger, Simon and Byrd, William E and Zinkov, Robert and Amin, Nada*


### Proof Search

1. **Deep Network Guided Proof Search** `LPAR 2017` [[paper]](https://arxiv.org/pdf/1701.06972.pdf) [E]

   *Loos, Sarah and Irving, Geoffrey and Szegedy, Christian and Kaliszyk, Cezary*

1. **Automated Theorem Proving in Intuitionistic Propositional Logic by Deep Reinforcement Learning** `arXiv 2018` [[paper]](https://arxiv.org/pdf/1811.00796.pdf) [IPL]

   *Kusumoto, Mitsuru and Yahata, Keisuke and Sakai, Masahiro*

1. **ENIGMA-NG: Efficient Neural and Gradient-Boosted Inference Guidance for E** `CADE 2019` [[paper]](https://arxiv.org/pdf/1903.03182.pdf) [ENIGMA]

   *Chvalovský, Karel and Jakubův, Jan and Suda, Martin and Urban, Josef*

1. **Hammering Mizar by Learning Clause Guidance** `ITP 2019` [[paper]](https://arxiv.org/pdf/1904.01677.pdf) [ENIGMA]

   *Jakubův, Jan and Urban, Josef*

1. **Learning Dynamic Polynomial Proofs** `NeurIPS 2019` [[paper]](https://arxiv.org/pdf/1906.01681.pdf) [polynomial inequality]

   *Fawzi, Alhussein and Malinowski, Mateusz and Fawzi, Hamza and Fawzi, Omar*

1. **A Neurally-Guided, Parallel Theorem Prover** `FroCoS 2019` [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-29007-8_3) [Z3]

   *Rawson, Michael and Reger, Giles*

1. **Property Invariant Embedding for Automated Reasoning** `ECAI 2019` [[paper]](https://arxiv.org/pdf/1911.12073.pdf) [leanCoP]

   *Olšák, Miroslav and Kaliszyk, Cezary and Urban, Josef*

1. **Automated Theorem Proving via Interacting with Proof Assistants by Dynamic Strategies** `BigCom 2020` [[paper]](https://ieeexplore.ieee.org/document/9160473) [Coq]

   *Mo, Guangshuai and Xiong, Yan and Huang, Wenchao and Ma, Lu*

1. **Guiding Inferences in Connection Tableau by Recurrent Neural Networks** `CICM 2020` [[paper]](https://arxiv.org/pdf/1905.07961.pdf) [connection tableau]

   *Piotrowski, Bartosz and Urban, Josef*

1. **ENIGMA Anonymous: Symbol-Independent Inference Guiding Machine (System Description)** `IJCAR 2020` [[paper]](https://arxiv.org/pdf/2002.05406.pdf) [ENIGMA]

   *Jakubův, Jan and Chvalovský, Karel and Olšák, Miroslav and Piotrowski, Bartosz and Suda, Martin and Urban, Josef*

1. **Deep Reinforcement Learning for Synthesizing Functions in Higher-Order Logic** `LPAR 2020` [[paper]](https://arxiv.org/pdf/1910.11797.pdf) [HOL4]

   *Gauthier, Thibault*

1. **Generative Language Modeling for Automated Theorem Proving** `arXiv 2020` [[paper]](https://arxiv.org/pdf/2009.03393.pdf) [Metamath]

   *Polu, Stanislas and Sutskever, Ilya*

1. **Learning to Prove from Synthetic Theorems** `arXiv 2020` [[paper]](https://arxiv.org/pdf/2006.11259.pdf) [saturation]

   *Aygün, Eser and Ahmed, Zafarali and Anand, Ankit and Firoiu, Vlad and Glorot, Xavier and Orseau, Laurent and Precup, Doina and Mourad, Shibl*

1. **An Experimental Study of Formula Embeddings for Automated Theorem Proving in First-Order Logic** `arXiv 2020` [[paper]](https://arxiv.org/pdf/2002.00423.pdf) [TRAIL]

   *Abdelaziz, Ibrahim and Thost, Veronika and Crouse, Maxwell and Fokoue, Achille*

1. **Training a First-Order Theorem Prover from Synthetic Data** `ICLR 2021 MATH-AI Workshop` [[paper]](https://arxiv.org/pdf/2103.03798.pdf) [saturation]

   *Firoiu, Vlad and Aygün, Eser and Anand, Ankit and Ahmed, Zafarali and Glorot, Xavier and Orseau, Laurent and Zhang, Lei and Precup, Doina and Mourad, Shibl*

1. **Learned Provability Likelihood for Tactical Search** `SCSS 2021` [[paper]](https://arxiv.org/pdf/2109.03234.pdf) [HOL4]

   *Gauthier, Thibault*

1. **TacticZero: Learning to Prove Theorems from Scratch with Deep Reinforcement Learning** `NeurIPS 2021` [[paper]](https://arxiv.org/pdf/2102.09756.pdf) [HOL4]

   *Wu, Minchao and Norrish, Michael and Walder, Christian and Dezfouli, Amir*

1. **Vampire with a Brain Is a Good ITP Hammer** `FroCoS 2021` [[paper]](https://arxiv.org/pdf/2102.03529.pdf) [Vampire]

   *Suda, Martin*

1. **Fast and Slow Enigmas and Parental Guidance** `FroCoS 2021` [[paper]](https://arxiv.org/pdf/2107.06750.pdf) [ENIGMA]

   *Goertzel, Zarathustra A and Chvalovský, Karel and Jakubův, Jan and Olšák, Miroslav and Urban, Josef*

1. **Towards Finding Longer Proofs** `TABLEAUX 2021` [[paper]](https://arxiv.org/pdf/1905.13100.pdf) [leanCoP]

   *Zombori, Zsolt and Csiszárik, Adrián and Michalewski, Henryk and Kaliszyk, Cezary and Urban, Josef*

1. **lazyCoP: Lazy Paramodulation Meets Neurally Guided Search** `TABLEAUX 2021` [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-86059-2_11) [leanCoP]

   *Rawson, Michael and Reger, Giles*

1. **The Role of Entropy in Guiding a Connection Prover** `TABLEAUX 2021` [[paper]](https://arxiv.org/pdf/2105.14706.pdf) [leanCoP]

   *Zombori, Zsolt and Urban, Josef and Olšák, Miroslav*

1. **Learning Theorem Proving Components** `TABLEAUX 2021` [[paper]](https://arxiv.org/pdf/2107.10034.pdf) [ENIGMA]

   *Chvalovský, Karel and Jakubův, Jan and Olšák, Miroslav and Urban, Josef*

1. **A Deep Reinforcement Learning Approach to First-Order Logic Theorem Proving** `AAAI 2021` [[paper]](https://arxiv.org/pdf/1911.02065.pdf) [TRAIL]

   *Crouse, Maxwell and Abdelaziz, Ibrahim and Makni, Bassem and Whitehead, Spencer and Cornelio, Cristina and Kapanipathi, Pavan and Srinivas, Kavitha and Thost, Veronika and Witbrock, Michael and Fokoue, Achille*

1. **Improving ENIGMA-Style Clause Selection While Learning From History** `CADE 2021` [[paper]](https://link.springer.com/chapter/10.1007/978-3-030-79876-5_31) [Vampire]

   *Suda, Martin*

1. **Proving Theorems using Incremental Learning and Hindsight Experience Replay** `ICML 2022` [[paper]](https://arxiv.org/pdf/2112.10664.pdf) [saturation]

   *Aygün, Eser and Anand, Ankit and Orseau, Laurent and Glorot, Xavier and Mcaleer, Stephen M and Firoiu, Vlad and Zhang, Lei M and Precup, Doina and Mourad, Shibl*

1. **HyperTree Proof Search for Neural Theorem Proving** `NeurIPS 2022` [[paper]](https://arxiv.org/pdf/2205.11491.pdf) [Metamath, Lean]

   *Lample, Guillaume and Lacroix, Timothee and Lachaux, Marie-Anne and Rodriguez, Aurelien and Hayat, Amaury and Lavril, Thibaut and Ebner, Gabriel and Martinet, Xavier*

1. **Learning to Prove Trigonometric Identities** `arXiv 2022` [[paper]](https://arxiv.org/pdf/2207.06679.pdf) [trigonometric identity]

   *Liu, Zhou and Li, Yujun and Liu, Zhengying and Li, Lin and Li, Zhenguo*

1. **Learning to Guide a Saturation-Based Theorem Prover** `TPAMI 2022` [[paper]](https://arxiv.org/pdf/2106.03906.pdf) [TRAIL]

   *Abdelaziz, Ibrahim and Crouse, Maxwell and Makni, Bassem and Austil, Vernon and Cornelio, Cristina and Ikbal, Shajith and Kapanipathi, Pavan and Makondo, Ndivhuwo and Srinivas, Kavitha and Witbrock, Michael and Fokoue, Achille*

1. **Machine Learning Meets the Herbrand Universe** `arXiv 2022` [[paper]](https://arxiv.org/pdf/2210.03590.pdf) [instantiation]

   *Piepenbrock, Jelle and Urban, Josef and Korovin, Konstantin and Olšák, Miroslav and Heskes, Tom and Janota, Mikolaš*

1. **Guiding An Automated Theorem Prover with Neural Rewriting** `IJCAR 2022` [[paper]](https://link.springer.com/chapter/10.1007/978-3-031-10769-6_35) [Prover9]

   *Piepenbrock, Jelle and Heskes, Tom and Janota, Mikoláš and Urban, Josef*

1. **The Isabelle ENIGMA** `ITP 2022` [[paper]](https://arxiv.org/pdf/2205.01981.pdf) [ENIGMA]

   *Goertzel, Zarathustra A and Jakubův, Jan and Kaliszyk, Cezary and Olšák, Miroslav and Piepenbrock, Jelle and Urban, Josef*

1. **Formal Mathematics Statement Curriculum Learning** `ICLR 2023` [[paper]](https://arxiv.org/pdf/2202.01344.pdf) [Lean]

   *Polu, Stanislas and Han, Jesse Michael and Zheng, Kunhao and Baksys, Mantas and Babuschkin, Igor and Sutskever, Ilya*

1. **An Ensemble Approach for Automated Theorem Proving Based on Efficient Name Invariant Graph Neural Representations** `IJCAI 2023` [[paper]](https://arxiv.org/pdf/2305.08676.pdf) [TRAIL]

   *Fokoue, Achille and Abdelaziz, Ibrahim and Crouse, Maxwell and Ikbal, Shajith and Kishimoto, Akihiro and Lima, Guilherme and Makondo, Ndivhuwo and Marinescu, Radu*

1. **Peano: Learning Formal Mathematical Reasoning** `Philosophical Transactions of the Royal Society A 2023` [[paper]](https://arxiv.org/pdf/2303.04910.pdf) [Peano]

   *Poesia, Gabriel and Goodman, Noah D*

1. **MizAR 60 for Mizar 50** `ITP 2023` [[paper]](https://arxiv.org/pdf/2303.06686.pdf) [ENIGMA]

   *Jakubův, Jan and Chvalovský, Karel and Goertzel, Zarathustra and Kaliszyk, Cezary and Olšák, Mirek and Piotrowski, Bartosz and Schulz, Stephan and Suda, Martin and Urban, Josef*

1. **Reinforcement Learning for Guiding the E Theorem Prover** `FLAIRS 2023` [[paper]](https://journals.flvc.org/FLAIRS/article/view/133334) [E]

   *McKeown, Jack and Sutcliffe, Geoff*

1. **Guiding an Instantiation Prover with Graph Neural Networks** `LPAR 2023` [[paper]](https://easychair.org/publications/open/5z94) [iProver]

   *Chvalovský, Karel and Korovin, Konstantin and Piepenbrock, Jelle and Urban, Josef*

1. **How Much Should This Symbol Weigh? A GNN-Advised Clause Selection** `LPAR 2023` [[paper]](https://easychair.org/publications/open/2BSs) [Vampire]

   *Bártěk, Filip and Suda, Martin*

1. **gym-saturation: Gymnasium Environments for Saturation Provers (System Description)** `TABLEAUX 2023` [[paper]](https://arxiv.org/pdf/2309.09022.pdf) [Vampire, iProver]

   *Shminke, Boris*

1. **DT-Solver: Automated Theorem Proving with Dynamic-Tree Sampling Guided by Proof-Level Value Function** `ACL 2023` [[paper]](https://aclanthology.org/2023.acl-long.706.pdf) [Isabelle, Lean]

   *Wang, Haiming and Yuan, Ye and Liu, Zhengying and Shen, Jianhao and Yin, Yichun and Xiong, Jing and Xie, Enze and Shi, Han and Li, Yujun and Li, Lin and Yin, Jian and Li, Zhenguo and Liang, Xiaodan*

1. **An In-Context Learning Agent for Formal Theorem-Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2310.04353.pdf) [Lean, Coq]

   *Thakur, Amitayush and Wen, Yeming and Chaudhuri, Swarat*

1. **Verified Multi-Step Synthesis using Large Language Models and Monte Carlo Tree Search** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.08147.pdf) [Dafny, Coq, Lean]

   *Brandfonbrener, David and Raja, Sibi and Prasad, Tarun and Loughridge, Chloe and Yang, Jianang and Henniger, Simon and Byrd, William E and Zinkov, Robert and Amin, Nada*

### Other Tasks

1. **First Neural Conjecturing Datasets and Experiments** `CICM 2020` [[paper]](https://arxiv.org/pdf/2005.14664.pdf) [Mizar]

   *Urban, Josef and Jakubův, Jan*

1. **Guiding Inferences in Connection Tableau by Recurrent Neural Networks** `CICM 2020` [[paper]](https://arxiv.org/pdf/1905.07961.pdf) [connection tableau]

   *Piotrowski, Bartosz and Urban, Josef*

1. **Mathematical Reasoning in Latent Space** `ICLR 2020` [[paper]](https://arxiv.org/pdf/1909.11851.pdf) [HOL Light]

   *Lee, Dennis and Szegedy, Christian and Rabe, Markus N and Loos, Sarah M and Bansal, Kshitij*

1. **Mathematical Reasoning via Self-supervised Skip-tree Training** `ICLR 2021` [[paper]](https://arxiv.org/pdf/2006.04757.pdf) [HOL Light]

   *Rabe, Markus N and Lee, Dennis and Bansal, Kshitij and Szegedy, Christian*

1. **Latent Action Space for Efficient Planning in Theorem Proving** `AITP 2021` [[paper]](https://aitp-conference.org/2021/abstract/paper_24.pdf) [inequality]

   *Wu, Minchao and Wu, Yuhuai*

1. **IsarStep: A Benchmark for High-Level Mathematical Reasoning** `ICLR 2021` [[paper]](https://arxiv.org/pdf/2006.09265.pdf) [Isabelle]

   *Li, Wenda and Yu, Lei and Wu, Yuhuai and Paulson, Lawrence C*

1. **LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning** `ICML 2021` [[paper]](https://arxiv.org/pdf/2101.06223.pdf) [Isabelle, HOL Light, Metamath, Lean]

   *Wu, Yuhuai and Rabe, Markus N and Li, Wenda and Ba, Jimmy and Grosse, Roger B and Szegedy, Christian*

1. **Proof Artifact Co-Training for Theorem Proving with Language Models** `ICLR 2022` [[paper]](https://arxiv.org/pdf/2102.06203.pdf) [Lean]

   *Han, Jesse Michael and Rute, Jason and Wu, Yuhuai and Ayers, Edward W and Polu, Stanislas*

1. **Exploring Mathematical Conjecturing with Large Language Models** `NeSy 2023` [[paper]](https://ceur-ws.org/Vol-3432/paper5.pdf) [Isabelle]

   *Johansson, Moa and Smallbone, Nicholas*

1. **BERT Is Not The Count: Learning to Match Mathematical Statements with Proofs** `EACL 2023` [[paper]](https://arxiv.org/pdf/2302.09350.pdf) [NL]

   *Li, Weixian Waylon and Ziser, Yftah and Coavoux, Maximin and Cohen, Shay B*

1. **REFACTOR: Learning to Extract Theorems from Proofs** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2402.17032.pdf) [Metamath]

   *Zhou, Jin Peng and Wu, Yuhuai and Li, Qiyang and Grosse, Roger*

## Datasets
### Data Collection

1. **Premise Selection for Mathematics by Corpus Analysis and Kernel Methods** `Journal of Automated Reasoning 2014` [[paper]](https://arxiv.org/pdf/1108.3446.pdf) [Mizar]

   *Alama, Jesse and Heskes, Tom and Kühlwein, Daniel and Tsivtsivadze, Evgeni and Urban, Josef*

1. **MizAR 40 for Mizar 40** `Journal of Automated Reasoning 2015` [[paper]](https://arxiv.org/pdf/1310.2805.pdf) [Mizar]

   *Kaliszyk, Cezary and Urban, Josef*

1. **The TPTP Problem Library and Associated Infrastructure** `Journal of Automated Reasoning 2017` [[paper]](https://link.springer.com/article/10.1007/s10817-017-9407-7) [TPTP]

   *Sutcliffe, Geoff*

1. **HolStep: A Machine Learning Dataset for Higher-Order Logic Theorem Proving** `ICLR 2017` [[paper]](https://arxiv.org/pdf/1703.00426.pdf) [HOL Light]

   *Kaliszyk, Cezary and Chollet, François and Szegedy, Christian*

1. **Reinforcement Learning of Theorem Proving** `NeurIPS 2018` [[paper]](https://arxiv.org/pdf/1805.07563.pdf) [Mizar]

   *Kaliszyk, Cezary and Urban, Josef and Michalewski, Henryk and Olšák, Miroslav*

1. **GamePad: A Learning Environment for Theorem Proving** `ICLR 2019` [[paper]](https://arxiv.org/pdf/1806.00608.pdf) [Coq]

   *Huang, Daniel and Dhariwal, Prafulla and Song, Dawn and Sutskever, Ilya*

1. **HOList: An Environment for Machine Learning of Higher-Order Logic Theorem Proving** `ICML 2019` [[paper]](https://arxiv.org/pdf/1904.03241.pdf) [HOL Light]

   *Kshitij Bansal and Sarah M. Loos and Markus Norman Rabe and Christian Szegedy and Stewart Wilcox*

1. **Learning to Prove Theorems via Interacting with Proof Assistants** `ICML 2019` [[paper]](https://arxiv.org/pdf/1905.09381.pdf) [Coq]

   *Yang, Kaiyu and Deng, Jia*

1. **TacticToe: Learning to Prove with Tactics** `Journal of Automated Reasoning 2020` [[paper]](https://arxiv.org/pdf/1804.00596.pdf) [HOL4]

   *Gauthier, Thibault and Kaliszyk, Cezary and Urban, Josef*

1. **Generative Language Modeling for Automated Theorem Proving** `arXiv 2020` [[paper]](https://arxiv.org/pdf/2009.03393.pdf) [pretraining, Metamath]

   *Polu, Stanislas and Sutskever, Ilya*

1. **The Tactician: A Seamless, Interactive Tactic Learner and Prover for Coq** `CICM 2020` [[paper]](https://arxiv.org/pdf/2008.00120.pdf) [Coq]

   *Blaauwbroek, Lasse and Urban, Josef and Geuvers, Herman*

1. **Natural Language Premise Selection: Finding Supporting Statements for Mathematical Text** `LREC 2020` [[paper]](https://aclanthology.org/2020.lrec-1.266.pdf) [NL]

   *Ferreira, Deborah and Freitas, André*

1. **IsarStep: A Benchmark for High-Level Mathematical Reasoning** `ICLR 2021` [[paper]](https://arxiv.org/pdf/2006.09265.pdf) [Isabelle]

   *Li, Wenda and Yu, Lei and Wu, Yuhuai and Paulson, Lawrence C*

1. **NaturalProofs: Mathematical Theorem Proving in Natural Language** `NeurIPS 2021` [[paper]](https://arxiv.org/pdf/2104.01112.pdf) [NL]

   *Welleck, Sean and Liu, Jiacheng and Bras, Ronan Le and Hajishirzi, Hannaneh and Choi, Yejin and Cho, Kyunghyun*

1. **LISA: Language Models of Isabelle Proofs** `AITP 2021` [[paper]](http://aitp-conference.org/2021/abstract/paper_17.pdf) [Isabelle]

   *Jiang, Albert Qiaochu and Li, Wenda and Han, Jesse Michael and Wu, Yuhuai*

1. **Proof Artifact Co-Training for Theorem Proving with Language Models** `ICLR 2022` [[paper]](https://arxiv.org/pdf/2102.06203.pdf) [Lean]

   *Han, Jesse Michael and Rute, Jason and Wu, Yuhuai and Ayers, Edward W and Polu, Stanislas*

1. **MiniF2F: A Cross-System Benchmark for Formal Olympiad-Level Mathematics** `ICLR 2022` [[paper]](https://arxiv.org/pdf/2109.00110.pdf) [Metamath, Lean, Isabelle, HOL Light]

   *Zheng, Kunhao and Han, Jesse Michael and Polu, Stanislas*

1. **UniGeo: Unifying Geometry Logical Reasoning via Reformulating Mathematical Expression** `EMNLP 2022` [[paper]](https://arxiv.org/pdf/2212.02746.pdf) [geometry]

   *Chen, Jiaqi and Li, Tong and Qin, Jinghui and Lu, Pan and Lin, Liang and Chen, Chongyu and Liang, Xiaodan*

1. **NaturalProver: Grounded Mathematical Proof Generation with Language Models** `NeurIPS 2022` [[paper]](https://arxiv.org/pdf/2205.12910.pdf) [NL]

   *Welleck, Sean and Liu, Jiacheng and Lu, Ximing and Hajishirzi, Hannaneh and Choi, Yejin*

1. **A Parallel Corpus of Natural Language and Isabelle Artefacts** `AITP 2022` [[paper]](https://aitp-conference.org/2022/abstract/AITP_2022_paper_8.pdf) [NL, Isabelle]

   *Bordg, Anthony and Stathopoulos, Yiannos A and Paulson, Lawrence C*

1. **Proof Repair Infrastructure for Supervised Models: Building a Large Proof Repair Dataset** `ITP 2023` [[paper]](https://drops.dagstuhl.de/storage/00lipics/lipics-vol268-itp2023/LIPIcs.ITP.2023.26/LIPIcs.ITP.2023.26.pdf) [Coq]

   *Reichel, Tom and Henderson, R and Touchet, Andrew and Gardner, Andrew and Ringer, Talia*

1. **BERT Is Not The Count: Learning to Match Mathematical Statements with Proofs** `EACL 2023` [[paper]](https://arxiv.org/pdf/2302.09350.pdf) [NL]

   *Li, Weixian Waylon and Ziser, Yftah and Coavoux, Maximin and Cohen, Shay B*


1. **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2306.15626.pdf) [Lean]

   *Yang, Kaiyu and Swope, Aidan and Gu, Alex and Chalamala, Rahul and Song, Peiyang and Yu, Shixing and Godil, Saad and Prenger, Ryan and Anandkumar, Anima*

1. **MLFMF: Data Sets for Machine Learning for Mathematical Formalization** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2310.16005.pdf) [Agda, Lean]

   *Bauer, Andrej and Petković, Matej and Todorovski, Ljupco*

1. **Mathematical Capabilities of ChatGPT** `NeurIPS 2023` [[paper]](https://arxiv.org/pdf/2301.13867.pdf) [NL]

   *Simon Frieder and Luca Pinchetti and Alexis Chevalier and Ryan-Rhys Griffiths and Tommaso Salvatori and Thomas Lukasiewicz and Philipp Christian Petersen and Julius Berner*

1. **TRIGO: Benchmarking Formal Mathematical Proof Reduction for Generative Language Models** `EMNLP 2023` [[paper]](https://arxiv.org/pdf/2310.10180.pdf) [Lean]

   *Xiong, Jing and Shen, Jianhao and Yuan, Ye and Wang, Haiming and Yin, Yichun and Liu, Zhengying and Li, Lin and Guo, Zhijiang and Cao, Qingxing and Huang, Yinya and Zheng, Chuanyang and Liang, Xiaodan and Zhang, Ming and Liu, Qun*

1. **Generative AI for Math: Part I - MathPile: A Billion-Token-Scale Pretraining Corpus for Math** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2312.17120.pdf) [pretraining]

   *Wang, Zengzhi and Xia, Rui and Liu, Pengfei*

1. **ProofNet: Autoformalizing and Formally Proving Undergraduate-Level Mathematics** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2302.12433.pdf) [pretraining, NL, Lean]

   *Azerbayev, Zhangir and Piotrowski, Bartosz and Schoelkopf, Hailey and Ayers, Edward W and Radev, Dragomir and Avigad, Jeremy*

1. **FIMO: A Challenge Formal Dataset for Automated Theorem Proving** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2309.04295.pdf) [NL, Lean]

   *Liu, Chengwu and Shen, Jianhao and Xin, Huajian and Liu, Zhengying and Yuan, Ye and Wang, Haiming and Ju, Wei and Zheng, Chuanyang and Yin, Yichun and Li, Lin and Zhang, Ming Zhang and Liu, Qun*

1. **FormalGeo: The First Step Toward Human-like IMO-level Geometric Automated Reasoning** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2310.18021.pdf) [geometry]

   *Zhang, Xiaokai and Zhu, Na and He, Yiming and Zou, Jia and Huang, Qike and Jin, Xiaoxiao and Guo, Yanjun and Mao, Chenyang and Li, Yang and Zhu, Zhe and Yue, Dengfeng and Zhu, Fangzhen and Wang, Yifan and Huang, Yiwen and Wang, Runan and Qin, Cheng and Zeng, Zhenbing and Xie, Shaorong and Luo, Xiangfeng and Leng, Tuo*

1. **Llemma: An Open Language Model for Mathematics** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.10631.pdf) [pretraining]

   *Azerbayev, Zhangir and Schoelkopf, Hailey and Paster, Keiran and Santos, Marco Dos and McAleer, Stephen and Jiang, Albert Q and Deng, Jia and Biderman, Stella and Welleck, Sean*

1. **Magnushammer: A Transformer-Based Approach to Premise Selection** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2303.04488.pdf) [Isabelle]

   *Mikuła, Maciej and Antoniak, Szymon and Tworkowski, Szymon and Jiang, Albert Qiaochu and Zhou, Jin Peng and Szegedy, Christian and Kuciński, Łukasz and Miłos, Piotr and Wu, Yuhuai*

1. **OpenWebMath: An Open Dataset of High-Quality Mathematical Web Text** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.06786.pdf) [pretraining]

   *Paster, Keiran and Santos, Marco Dos and Azerbayev, Zhangir and Ba, Jimmy*

1. **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.03300.pdf) [pretraining]

   *Shao, Zhihong and Wang, Peiyi and Zhu, Qihao and Xu, Runxin and Song, Junxiao and Zhang, Mingchuan and Li, YK and Wu, Y and Guo, Daya*

1. **InternLM-Math: Open Math Large Language Models Toward Verifiable Reasoning** `arXiv 2024` [[paper]](https://arxiv.org/pdf/2402.06332.pdf) [pretraining]

   *Ying, Huaiyuan and Zhang, Shuo and Li, Linyang and Zhou, Zhejian and Shao, Yunfan and Fei, Zhaoye and Ma, Yichuan and Hong, Jiawei and Liu, Kuikun and Wang, Ziyi and Wang, Yudong and Wu, Zijian and Li, Shuaibin and Zhou, Fengzhe and Liu, Hongwei and Zhang, Songyang and Zhang, Wenwei and Yan, Hang and Qiu, Xipeng and Wang, Jiayu and Chen, Kai and Lin, Dahua*

### Data Generation

1. **Learning to Reason in Large Theories without Imitation** `arXiv 2019` [[paper]](https://arxiv.org/pdf/1905.10501.pdf) [HOL Light]

   *Bansal, Kshitij and Szegedy, Christian and Rabe, Markus N and Loos, Sarah M and Toman, Viktor*

1. **Learning to Prove Theorems by Learning to Generate Theorems** `NeurIPS 2020` [[paper]](https://arxiv.org/pdf/2002.07019.pdf) [Metamath]

   *Wang, Mingzhe and Deng, Jia*

1. **INT: An Inequality Benchmark for Evaluating Generalization in Theorem Proving** `ICLR 2021` [[paper]](https://arxiv.org/pdf/2007.02924.pdf) [inequality]

   *Wu, Yuhuai and Jiang, Albert Qiaochu and Ba, Jimmy and Grosse, Roger*

1. **Training a First-Order Theorem Prover from Synthetic Data** `ICLR 2021 MATH-AI Workshop` [[paper]](https://arxiv.org/pdf/2103.03798.pdf) [saturation]

   *Firoiu, Vlad and Aygün, Eser and Anand, Ankit and Ahmed, Zafarali and Glorot, Xavier and Orseau, Laurent and Zhang, Lei and Precup, Doina and Mourad, Shibl*

1. **LIME: Learning Inductive Bias for Primitives of Mathematical Reasoning** `ICML 2021` [[paper]](https://arxiv.org/pdf/2101.06223.pdf) [reasoning primitives]

   *Wu, Yuhuai and Rabe, Markus N and Li, Wenda and Ba, Jimmy and Grosse, Roger B and Szegedy, Christian*

1. **Proving Theorems using Incremental Learning and Hindsight Experience Replay** `ICML 2022` [[paper]](https://arxiv.org/pdf/2112.10664.pdf) [saturation]

   *Aygün, Eser and Anand, Ankit and Orseau, Laurent and Glorot, Xavier and Mcaleer, Stephen M and Firoiu, Vlad and Zhang, Lei M and Precup, Doina and Mourad, Shibl*

1. **Synthetic Proof Term Data Augmentation for Theorem Proving with Language Models** `AITP 2022` [[paper]](https://aitp-conference.org/2022/abstract/AITP_2022_paper_5.pdf) [Lean]

   *Palermo, Joseph and Ye, Johnny and Han, Jesse Michael*

1. **Learning to Prove Trigonometric Identities** `arXiv 2022` [[paper]](https://arxiv.org/pdf/2207.06679.pdf) [trigonometric identity]

   *Liu, Zhou and Li, Yujun and Liu, Zhengying and Li, Lin and Li, Zhenguo*

1. **Formal Mathematics Statement Curriculum Learning** `ICLR 2023` [[paper]](https://arxiv.org/pdf/2202.01344.pdf) [Lean]

   *Polu, Stanislas and Han, Jesse Michael and Zheng, Kunhao and Baksys, Mantas and Babuschkin, Igor and Sutskever, Ilya*

1. **GeomVerse: A Systematic Evaluation of Large Models for Geometric Reasoning** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2312.12241.pdf) [geometry]

   *Kazemi, Mehran and Alvari, Hamidreza and Anand, Ankit and Wu, Jialin and Chen, Xi and Soricut, Radu*

1. **Multilingual Mathematical Autoformalization** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2311.03755.pdf) [NL, Isabelle, Lean]

   *Jiang, Albert Q and Li, Wenda and Jamnik, Mateja*

1. **Solving Olympiad Geometry without Human Demonstrations** `Nature 2024` [[paper]](https://www.nature.com/articles/s41586-023-06747-5) [geometry]

   *Trinh, Trieu H and Wu, Yuhuai and Le, Quoc V and He, He and Luong, Thang*

1. **LEGO-Prover: Neural Theorem Proving with Growing Libraries** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2310.00656.pdf) [Isabelle]

   *Wang, Haiming and Xin, Huajian and Zheng, Chuanyang and Li, Lin and Liu, Zhengying and Cao, Qingxing and Huang, Yinya and Xiong, Jing and Shi, Han and Xie, Enze and Yin, Jian and Li, Zhenguo and Liao, Heng and Liang, Xiaodan*

1. **REFACTOR: Learning to Extract Theorems from Proofs** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2402.17032.pdf) [Metamath]

   *Zhou, Jin Peng and Wu, Yuhuai and Li, Qiyang and Grosse, Roger*

1. **MUSTARD: Mastering Uniform Synthesis of Theorem and Proof Data** `ICLR 2024` [[paper]](https://arxiv.org/pdf/2402.08957.pdf) [NL, Lean]

   *Huang, Yinya and Lin, Xiaohan and Liu, Zhengying and Cao, Qingxing and Xin, Huajian and Wang, Haiming and Li, Zhenguo and Song, Linqi and Liang, Xiaodan*

## Related Surveys

1. **QED at Large: A Survey of Engineering of Formally Verified Software** `Foundations and Trends® in Programming Languages 2019` [[paper]](https://arxiv.org/pdf/2003.06458.pdf)

   *Ringer, Talia and Palmskog, Karl and Sergey, Ilya and Gligoric, Milos and Tatlock, Zachary*

1. **A Survey of Deep Learning for Mathematical Reasoning** `ACL 2023` [[paper]](https://arxiv.org/pdf/2212.10535.pdf)

   *Lu, Pan and Qiu, Liang and Yu, Wenhao and Welleck, Sean and Chang, Kai-Wei*

1. **Mathematical Language Models: A Survey** `arXiv 2023` [[paper]](https://arxiv.org/pdf/2312.07622.pdf)

   *Liu, Wentao and Hu, Hanglei and Zhou, Jie and Ding, Yuyang and Li, Junsong and Zeng, Jiayi and He, Mengliang and Chen, Qin and Jiang, Bo and Zhou, Aimin and He, Liang*

1. **Large Language Models for Mathematical Reasoning: Progresses and Challenges** `EACL 2024` [[paper]](https://arxiv.org/pdf/2402.00157.pdf)

   *Ahn, Janice and Verma, Rishu and Lou, Renze and Liu, Di and Zhang, Rui and Yin, Wenpeng*

1. **AI for Math Resources** `Google Sheet` [[link]](https://docs.google.com/document/d/1kD7H4E28656ua8jOGZ934nbH2HcBLyxcRgFDduH5iQ0/edit)

   *Available to Everyone*

## Citation
If you find this repository useful, please consider citing our survey paper:

```
@article{li2024dl4tp,
   title={A Survey on Deep Learning for Theorem Proving}, 
   author={Li, Zhaoyu and Sun, Jialiang and Murphy, Logan and Su, Qidong and Li, Zenan and Zhang, Xian and Yang, Kaiyu and Si, Xujie},
   journal={arXiv preprint arXiv:2404.09939},
   year={2024},
}
```
