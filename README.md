# Awesome LLM AIOps
![](https://img.shields.io/github/last-commit/Jun-jie-Huang/awesome-LLM-AIOps?color=blue) ![](https://img.shields.io/badge/PaperNumber-29-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 


A list of awesome academic researches and industrial materials about Large Language Model (LLM) and Artificial Intelligence for IT Operations (AIOps).


## Content
- [Awesome LLM AIOps](#awesome-llm-aiops)
  - [Introduction](#introduction)
    - [Keywords Convention](#keywords-convention)
  - [Papers](#papers)
    - [LLM Agent](#llm-agent)
    - [LLM for Incident Management](#llm-for-incident-management)
    - [LLM for Log Analysis](#llm-for-log-analysis)
    - [AIOps Question Answering](#aiops-question-answering)
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
### LLM Agent

1. [**EuroSys 24**] [Automatic Root Cause Analysis via Large Language Models for Cloud Incidents](https://arxiv.org/pdf/2305.15778.pdf). ![](https://img.shields.io/badge/RCACopilot-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red)  ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/RCA_Classification-brown)
2. [**Preprint 2023**] [D-Bot: Database Diagnosis System using Large Language Models](https://arxiv.org/pdf/2312.01454.pdf) [[project](https://github.com/TsinghuaDatabaseGroup/DB-GPT)]. ![](https://img.shields.io/badge/D_Bot-blue) ![](https://img.shields.io/badge/Prompting(Tree_of_Thought)-red) ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/DB_Administor-brown)
3. [**Preprint 2023**] [RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models](https://arxiv.org/pdf/2310.16340.pdf). ![](https://img.shields.io/badge/RCAgent-blue) ![](https://img.shields.io/badge/LLM_Agent-red) ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/RCA-brown)

### LLM for Incident Management

1. [**ICSE 2023**] [Recommending Root-Cause and Mitigation Steps for Cloud Incidents using Large Language Models](https://arxiv.org/pdf/2301.03797.pdf). ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Root_Cause_Generation-brown)
2. [**HotNets 2023**] [A Holistic View of AI-driven Network Incident Management](https://www.microsoft.com/en-us/research/uploads/prod/2023/09/LLM4IcMs___HotNets__23-6.pdf). ![](https://img.shields.io/badge/Incident_Lifecycle-brown) ![](https://img.shields.io/badge/Analysis-green)
3. [**ESEC/FSE Industry 2023**] [Assess and Summarize: Improve Outage Understanding with Large Language Models](https://dl.acm.org/doi/10.1145/3611643.3613891). ![](https://img.shields.io/badge/Oasis-blue) ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Outage_Summarization-brown)
4. [**ICSE 2024**] [Xpert: Empowering Incident Management with Query Recommendations via Large Language Models](https://arxiv.org/pdf/2305.18084.pdf). ![](https://img.shields.io/badge/Xpert-blue)![](https://img.shields.io/badge/Prompting-red)
5. [**ICSE-SEIP 2024**] [Knowledge-aware Alert Aggregation in Large-scale Cloud Systems: a Hybrid Approach](https://arxiv.org/pdf/2403.06485.pdf). ![](https://img.shields.io/badge/COLA-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Alert_Aggregation-brown)
6. [**Preprint 2023**] [PACE-LM: Prompting and Augmentation for Calibrated Confidence Estimation with GPT-4 in Cloud Incident Root Cause Analysis](https://arxiv.org/pdf/2309.05833.pdf). ![](https://img.shields.io/badge/PACE_LM-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/RCA_Confidence_Estimation-brown)
7. [**Preprint 2024**] [Automated Root Causing of Cloud Incidents using In-Context Learning with GPT-4](https://arxiv.org/pdf/2401.13810v1.pdf). ![](https://img.shields.io/badge/Prompting(ICL)-red)![](https://img.shields.io/badge/Root_Cause_Generation-brown)
8. [**Preprint 2024**] [X-lifecycle Learning for Cloud Incident Management using LLMs](https://arxiv.org/pdf/2404.03662). ![](https://img.shields.io/badge/Prompting(ICL)-red)![](https://img.shields.io/badge/Root_Cause_Generation-brown)
9. [**Preprint 2024**] [Exploring LLM-based Agents for Root Cause Analysis](https://arxiv.org/pdf/2403.04123). ![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Generation-brown)
10. [**Preprint 2024**] [Nissist: An Incident Mitigation Copilot based on Troubleshooting Guides](https://arxiv.org/pdf/2402.17531). ![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Mitigation_Action_Generation-brown)
11. [**Preprint 2024**] [mABC: Multi-Agent Blockchain-inspired Collaboration for Root Cause Analysis in Micro-Services Architecture](https://arxiv.org/pdf/2404.12135). ![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Localization-brown)

### LLM for Log Analysis

1. [**ASE-NIER 2023**] [Log Parsing: How Far Can ChatGPT Go?](https://arxiv.org/pdf/2306.01590.pdf) [[project](https://github.com/LogIntelligence/log-analytics-chatgpt)]. ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
2. [**ICSE 2024**] [UniLog: Automatic Logging via LLM and In-Context Learning](https://www.computer.org/csdl/proceedings-article/icse/2024/021700a129/1RLIWpCelqg). ![](https://img.shields.io/badge/UniLog-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Cache-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown)
3. [**ICSE 2024**] [DivLog: Log Parsing with Prompt Enhanced In-Context Learning](https://arxiv.org/pdf/2307.09950.pdf). ![](https://img.shields.io/badge/DivLog-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
4. [**FSE 2024**] [LILAC: Log Parsing using LLMs with Adaptive Parsing Cache](https://arxiv.org/pdf/2310.01796.pdf). ![](https://img.shields.io/badge/LILAC-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Cache-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
5. [**FSE 2024**] [Go Static: Contextualized Logging Statement Generation](https://arxiv.org/pdf/2402.12958.pdf). ![](https://img.shields.io/badge/SCLogger-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown)
6. [**Preprint 2023**] [Log-based Anomaly Detection based on EVT Theory with feedback](https://arxiv.org/pdf/2306.05032.pdf). ![](https://img.shields.io/badge/LLMParser-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown)
7. [**Preprint 2023**] [Exploring the Effectiveness of LLMs in Automated Logging Generation: An Empirical Study](https://arxiv.org/pdf/2307.05950.pdf) [[project](https://github.com/LogStudySE/LogStudy)]. ![](https://img.shields.io/badge/LogBench-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown) ![](https://img.shields.io/badge/Analysis-green)
8. [**Preprint 2023**] [LogPrompt: Prompt Engineering Towards Zero-Shot and Interpretable Log Analysis](https://arxiv.org/pdf/2308.07610.pdf). ![](https://img.shields.io/badge/LogPrompt-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown)
9. [**Preprint 2023**] [LogGPT: Exploring ChatGPT for Log-Based Anomaly Detection](https://arxiv.org/pdf/2309.01189.pdf). ![](https://img.shields.io/badge/LogGPT-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown)
10. [**Preprint 2023**] [LEMUR : Log Parsing with Entropy Sampling and Chain-of-Thought Merging](https://arxiv.org/pdf/2309.01189.pdf). ![](https://img.shields.io/badge/LEMUR-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red) ![](https://img.shields.io/badge/LogParsing-brown)
11. [**Preprint 2024**] [RAGLog: Log Anomaly Detection using Retrieval Augmented Generation](https://arxiv.org/pdf/2311.05261.pdf). ![](https://img.shields.io/badge/RAGLog-blue) ![](https://img.shields.io/badge/Prompting(RAG)-red) ![](https://img.shields.io/badge/LogAD-brown)

### AIOps Question Answering

1. [**EMNLP Industry 2023**] [Empower Large Language Model to Perform Better on Industrial Domain-Specific Question Answering](https://aclanthology.org/2023.emnlp-industry.29.pdf) [[project](https://github.com/ModelInteraction/MSQA)]. ![](https://img.shields.io/badge/MSQA-blue) ![](https://img.shields.io/badge/Instrcuction_Tuning-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)
2. [**ICLR 2024**] [OWL: A Large Language Model for IT Operations](https://openreview.net/pdf?id=SZOQ9RKYJu) [[project](https://github.com/HC-Guo/Owl)]. ![](https://img.shields.io/badge/OWL-blue) ![](https://img.shields.io/badge/Instrcuction_Tuning-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown)![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Domain_LLM-green)![](https://img.shields.io/badge/Benchmark-green)
3. [**Preprint 2023**] [An Empirical Study of NetOps Capability of Pre-Trained Large Language Models](https://arxiv.org/pdf/2309.05557.pdf) [[project](https://huggingface.co/datasets/NASP/neteval-exam)]. ![](https://img.shields.io/badge/NetEval-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)
4. [**Preprint 2023**] [OpsEval: A Comprehensive Task-Oriented AIOps Benchmark for Large Language Models](https://arxiv.org/pdf/2310.07637.pdf) [[project](https://opseval.cstcloud.cn/content/home#home)]. ![](https://img.shields.io/badge/OpsEval-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)





## Contribution

### Contributing to this paper list

- First, think about which category the work should belong to.
- Second, use the same format as the others to discribe the work. Note that there should be an empty line between the title and the authors list, and take care of the indentation.
- Then, add [keywords tags](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps/blob/main/README.md#keywords-convention). Add the pdf link of the paper. If it is an arxiv publication, we prefer /abs/ format to /pdf/ format.

**Don't worry if you put all these wrong, we will fix them for you.** Just contribute and promote your awesome work here!

If you recommended a work that wasn't yours, you will be added to the contributor list (be sure to provide your information in [other contributors](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps/blob/main/README.md#other-contributors)).

