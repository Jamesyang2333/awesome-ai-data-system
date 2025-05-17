# Awesome AI-powered data processing systems  ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)
What are AI-powered data processing systems, how are they different from other systems that marry data & AI, e.g., vector databases? AI-powered data processing systems incorporate AI/LLM capabilites into the query processing flow of a data management system to enable operations and queries not possible on existing systems. For example, you can leverate AI to find relevant precedents from legal case summaries, classify the taffic accident reports by the causes, or summarize the competitive landscape of a market from financial reports, in a performance & cost efficient manner using a highly optimized query processing framework similar to those in relational databases. Similarity search (for RAG), the key operator enabled by vector databases, is only one of the many AI-powered operators in AI-powered data processing systems, which support far more complicated query processing flows beyond RAG. AI-powered data processing systems opens the gate for innovations on new data processing operators, new query optimization strategies and new ways of user-system interaction. In this repository, we maintain:

**A curated list of resources on AI-powered data processing systems**
- [0. VISIONS](#visions)
- [1. SYSTEMS](#systems)
- [2. OPERATORS](#operators)

## VISIONS
**Databases Unbound: Querying All of the World’s Bytes with AI**  
S Madden, M Cafarella, M Franklin, T Kraska. _VLDB 2024_ [[PDF](https://dl.acm.org/doi/abs/10.14778/3685800.3685916)]

**How Large Language Models Will Disrupt Data Management**  
RC Fernandez, AJ Elmore, MJ Franklin, S Krishnan, C Tan. _VLDB 2023_ [[PDF](https://www.vldb.org/pvldb/vol16/p3302-fernandez.pdf)]

## SYSTEMS
**The Design of an LLM-powered Unstructured Analytics System (Aryn)**  
E Anderson, J Fritz, A Lee, B Li, M Lindblad, H Lindeman, A Meyer, P Parmar, et al. [[PDF](https://arxiv.org/pdf/2409.00847)] [[CODE](https://github.com/aryn-ai/sycamore)]

**DocETL: Agentic Query Rewriting and Evaluation for Complex Document Processing**  
S Shankar, T Chambers, T Shah, AG Parameswaran, E Wu. [[PDF](https://arxiv.org/abs/2410.12189)] [[CODE](https://github.com/ucbepic/docetl)]

**Semantic Operators: A Declarative Model for Rich, AI-based Data Processing (LOTUS)**  
L Patel, S Jha, M Pan, H Gupta, P Asawa, C Guestrin†, M Zaharia. [[PDF](https://arxiv.org/abs/2407.11418)] [[CODE](https://github.com/lotus-data/lotus)]

**A DECLARATIVE SYSTEM FOR OPTIMIZING AI WORKLOADS (PALIMPZEST)**  
C Liu, M Russo, M Cafarella, L Cao, PB Chen, Z Chen, M Franklin, T Kraska, S Madden, G Vitagliano. _CIDR 2025_ [[PDF](https://arxiv.org/pdf/2405.14696)] [[CODE](https://github.com/mitdbg/palimpzest)]

**CAESURA: Language Models as Multi-Modal Query Planners**  
M Urban, C Binnig. _CIDR 2024_ [[PDF](https://www.cidrdb.org/cidr2024/papers/p14-urban.pdf)]

**Towards Accurate and Efficient Document Analytics with Large Language Models (ZenDB)**  
Y Lin, M Hulsebos, R Ma, S Shankar, S Zeigham, AG Parameswaran, E Wu. [[PDF](https://arxiv.org/abs/2405.04674)]

## OPERATORS
### Map / Extract
**Language Models Enable Simple Systems for Generating Structured Views of Heterogeneous Data Lakes (EVAPORATE)**  
S Arora, B Yang, S Eyuboglu, A Narayan, A Hojel, I Trummer, C Ré. _VLDB 2023_ [[PDF](https://www.vldb.org/pvldb/vol17/p92-arora.pdf)]

