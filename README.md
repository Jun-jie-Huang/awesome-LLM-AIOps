# Awesome LLM AIOps
![](https://img.shields.io/github/last-commit/Jun-jie-Huang/awesome-LLM-AIOps?color=blue) ![](https://img.shields.io/badge/PaperNumber-14-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 


A list of awesome academic researches and industrial materials about Large Language Model (LLM) and Artificial Intelligence for IT Operations (AIOps).


## Content
- [Awesome LLM AIOps](#awesome-llm-aiops)
  - [Introduction](#introduction)
    - [Keywords Convention](#keywords-convention)
  - [Papers](#papers)
    - [LLM as an Agent/Administrator](#llm-as-an-agentadministrator)
    - [LLM for Incident Management](#llm-for-incident-management)
    - [LLM for Log Analysis](#llm-for-log-analysis)
    - [Domain LLM](#domain-llm)
  - [Contribution](#contribution)
    - [Contributing to this paper list](#contributing-to-this-paper-list)

## Introduction

This is a list of awesome academic researches and industrial materials about Large Language Model (LLM) and Artificial Intelligence for IT Operations (AIOps).

### Keywords Convention

![](https://img.shields.io/badge/ChatGPT-blue) The abbreviation of the work.

![](https://img.shields.io/badge/Prompting-red) The utilized LLM techniques used in the work.

![](https://img.shields.io/badge/Root_Cause_Analysis-brown) The mainly explored task of the work.

![](https://img.shields.io/badge/Other-green) Other important information of the work.


## Papers
### LLM as an Agent/Administrator

- **Automatic Root Cause Analysis via Large Language Models for Cloud Incidents**. EuroSys 2024. ![](https://img.shields.io/badge/RCACopilot-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red)  ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/RCA_Classification-brown)

  *Yinfang Chen, Huaibing Xie, Minghua Ma, Yu Kang, Xin Gao, Liu Shi, Yunjie Cao, Xuedong Gao, Hao Fan, Ming Wen, Jun Zeng, Supriyo Ghosh, Xuchao Zhang, Qingwei Lin, Saravan Rajmohan, Dongmei Zhang, Tianyin Xu* [[pdf](https://arxiv.org/pdf/2305.15778.pdf)] 

- **LLM As DBA**. Preprint 2023. ![](https://img.shields.io/badge/D_Bot-blue) ![](https://img.shields.io/badge/Prompting(Tree_of_Thought)-red) ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/DB_Administor-brown)

  *Xuanhe Zhou, Guoliang Li, Zhiyuan Liu* [[pdf](https://arxiv.org/pdf/2308.05481.pdf)] [[project](https://github.com/TsinghuaDatabaseGroup/DB-GPT/tree/main#-customize)] 

### LLM for Incident Management

- **Recommending Root-Cause and Mitigation Steps for Cloud Incidents using Large Language Models**. ICSE 2023. ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/RCA_Generation-brown)

  *Toufique Ahmed, Supriyo Ghosh, Chetan Bansal, Thomas Zimmermann, Xuchao Zhang, Saravan Rajmohan* [[pdf](https://arxiv.org/pdf/2301.03797.pdf)] 


- **Assess and Summarize: Improve Outage Understanding with Large Language Models**. Preprint 2023. ![](https://img.shields.io/badge/Oasis-blue) ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Outage_Summarization-brown)

  *Pengxiang Jin, Shenglin Zhang, Minghua Ma, Haozhe Li, Yu Kang, Liqun Li, Yudong Liu, Bo Qiao, Chaoyun Zhang, Pu Zhao, Shilin He, Federica Sarro, Yingnong Dang, Saravan Rajmohan, Qingwei Lin, Dongmei Zhang* [[pdf](https://arxiv.org/pdf/2305.18084.pdf)] 


- **PACE-LM: Prompting and Augmentation for Calibrated Confidence Estimation with GPT-4 in Cloud Incident Root Cause Analysis**. Preprint 2023. ![](https://img.shields.io/badge/PACE_LM-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/RCA_Confidence_Estimation-brown)

  *Dylan Zhang, Xuchao Zhang, Chetan Bansal, Pedro Las-Casas, Rodrigo Fonseca, Saravan Rajmohan* [[pdf](https://arxiv.org/pdf/2309.05833.pdf)] 

- **A Holistic View of AI-driven Network Incident Management**. Preprint  2023.  ![](https://img.shields.io/badge/Incident_Lifecycle-brown) ![](https://img.shields.io/badge/Analysis-green)

  *Pouya Hamadanian, Behnaz Arzani, Sadjad Fouladi, Siva Kesava Reddy Kakarla, Rodrigo Fonseca, Denizcan Billor, Ahmad Cheema, Edet Nkposong, Ranveer Chandra* [[pdf](https://www.microsoft.com/en-us/research/uploads/prod/2023/09/LLM4IcMs___HotNets__23-6.pdf)] 

### LLM for Log Analysis

- **Log Parsing: How Far Can ChatGPT Go?**. ASE-NIER 2023. ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)

  *Van-Hoang Le and Hongyu Zhang* [[pdf](https://arxiv.org/pdf/2306.01590.pdf)] [[project](https://github.com/LogIntelligence/log-analytics-chatgpt)]


- **Log-based Anomaly Detection based on EVT Theory with feedback**. Preprint 2023. ![](https://img.shields.io/badge/LLMParser-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown)

  *Zhihan Jiang, Jinyang Liu, Zhuangbin Chen, Yichen Li, Junjie Huang, Yintong Huo, Pinjia He, Jiazhen Gu, Michael R. Lyu* [[pdf](https://arxiv.org/pdf/2306.05032.pdf)] 

- **Exploring the Effectiveness of LLMs in Automated Logging Generation: An Empirical Study**. Preprint 2023. ![](https://img.shields.io/badge/LogBench-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Logging-brown) ![](https://img.shields.io/badge/Analysis-green)

  *Yichen Li, Yintong Huo, Zhihan Jiang, Renyi Zhong, Pinjia He, Yuxin Su, Michael R. Lyu* [[pdf](https://arxiv.org/pdf/2307.05950.pdf)] [[project](https://github.com/LogStudySE/LogStudy)] 

- **Prompting for Automatic Log Template Extraction**. Preprint 2023. ![](https://img.shields.io/badge/LogDiv-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)

  *Junjielong Xu, Ruichun Yang, Yintong Huo, Chengyu Zhang, Pinjia He* [[pdf](https://arxiv.org/pdf/2307.09950.pdf)] 

- **LogPrompt: Prompt Engineering Towards Zero-Shot and Interpretable Log Analysis**. Preprint 2023. ![](https://img.shields.io/badge/LogPrompt-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown)

  *Yilun Liu, Shimin Tao, Weibin Meng, Jingyu Wang, Wenbing Ma, Yanqing Zhao, Yuhang Chen, Hao Yang, Yanfei Jiang, Xun Chen* [[pdf](https://arxiv.org/pdf/2308.07610.pdf)]

- **LogGPT: Exploring ChatGPT for Log-Based Anomaly Detection**. Preprint 2023. ![](https://img.shields.io/badge/LogGPT-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown)

  *Jiaxing Qi, Shaohan Huang, Zhongzhi Luan, Carol Fung, Hailong Yang, Depei Qian* [[pdf](https://arxiv.org/pdf/2309.01189.pdf)] 

- **LLMParser: A LLM-based Log Parsing Framework**. Preprint 2023. ![](https://img.shields.io/badge/LLMParser-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Cache-red) ![](https://img.shields.io/badge/Log_Parsing-brown)

  *Zhihan Jiang, Jinyang Liu, Zhuangbin Chen, Yichen Li, Junjie Huang, Yintong Huo, Pinjia He, Jiazhen Gu, Michael R. Lyu* [[pdf](https://arxiv.org/pdf/2310.01796.pdf)] 

### Domain LLM

- **OWL: A Large Language Model for IT Operations**. Preprint 2023. ![](https://img.shields.io/badge/OWL-blue) ![](https://img.shields.io/badge/Instrcuction_Tuning-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown) ![](https://img.shields.io/badge/Domain_LLM-green)

  *Hongcheng Guo, Jian Yang, Jiaheng Liu, Liqun Yang, Linzheng Chai, Jiaqi Bai, Junran Peng, Xiaorong Hu, Chao Chen, Dongfeng Zhang, Xu Shi, Tieqiao Zheng, Liangfan Zheng, Bo Zhang, Ke Xu, Zhoujun Li* [[pdf](https://arxiv.org/pdf/2309.09298.pdf)] [[project](https://github.com/HC-Guo/Owl)] 



## Contribution

### Contributing to this paper list

- First, think about which category the work should belong to.
- Second, use the same format as the others to discribe the work. Note that there should be an empty line between the title and the authors list, and take care of the indentation.
- Then, add [keywords tags](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps/blob/main/README.md#keywords-convention). Add the pdf link of the paper. If it is an arxiv publication, we prefer /abs/ format to /pdf/ format.

**Don't worry if you put all these wrong, we will fix them for you.** Just contribute and promote your awesome work here!

If you recommended a work that wasn't yours, you will be added to the contributor list (be sure to provide your information in [other contributors](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps/blob/main/README.md#other-contributors)).

