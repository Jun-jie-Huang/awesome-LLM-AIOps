# Awesome LLM AIOps
![](https://badgen.net/github/last-commit/Jun-jie-Huang/awesome-LLM-AIOps) ![](https://img.shields.io/badge/PaperNumber-63-brightgreen) ![](https://img.shields.io/badge/PRs-Welcome-red) 


A list of awesome academic researches and industrial materials about Large Language Model (LLM) and Artificial Intelligence for IT Operations (AIOps).

## Content

- [Awesome LLM AIOps](#awesome-llm-aiops)
  * [Content](#content)
  * [Introduction](#introduction)
      - [Keywords Convention](#keywords-convention)
  * [1. LLM for Incident Management](#1-llm-for-incident-management)
      - [1.1 Incident Lifecycle](#11-incident-lifecycle)
      - [1.2 Incident Reporting](#12-incident-reporting)
      - [1.3 Root Cause Analysis](#13-root-cause-analysis)
      - [1.4 Incident Mitigation](#14-incident-mitigation)
      - [1.5 Incident Postmortem Analysis](#15-incident-postmortem-analysis)
      - [1.6 AIOps Question Answering](#16-aiops-question-answering)
  * [2. LLM for Log Analysis](#2-llm-for-log-analysis)
      - [2.1 Log Parsing](#21-log-parsing)
      - [2.2 Log Anomaly Detection](#22-log-anomaly-detection)
      - [2.3 Logging Statement Generation](#23-logging-statement-generation)
  * [3. LLM for Infrastructure Management](#3-llm-for-infrastructure-management)
      - [3.1 Benchmark](#31-benchmark)
      - [3.2 Vision](#32-vision)
      - [3.3 Infrastructure-as-Code](#33-infrastructure-as-code)
  * [Contribution](#contribution)
    + [Contributing to this paper list](#contributing-to-this-paper-list)

## Introduction

This is a list of awesome academic researches and industrial materials about Large Language Model (LLM) and Artificial Intelligence for IT Operations (AIOps).

#### Keywords Convention

![](https://img.shields.io/badge/ChatGPT-blue) The abbreviation of the work.

![](https://img.shields.io/badge/Prompting-red) The utilized LLM techniques used in the work.

![](https://img.shields.io/badge/Root_Cause_Analysis-brown) The mainly explored task of the work.

![](https://img.shields.io/badge/Other-green) Other important information of the work.

## 1. LLM for Incident Management

#### 1.0 Survey & Benchmark

1. [**Preprint 2024**] [A Survey of AIOps for Failure Management in the Era of Large Language Models](https://arxiv.org/pdf/2406.11213).
2. [**Preprint 2024**] [AI Assistants for Incident Lifecycle in a Microservice Environment: A Systematic Literature Review](https://arxiv.org/pdf/2410.04334).
3. [**MLSys 2025**] [AIOpsLab: A Holistic Framework for Evaluating AI Agents for Enabling Autonomous Cloud](https://arxiv.org/pdf/2501.06706). ![](https://img.shields.io/badge/AIOpsLab-blue) ![](https://img.shields.io/badge/Benchmark-brown)
4. [**ICML 2025**] [ITBench: Evaluating AI Agents across Diverse Real-World IT Automation Tasks](https://arxiv.org/pdf/2502.05352). ![](https://img.shields.io/badge/ITBench-blue) ![](https://img.shields.io/badge/Benchmark-brown)

#### 1.1 Incident Management

1. [**NDSS 2026**] [Incident Response Planning Using a Lightweight Large Language Model with Reduced Hallucination](https://www.ndss-symposium.org/ndss-paper/incident-response-planning-using-a-lightweight-large-language-model-with-reduced-hallucination/). ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Prompting(ICL)-red)
2. [**SoCC 2024**] [Building AI Agents for Autonomous Clouds: Challenges and Design Principles](https://arxiv.org/pdf/2407.12165). ![](https://img.shields.io/badge/Vision_Paper-green)
3. [**VLDB 2024**] [D-Bot: Database Diagnosis System using Large Language Models](https://arxiv.org/pdf/2312.01454.pdf) [[project](https://github.com/TsinghuaDatabaseGroup/DB-GPT)]. ![](https://img.shields.io/badge/D_Bot-blue) ![](https://img.shields.io/badge/Prompting(Tree_of_Thought)-red) ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/DB_Administor-brown)
4. [**HotNets 2023**] [A Holistic View of AI-driven Network Incident Management](https://www.microsoft.com/en-us/research/uploads/prod/2023/09/LLM4IcMs___HotNets__23-6.pdf). ![](https://img.shields.io/badge/Incident_Lifecycle-brown) ![](https://img.shields.io/badge/Analysis-green)
5. [**Preprint 2024**] [FLASH: A Workflow Automation Agent for Diagnosing Recurring Incidents](https://www.microsoft.com/en-us/research/uploads/prod/2024/10/FLASH_Paper.pdf). ![](https://img.shields.io/badge/FLASH-blue) ![](https://img.shields.io/badge/Incident_Diagnosis-brown)
6. [**NSDI 2024**] [NetAssistant: Dialogue Based Network Diagnosis in Data Center Networks](https://www.usenix.org/system/files/nsdi24-wang-haopei.pdf). ![](https://img.shields.io/badge/NetAssistant-blue) ![](https://img.shields.io/badge/Incident_Diagnosis-brown)
7. [**ASE 2025**] [AlertGuardian: Intelligent Alert Life-Cycle Management for Large-scale Cloud Systems](https://arxiv.org/abs/2601.14912)  ![](https://img.shields.io/badge/AlertGuardian-blue) ![](https://img.shields.io/badge/Agent-red) ![](https://img.shields.io/badge/Lifecycle-brown)

#### 1.2 Incident Reporting

1. [**ICSE-SEIP 2024**] [Knowledge-aware Alert Aggregation in Large-scale Cloud Systems: a Hybrid Approach](https://arxiv.org/pdf/2403.06485.pdf). ![](https://img.shields.io/badge/COLA-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Alert_Aggregation-brown)
2. [**ISSRE 2024**] [Large Language Models Can Provide Accurate and Interpretable Incident Triage](https://www.microsoft.com/en-us/research/uploads/prod/2024/08/ISSRE24_LLM4triage.pdf). ![](https://img.shields.io/badge/COMET-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Incident_Triage-brown)
3. [**FSE Industry 2024**] [MonitorAssistant: Simplifying Cloud Service Monitoring via Large Language Models](https://netman.aiops.org/wp-content/uploads/2024/07/MonitorAssistant_CameraReady-v1.5_submitted.pdf). ![](https://img.shields.io/badge/MonitorAssistant-blue) ![](https://img.shields.io/badge/Anomaly_Detection-brown)
4. [**ESEC/FSE Industry 2023**] [Assess and Summarize: Improve Outage Understanding with Large Language Models](https://arxiv.org/pdf/2305.18084). ![](https://img.shields.io/badge/Oasis-blue) ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Outage_Summarization-brown)
5. [**Preprint 2024**] [Large Language Models can Deliver Accurate and Interpretable Time Series Anomaly Detection](https://arxiv.org/pdf/2405.15370v1). ![](https://img.shields.io/badge/LLMAD-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red) ![](https://img.shields.io/badge/Anomaly_Detection-brown)
6. [**Preprint 2025**] [Argos: Agentic Time-Series Anomaly Detection with Autonomous Rule Generation via Large Language Models](https://arxiv.org/pdf/2501.14170). ![](https://img.shields.io/badge/Argos-blue) ![](https://img.shields.io/badge/Agent-red) ![](https://img.shields.io/badge/Anomaly_Detection-brown)


#### 1.3 Root Cause Analysis

1. [**ICSE 2023**] [Recommending Root-Cause and Mitigation Steps for Cloud Incidents using Large Language Models](https://arxiv.org/pdf/2301.03797.pdf). ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Root_Cause_Generation-brown)
2. [**EuroSys 2024**] [Automatic Root Cause Analysis via Large Language Models for Cloud Incidents](https://arxiv.org/pdf/2305.15778.pdf). ![](https://img.shields.io/badge/RCACopilot-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red) ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/RCA_Classification-brown)
3. [**ICSE 2024**] [Xpert: Empowering Incident Management with Query Recommendations via Large Language Models](https://arxiv.org/pdf/2312.11988). ![](https://img.shields.io/badge/Xpert-blue)![](https://img.shields.io/badge/Prompting-red)![](https://img.shields.io/badge/Diagnosis_Query_Generation-brown)
4. [**ASE 2024**] [The Potential of One-Shot Failure Root Cause Analysis: Collaboration of the Large Language Model and Small Classifier](https://dl.acm.org/doi/10.1145/3691620.3695475). ![](https://img.shields.io/badge/LasRCA-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Fault_Classification-brown)
5. [**FSE Industry 2024**] [LM-PACE: Confidence Estimation by Large Language Models for Effective Root Causing of Cloud Incidents](https://arxiv.org/pdf/2309.05833.pdf). ![](https://img.shields.io/badge/PACE_LM-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/RCA_Confidence_Estimation-brown)
6. [**FSE Industry 2024**] [Automated Root Causing of Cloud Incidents using In-Context Learning with GPT-4](https://arxiv.org/pdf/2401.13810v1.pdf). ![](https://img.shields.io/badge/Prompting(ICL)-red)![](https://img.shields.io/badge/Root_Cause_Generation-brown)
7. [**FSE Industry 2024**] [X-lifecycle Learning for Cloud Incident Management using LLMs](https://arxiv.org/pdf/2404.03662). ![](https://img.shields.io/badge/Prompting(ICL)-red)![](https://img.shields.io/badge/Root_Cause_Generation-brown)
8. [**FSE Industry 2024**] [Exploring LLM-based Agents for Root Cause Analysis](https://arxiv.org/pdf/2403.04123). ![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Generation-brown)
9. [**CIKM 2024**] [RCAgent: Cloud Root Cause Analysis by Autonomous Agents with Tool-Augmented Large Language Models](https://arxiv.org/pdf/2310.16340.pdf). ![](https://img.shields.io/badge/RCAgent-blue) ![](https://img.shields.io/badge/LLM_Agent-red) ![](https://img.shields.io/badge/System-green) ![](https://img.shields.io/badge/Root_Cause_Generation-brown)
10. [**EMNLP 2024 (Findings)**] [mABC: Multi-Agent Blockchain-inspired Collaboration for Root Cause Analysis in Micro-Services Architecture](https://arxiv.org/pdf/2404.12135). ![](https://img.shields.io/badge/mABC-blue)![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Localization-brown)
11. [**WWW industry 2025**] [Flow-of-Action: SOP Enhanced LLM-Based Multi-Agent System for Root Cause Analysis](https://www.arxiv.org/pdf/2502.08224). ![](https://img.shields.io/badge/Flow_of_Action-blue)![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Analysis-brown)
12. [**ICLR 2025**] [OpenRCA: Can Large Language Models Locate the Root Cause of Software Failures?](https://openreview.net/pdf?id=M4qNIzQYpd). ![](https://img.shields.io/badge/OpenRCA-blue)![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Localization-brown)![](https://img.shields.io/badge/Benchmark-green)
13. [**Preprint 2024**] [Cloud Atlas: Efficient Fault Localization for Cloud Systems using Language Models and Causal Insight](https://arxiv.org/pdf/2407.08694). ![](https://img.shields.io/badge/Atlas-blue)![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Fault_Localization-brown)
14. [**Preprint 2025**] [AgentFM: Role-Aware Failure Management for Distributed Databases with LLM-Driven Multi-Agents](https://arxiv.org/pdf/2504.06614)  ![](https://img.shields.io/badge/AgentFM-blue) ![](https://img.shields.io/badge/Agent-red) ![](https://img.shields.io/badge/Root_Cause_Analysis-green)
15. [**Preprint 2025**] [ThinkFL: Self-Refining Failure Localization for Microservice Systems via Reinforcement Fine-Tuning](https://arxiv.org/abs/2504.18776). ![](https://img.shields.io/badge/ThinkFL-blue)![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Fault_Localization-brown)
16. [**Preprint 2025**] [eARCO: Efficient Automated Root Cause Analysis with Prompt Optimization](https://arxiv.org/pdf/2504.11505)  ![](https://img.shields.io/badge/eARCO-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Root_Cause_Analysis-green)
17. [**ICSE 2025**] [COCA: Generative Root Cause Analysis for Distributed Systems with Code Knowledge](https://arxiv.org/abs/2503.23051v1)  ![](https://img.shields.io/badge/COCA-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Root_Cause_Analysis-green)
18. [**Preprint 2025**] [FVDebug: An LLM-Driven Debugging Assistant for Automated Root Cause Analysis of Formal Verification Failures](https://arxiv.org/abs/2510.15906)  ![](https://img.shields.io/badge/FVDebug-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Root_Cause_Analysis-green)
19. [**FSE2 2026**] [Rethinking the Evaluation of Microservice RCA with a Fault Propagation-Aware Benchmark](https://arxiv.org/pdf/2510.04711).  ![](https://img.shields.io/badge/OpenRCA-blue)![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Root_Cause_Localization-brown)![](https://img.shields.io/badge/Benchmark-green)

#### 1.4 Incident Mitigation

1. [**SIGOPS 2024**] [LLexus: an AI agent system for incident management](https://www.microsoft.com/en-us/research/publication/llexus-an-ai-agent-system-for-incident-management/).![](https://img.shields.io/badge/LLexus-blue) ![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Mitigation_Generation-brown)
2. [**FSE Industry 2024**] [Leveraging Large Language Models for the Auto-remediation of Microservice Applications - An Experimental Study](https://dl.acm.org/doi/pdf/10.1145/3663529.3663855).  ![](https://img.shields.io/badge/Mitigation_Action_Generation-brown)
3. [**ECAI 2024**] [Nissist: An Incident Mitigation Copilot based on Troubleshooting Guides](https://arxiv.org/pdf/2402.17531).![](https://img.shields.io/badge/Nissist-blue) ![](https://img.shields.io/badge/Agent-red)![](https://img.shields.io/badge/Mitigation_Action_Generation-brown)
4. [**Preprint 2024**] [Retrieval Augmented Generation-Based Incident Resolution Recommendation System for IT Support](https://arxiv.org/pdf/2409.13707).  ![](https://img.shields.io/badge/Mitigation_Action_Generation-brown)

#### 1.5 Incident Postmortem Analysis

1. [**ICSE-SEIP 2024**] [FaultProfIT: Hierarchical Fault Profiling of Incident Tickets in Large-scale Cloud Systems](https://dl.acm.org/doi/pdf/10.1145/3639477.3639754).![](https://img.shields.io/badge/FaultProfIT-blue) ![](https://img.shields.io/badge/Finetuning-red)![](https://img.shields.io/badge/Fault_Profiling-brown)
2. [**ASE 2024**] [FAIL: Analyzing Software Failures from the News Using LLMs](https://arxiv.org/pdf/2406.08221).![](https://img.shields.io/badge/FAIL-blue) ![](https://img.shields.io/badge/Prompting-red)![](https://img.shields.io/badge/Failure_Analysis-brown)

#### 1.6 AIOps Question Answering

1. [**EMNLP Industry 2023**] [Empower Large Language Model to Perform Better on Industrial Domain-Specific Question Answering](https://aclanthology.org/2023.emnlp-industry.29.pdf) [[project](https://github.com/ModelInteraction/MSQA)]. ![](https://img.shields.io/badge/MSQA-blue) ![](https://img.shields.io/badge/Instrcuction_Tuning-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)
2. [**ICLR 2024**] [OWL: A Large Language Model for IT Operations](https://openreview.net/pdf?id=SZOQ9RKYJu) [[project](https://github.com/HC-Guo/Owl)]. ![](https://img.shields.io/badge/OWL-blue) ![](https://img.shields.io/badge/Instrcuction_Tuning-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown)![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Domain_LLM-green)![](https://img.shields.io/badge/Benchmark-green)
3. [**SANER 2024**] [Gloss: Guiding Large Language Models to Answer Questions from System Logs](https://ieeexplore.ieee.org/abstract/document/10589781). ![](https://img.shields.io/badge/Gloss-blue) ![](https://img.shields.io/badge/Data_Synthesis-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)
4. [**Preprint 2023**] [An Empirical Study of NetOps Capability of Pre-Trained Large Language Models](https://arxiv.org/pdf/2309.05557.pdf) [[project](https://huggingface.co/datasets/NASP/neteval-exam)]. ![](https://img.shields.io/badge/NetEval-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)
5. [**Preprint 2023**] [OpsEval: A Comprehensive Task-Oriented AIOps Benchmark for Large Language Models](https://arxiv.org/pdf/2310.07637.pdf) [[project](https://opseval.cstcloud.cn/content/home#home)]. ![](https://img.shields.io/badge/OpsEval-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/QuestionAnswering-brown) ![](https://img.shields.io/badge/Benchmark-green)

## 2. LLM for Log Analysis

#### 2.1 Log Parsing

1. [**ISSTA 2024**] [A Large-Scale Evaluation for Log Parsing Techniques: How Far Are We?](https://arxiv.org/pdf/2308.10828). ![](https://img.shields.io/badge/LogHub2.0-blue) ![](https://img.shields.io/badge/Benchmark-green)![](https://img.shields.io/badge/Log_Parsing-brown)
2. [**ASE-NIER 2023**] [Log Parsing: How Far Can ChatGPT Go?](https://arxiv.org/pdf/2306.01590.pdf) [[project](https://github.com/LogIntelligence/log-analytics-chatgpt)]. ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
3. [**ICSE 2024**] [DivLog: Log Parsing with Prompt Enhanced In-Context Learning](https://arxiv.org/pdf/2307.09950.pdf). ![](https://img.shields.io/badge/DivLog-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
4. [**ICSE 2024**] [LLMParser: An Exploratory Study on Using Large Language Models for Log Parsing](https://arxiv.org/pdf/2404.18001). ![](https://img.shields.io/badge/LLMParser-blue) ![](https://img.shields.io/badge/Prompting-red)![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
5. [**FSE 2024**] [LILAC: Log Parsing using LLMs with Adaptive Parsing Cache](https://arxiv.org/pdf/2310.01796.pdf). ![](https://img.shields.io/badge/LILAC-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Cache-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
6. [**ICPC 2024**] [Interpretable Online Log Analysis Using Large Language Models with Prompt Strategies](https://arxiv.org/pdf/2308.07610.pdf). ![](https://img.shields.io/badge/LogPrompt-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown)
7. [**Preprint 2024**] [LEMUR : Log Parsing with Entropy Sampling and Chain-of-Thought Merging](https://arxiv.org/pdf/2402.18205.pdf). ![](https://img.shields.io/badge/LEMUR-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red) ![](https://img.shields.io/badge/LogParsing-brown)
8. [**Preprint 2024**] [HELP: Hierarchical Embeddings-based Log Parsing](https://arxiv.org/pdf/2402.18205.pdf). ![](https://img.shields.io/badge/HELP-blue) ![](https://img.shields.io/badge/Prompting(CoT)-red) ![](https://img.shields.io/badge/LogParsing-brown)
9. [**ASE 2024**] [Stronger, Cheaper and Demonstration-Free Log Parsing with LLMs](https://arxiv.org/pdf/2406.06156). ![](https://img.shields.io/badge/LogBatcher-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Log_Parsing-brown)
10. [**ICPC 2025**] [Log Parsing with Self-Generated In-Context Learning and Self-Correction](https://arxiv.org/pdf/2406.03376). ![](https://img.shields.io/badge/AdaParser-blue) ![](https://img.shields.io/badge/Prompting-red)![](https://img.shields.io/badge/Log_Parsing-brown)
11. [**ICSE 2025**] [LibreLog: Accurate and Efficient Unsupervised Log Parsing Using Open-Source Large Language Models](https://www.arxiv.org/pdf/2408.01585). ![](https://img.shields.io/badge/LiberLog-blue) ![](https://img.shields.io/badge/Prompting-red)![](https://img.shields.io/badge/Log_Parsing-brown)
12. [**FSE 2025**] [No More Labelled Examples? An Unsupervised Log Parser with LLMs](https://arxiv.org/pdf/2406.07174). ![](https://img.shields.io/badge/LUNAR-blue) ![](https://img.shields.io/badge/Prompting-red)![](https://img.shields.io/badge/LRU-red) ![](https://img.shields.io/badge/Log_Parsing-brown)

#### 2.2 Log Anomaly Detection

1. [**ICPC 2024**] [Interpretable Online Log Analysis Using Large Language Models with Prompt Strategies](https://arxiv.org/pdf/2308.07610.pdf). ![](https://img.shields.io/badge/LogPrompt-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown) ![](https://img.shields.io/badge/Log_Parsing-brown)
2. [**ISSRE 2024**] [LLMeLog: An Approach for Anomaly Detection based on LLM-enriched Log Events](https://ieeexplore.ieee.org/abstract/document/10771398). ![](https://img.shields.io/badge/LogPrompt-blue) ![](https://img.shields.io/badge/LLMeLog-red) ![](https://img.shields.io/badge/LogAD-brown) 
3. [**Preprint 2023**] [Log-based Anomaly Detection based on EVT Theory with feedback](https://arxiv.org/pdf/2306.05032.pdf). ![](https://img.shields.io/badge/ScaleAD-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown)
4. [**Preprint 2023**] [LogGPT: Exploring ChatGPT for Log-Based Anomaly Detection](https://arxiv.org/pdf/2309.01189.pdf). ![](https://img.shields.io/badge/LogGPT-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/LogAD-brown)
5. [**Preprint 2024**] [RAGLog: Log Anomaly Detection using Retrieval Augmented Generation](https://arxiv.org/pdf/2311.05261.pdf). ![](https://img.shields.io/badge/RAGLog-blue) ![](https://img.shields.io/badge/Prompting(RAG)-red) ![](https://img.shields.io/badge/LogAD-brown)
6. [**Preprint 2024**] [Anomaly Detection on Unstable Logs with GPT Models](https://arxiv.org/pdf/2406.07467).  ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/LogAD-brown)

#### 2.3 Logging Statement Generation

1. [**ICSE 2024**] [UniLog: Automatic Logging via LLM and In-Context Learning](https://www.computer.org/csdl/proceedings-article/icse/2024/021700a129/1RLIWpCelqg). ![](https://img.shields.io/badge/UniLog-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Cache-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown)
2. [**FSE 2024**] [Go Static: Contextualized Logging Statement Generation](https://arxiv.org/pdf/2402.12958.pdf). ![](https://img.shields.io/badge/SCLogger-blue) ![](https://img.shields.io/badge/Prompting(ICL)-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown)
3. [**ISSTA 2024**] [FastLog: An End-to-End Method to Efficiently Generate and Insert Logging Statements](https://arxiv.org/pdf/2311.02862). ![](https://img.shields.io/badge/FastLog-blue) ![](https://img.shields.io/badge/Finetuning-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown)
4. [**TSE 2024**] [Exploring the Effectiveness of LLMs in Automated Logging Generation: An Empirical Study](https://arxiv.org/pdf/2307.05950.pdf) [[project](https://github.com/LogStudySE/LogStudy)]. ![](https://img.shields.io/badge/LogBench-blue) ![](https://img.shields.io/badge/Prompting-red) ![](https://img.shields.io/badge/Logging_Statement_Generation-brown) ![](https://img.shields.io/badge/Analysis-green)

## 3. LLM for Infrastructure Management

#### 3.1 Benchmark

1. [**NeurIPS D&B 2024**] [IaC-Eval: A Code Generation Benchmark for Cloud Infrastructure-as-Code Programs](https://proceedings.neurips.cc/paper_files/paper/2024/file/f26b29298ae8acd94bd7e839688e329b-Paper-Datasets_and_Benchmarks_Track.pdf) ![](https://img.shields.io/badge/IaC-blue) ![](https://img.shields.io/badge/Benchmark-brown)

#### 3.2 Vision

1. [**SIGOPS 2025**] [Cloud Infrastructure Management in the Age of AI Agents](https://dl.acm.org/doi/pdf/10.1145/3759441.3759443) ![](https://img.shields.io/badge/Vision_Paper-green) ![](https://img.shields.io/badge/Agent-red) ![](https://img.shields.io/badge/System-green)

#### 3.3 Infrastructure-as-Code
 
1. [**SOSP 2024**] [Unearthing Semantic Checks for Cloud Infrastructure-as-Code Programs](https://dl.acm.org/doi/pdf/10.1145/3694715.3695974). ![](https://img.shields.io/badge/IaC-blue) ![](https://img.shields.io/badge/Reliability-red) ![](https://img.shields.io/badge/checks-green) 
2. [**AIOPS at ICSE 2025**] [Automated Bug Discovery in Cloud Infrastructure-as-Code Updates with LLM Agents](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11029328) ![](https://img.shields.io/badge/Agent-red) ![](https://img.shields.io/badge/IaC-blue) ![](https://img.shields.io/badge/Reliability-red)
3. [**AIOPS at ICSE 2025**] [Automated Lifting for Cloud Infrastructure-as-Code Programs](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11029329) ![](https://img.shields.io/badge/Agent-red) ![](https://img.shields.io/badge/IaC-blue) ![](https://img.shields.io/badge/Lifting-brown)


## Contribution

### Contributing to this paper list

- First, think about which category the work should belong to.
- Second, use the same format as the others to discribe the work. Note that there should be an empty line between the title and the authors list, and take care of the indentation.
- Then, add [keywords tags](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps/blob/main/README.md#keywords-convention). Add the pdf link of the paper. If it is an arxiv publication, we prefer /abs/ format to /pdf/ format.

**Don't worry if you put all these wrong, we will fix them for you.** Just contribute and promote your awesome work here!

If you recommended a work that wasn't yours, you will be added to the contributor list (be sure to provide your information in [other contributors](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps/blob/main/README.md#other-contributors)).

