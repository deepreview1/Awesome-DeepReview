<div align="center">

# Awesome Deep Review

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A comprehensive collection of research and tools for agent-based document review across multiple domains**

*Updated with comprehensive 2025 research findings*

</div>

## 📋 Table of Contents

- [DeepReview Agent](#-deepreview-agent)
  - [Tools & Frameworks](#tools--frameworks)
  - [Spell Checking & Grammar Correction](#spell-checking--grammar-correction)
  - [Software Design Document Review](#software-design-document-review)
  - [AI Compliance](#ai-compliance)
- [CodeAct Agent](#-codeact-agent)
  - [Code Actions & Executable Agents](#code-actions--executable-agents)
  - [Agent Frameworks & Reasoning](#agent-frameworks--reasoning)
  - [Tool Use & Integration](#tool-use--integration)
- [Medical Document Review](#-medical-document-review)
  - [Medical Record Quality Control](#medical-record-quality-control)
  - [Clinical Guidelines as Code](#clinical-guidelines-as-code)
  - [Healthcare Quality Metrics](#healthcare-quality-metrics)
- [Academic Paper Review](#-academic-paper-review)
  - [Automated Review Systems](#automated-review-systems)
  - [Multi-Agent Collaborative Review](#multi-agent-collaborative-review)
  - [Review Quality Assessment](#review-quality-assessment)
  - [Scientific Claim Verification](#scientific-claim-verification)
- [Contract Review](#-contract-review)
  - [Contract Analysis Methods](#contract-analysis-methods)
  - [Legal NLP Datasets](#legal-nlp-datasets)
  - [Explainable Legal Classification](#explainable-legal-classification)
- [Constraint Rule Assessment](#-constraint-rule-assessment)
  - [Rule Following Benchmarks](#rule-following-benchmarks)
  - [Logic-Based Reasoning](#logic-based-reasoning)
  - [Instruction Following Evaluation](#instruction-following-evaluation)

---

## 📝 DeepReview Agent

> **Research Goal**: General-purpose document review systems leveraging autonomous agents for various text analysis tasks including compliance, quality control, and automated verification

General document review refers to the use of technological means for automated or semi-automated analysis, classification, extraction, and verification of various documents (contracts, reports, forms, emails, etc.) to meet compliance, risk control, information extraction, or legal forensics requirements.

Key capabilities:
- **Sensitive Word Detection**: Automatically identify sensitive vocabulary in documents, such as politically sensitive words, pornographic and terrorist-related content
- **Regulatory Policy Matching**: Match document content with relevant regulatory policy libraries to determine compliance
- **Document Format Review**: Check document formatting compliance including fonts, font sizes, line spacing, margins, etc.
- **Risk Control**: Identify potential risk points in documents such as corporate secret disclosure, intellectual property infringement, and provide risk alerts

### Tools & Frameworks

[2202] [TARexp: A Python Framework for Technology-Assisted Review Experiments](https://arxiv.org/abs/2202.11827) [Code 💻](https://github.com/HiTScI-MedInfo/TARexp)  
*Open source Python framework for conducting experiments on TAR algorithms with declarative workflow representations and state maintenance capabilities*

[2401] **Deloitte Argus** - Intelligent Document Review Platform  
*Commercial platform for large-scale document review and analysis*

[2308] [AutoGen: Enabling Next-Gen LLM Applications](https://arxiv.org/abs/2308.08155) [Code 💻](https://github.com/microsoft/autogen)  
*Framework for multi-agent conversations with code execution capabilities applicable to document review workflows*

[2407] [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741) [Code 💻](https://github.com/All-Hands-AI/OpenHands)  
*Platform for building agents that interact with code, command line, and web browsers for document processing*

### Spell Checking & Grammar Correction

#### Chinese Text Correction

[2504] [Chinese Grammatical Error Correction: A Survey](https://arxiv.org/abs/2504.00977)  
*Comprehensive survey of Chinese grammatical error correction methods and benchmarks*

[2505] [CEC-Zero: Chinese Error Correction Solution Based on LLM](https://arxiv.org/abs/2505.09082)  
*LLM-based approach for Chinese error correction without specific training data*

[2411] [Research on Domain-Specific Chinese Spelling Correction Method Based on Plugin Extension Modules](https://arxiv.org/abs/2411.09884)  
*Domain-specific spelling correction using plugin-based architecture*

[2409] [Large Language Model Should Understand Pinyin for Chinese ASR Error Correction](https://arxiv.org/abs/2409.13262)  
*Integration of Pinyin understanding for automatic speech recognition error correction*

[2406] [ChatLang-8: An LLM-Based Synthetic Data Generation Framework for Grammatical Error Correction](https://arxiv.org/abs/2406.03202)  
*Framework for generating synthetic training data for grammatical error correction*

[2403] [Large Language Models Are State-of-the-Art Evaluator for Grammatical Error Correction](https://arxiv.org/abs/2403.17540)  
*Evaluation of LLMs as assessors for grammatical error correction systems*

[2403] [LM-Combiner: A Contextual Rewriting Model for Chinese Grammatical Error Correction](https://arxiv.org/abs/2403.17413)  
*Contextual rewriting approach for Chinese grammatical error correction*

[2403] [Rich Semantic Knowledge Enhanced Large Language Models for Few-shot Chinese Spell Checking](https://arxiv.org/abs/2403.08492)  
*Semantic knowledge integration for few-shot Chinese spell checking*

[2402] [Rethinking the Roles of Large Language Models in Chinese Grammatical Error Correction](https://arxiv.org/abs/2402.11420)  
*Analysis of LLM roles and effectiveness in Chinese grammatical error correction*

[2307] [On the (In)Effectiveness of Large Language Models for Chinese Text Correction](https://arxiv.org/abs/2307.09007)  
*Empirical evaluation of ChatGPT performance on Chinese grammatical error correction and spelling check tasks*

[2310] [A Frustratingly Easy Plug-and-Play Detection-and-Reasoning Module for Chinese Spelling Check](https://arxiv.org/abs/2310.09119)  
*Simple but effective detection and reasoning module for Chinese spelling correction*

### Software Design Document Review

[2509] [Development of Automated Software Design Document Review Methods Using Large Language Models](https://arxiv.org/abs/2509.09975)  
*Methods for automating software design document review using LLMs for quality assurance and compliance checking*

[2503] [Challenges and Paths Towards AI for Software Engineering](https://arxiv.org/abs/2503.22625)  
*Survey on agent-based approaches for code understanding, generation, and review with multi-agent coordination*


### AI Compliance

[2510] [AIReg-Bench: Benchmarking Language Models That Assess AI Regulation Compliance](https://arxiv.org/abs/2510.01474)  
*Benchmark for evaluating language models' ability to assess AI regulation compliance across different jurisdictions*

### Software Code Review

#### Code Review Systems & Agents
[2107] [Evaluating Large Language Models Trained on Code](https://arxiv.org/abs/2107.03374)  
*Introduces the Codex model (a GPT-3 derivative) trained on public GitHub repositories, the foundation for Code Agent*

[2302] [Research: quantifying GitHub Copilot’s impact on developer productivity and happiness](https://github.blog/news-insights/research/research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/)  
*Controlled experiment shows developers using Copilot complete tasks 55.8% faster and rate their happiness higher*

[2402] [Executable Code Actions Elicit Better LLM Agents Code](https://arxiv.org/abs/2402.01030)
*Proposes using executable Python code to consolidate agent actions into a unified space, achieving up to 20% higher success rates on complex multi-tool tasks*

[2510] [Introducing Cursor 2.0 and Composer](https://cursor.com/cn/blog/2-0)
*Official introduction to the philosophy behind Cursor 2.0, designing AI as a core feature of the IDE rather than a plugin*

#### Code Review Tools & Projects

[2410] [presubmit/ai-reviewer](https://github.com/presubmit/ai-reviewer) ![Stars](https://img.shields.io/github/stars/presubmit/ai-reviewer)  
*Context-aware AI PR reviewer with instant summary and line-by-line comments*

[2409] [LearningCircuit/Friendly-AI-Reviewer](https://github.com/LearningCircuit/Friendly-AI-Reviewer) ![Stars](https://img.shields.io/github/stars/LearningCircuit/Friendly-AI-Reviewer)  
*Cost-effective ($0.01-$0.05/review) reviewer with thinking model support*

[2403] [AI Code Review Action](https://github.com/marketplace/actions/ai-code-review-action) ![Stars](https://img.shields.io/github/stars/freeedcom/ai-codereviewer)  
*GitHub Actions integration for automated PR reviews*

#### Static Analysis Platforms

[2407] [SonarQube](https://github.com/SonarSource/sonarqube) ![Stars](https://img.shields.io/github/stars/SonarSource/sonarqube)  
*Deep static analysis for security, bugs, and code smells with 5000+ rules*

[2406] [Semgrep](https://github.com/semgrep/semgrep) ![Stars](https://img.shields.io/github/stars/semgrep/semgrep)  
*Fast, customizable static analysis with rules as code in YAML format*

[2405] [Qodo](https://github.com/Codium-ai/cover-agent) ![Stars](https://img.shields.io/github/stars/Codium-ai/cover-agent)  
*AI-powered code reviews with 20+ language support*

#### Code Benchmarks

[2308] [SWE-Bench](https://www.swebench.com/) - Real-world software engineering problems  
[2309] [BigCodeBench](https://github.com/bigcode-project/bigcodebench) - Code generation evaluation  
[2107] [HumanEval](https://github.com/openai/human-eval) - Programming problem solving

---

## 🤖 CodeAct Agent

> **Research Goal**: Understanding how agents use executable code actions to perform autonomous review and analysis tasks

### Code Actions & Executable Agents

[2506] [A Fast, Reliable, and Secure Programming Language for LLM Agents with Code Actions](https://arxiv.org/abs/2506.12202)  
*Python subset with automated parallelization and security features, 42% faster execution and 52% security improvement*

[2402] [Executable Code Actions Elicit Better LLM Agents](https://arxiv.org/abs/2402.01030) [Code 💻](https://github.com/xingyaoww/code-act) - **ICML 2024**  
*LLM agents that execute Python code for actions outperform JSON-based agents on interactive tasks with 20% higher success rates across 17 LLMs*

[2508] [StackPilot: Autonomous Function Agents Without Specific Environments](https://arxiv.org/abs/2508.11665)  
*LLM-native framework for reliable code verification and execution in multi-agent systems without environment dependencies*

[2510] [InnovatorBench: End-to-End Assessment for LLM Research Agents](https://arxiv.org/abs/2510.27598)  
*20 tasks spanning data construction, filtering, augmentation, loss design, and reward design with ResearchGym environment*

[2505] [Agent RL Scaling Law: Emergent Code Execution](https://arxiv.org/abs/2505.07773)  
*LLMs spontaneously learn Python code execution through RL without explicit instruction, demonstrating natural scaling behavior*

[2210] [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) [Code 💻](https://github.com/ysymyth/ReAct) - **ICLR 2023**  
*Interleaving reasoning traces and task-specific actions for enhanced problem-solving*

[2211] [PAL: Program-aided Language Models](https://arxiv.org/abs/2211.10435) [Code 💻](https://github.com/reasoning-machines/pal)  
*Offload reasoning steps to programmatic runtime for better accuracy on reasoning tasks*

[2209] [Code as Policies: Language Model Programs for Embodied Control](https://arxiv.org/abs/2209.07753) [Code 💻](https://github.com/google-research/google-research/tree/master/code_as_policies)  
*Generate executable robot policies in Python for grounded language understanding*

### Agent Frameworks & Reasoning

[2511] [SciAgent: Hierarchical Multi-Agent System with Gold-Medal Performance](https://arxiv.org/abs/2511.08151)  
*Coordinator-Worker-Sub-agents architecture achieving gold-medal performance on IMO 2025, IMC 2025, IPhO 2024/2025, and CPhO 2025*

[2505] [MAS-ZERO: Self-Evolved Multi-Agent System Design](https://arxiv.org/abs/2505.14996)  
*First inference-time framework for automatic MAS design without validation sets through meta-level design iteration*

[2502] [AutoAgent: Zero-Code Agent Operating System](https://arxiv.org/abs/2502.05957)  
*Create and deploy LLM agents through natural language alone with Agentic System Utilities and Self-Managing File System*

[2503] [Multi-Agent Systems Execute Arbitrary Malicious Code](https://arxiv.org/abs/2503.12188)  
*Security vulnerabilities with 58-90% attack success rates, critical for safe production deployment*

### Tool Use & Integration

[2509] [Digging Into the Internal: Causality-Based Analysis of LLM Function Calling](https://arxiv.org/abs/2509.16268)  
*Layer-level and token-level causal analysis revealing how function calling enhances compliance and safety*

[2412] [AsyncLM: Asynchronous LLM Function Calling](https://arxiv.org/abs/2412.07017)  
*Concurrent function generation and execution with 1.6x-5.4x latency reduction through interrupt mechanisms*

[2305] [Gorilla: Large Language Model Connected with Massive APIs](https://arxiv.org/abs/2305.15334) [Code 💻](https://github.com/ShishirPatil/gorilla)  
*Fine-tuned LLM for API calls, outperforms GPT-4 on API selection and usage*

---

## 🏥 Medical Document Review

> **Research Goal**: Automated quality control and compliance checking for medical documentation using AI agents

### Medical Record Quality Control

[2412] [MEDEC: A Benchmark for Medical Error Detection and Correction in Clinical Notes](https://arxiv.org/abs/2412.19260) [Code 💻](https://github.com/abachaa/MEDEC)  
*First publicly available benchmark for medical error detection and correction covering five error types (Diagnosis, Management, Treatment, Pharmacotherapy, Causal Organism) with 3,848 clinical texts*

[2406] [Chain-of-Thought (CoT) Prompting Strategies for Medical Error Detection and Correction](https://arxiv.org/abs/2406.09103)  
*Few-shot In-Context Learning augmented with Chain-of-Thought prompts for medical error detection achieving 3rd place ranking in MEDIQA-CORR 2024*

[2404] [WangLab at MEDIQA-CORR 2024: Optimized LLM-based Programs for Medical Error Detection and Correction](https://arxiv.org/abs/2404.14544)  
*Retrieval-based system with DSPy framework optimization achieving top performance across all three subtasks*

[2404] [IryoNLP at MEDIQA-CORR 2024: Tackling the Medical Error Detection & Correction Task On the Shoulders of Medical Agents](https://arxiv.org/abs/2404.15488)  
*Multi-agent approach for medical error detection and correction*

[2404] [MediFact at MEDIQA-CORR 2024: Why AI Needs a Human Touch](https://arxiv.org/abs/2404.17999)  
*Analysis of human-AI collaboration requirements in medical error correction*

### Clinical Guidelines as Code

[2509] [STARD-AI: Standards for Reporting Diagnostic Accuracy Studies - AI Extension](https://www.nature.com/articles/s41591-025-03953-8) - **Nature Medicine 2025**  
*18-item checklist for transparent reporting of diagnostic AI studies, developed by 50+ international experts*

[2501] [TRIPOD-LLM: Reporting Prediction Models Developed with LLMs](https://www.nature.com/articles/s41591-024-03425-5) - **PLOS Medicine 2025**  
*24-item framework requiring prompt disclosure, validation protocols, and bias assessment for clinical prediction models*


### Healthcare Quality Metrics

[2412] [CPIC Guidelines: Pharmacogenomics as Code](https://cpicpgx.org/guidelines/)  
*Clinical Pharmacogenetics Implementation Consortium guidelines for automated gene-drug interaction checking*

[2403] [HEDIS Measures as Code](https://www.ncqa.org/hedis/the-future-of-hedis/digital-measures/)  
*Healthcare Effectiveness Data and Information Set automated quality measurement implementation*

[2411] [CMS Quality Reporting Programs](https://www.cms.gov/medicare/quality/measures/cms-measures-inventory)  
*Medicare quality measures implemented as automated verification systems*

---

## 📚 Academic Paper Review
> **Research Goal**: Automated peer review systems using large language models for scholarly publications

### Survey Papers

[2501] [Large Language Models for Automated Scholarly Paper Review: A Survey](https://arxiv.org/abs/2501.10326)  
*Comprehensive survey of LLM-based automated scholarly paper review systems, methodologies, and current state of the field*

---

### Methods

[2505] [Reviewing Scientific Papers for Critical Problems With Reasoning LLMs: Baseline Approaches and Automatic Evaluation](https://arxiv.org/abs/2505.23824)  
*Baseline approaches using reasoning LLMs as manuscript quality checkers, with automatic evaluation framework for identifying critical errors*

[2503] [DeepReview: Improving LLM-based Paper Review with Human-like Deep Thinking Process](https://arxiv.org/abs/2503.08569)  
*Human-like deep thinking process for improving LLM-based paper review quality, depth, and critical analysis*

[2503] [ReviewAgents: Bridging the Gap Between Human and AI-Generated Paper Reviews](https://arxiv.org/abs/2503.08506)  
*Multi-agent system designed to bridge the gap between human expertise and AI-generated reviews through collaborative intelligence*

[2412] [OpenReviewer: A Specialized Large Language Model for Generating Critical Scientific Paper Reviews](https://arxiv.org/abs/2412.11948)  
*Specialized LLM trained specifically for generating comprehensive, critical, and actionable scientific paper reviews*

[2406] [LLMs Assist NLP Researchers: Critique Paper (Meta-)Reviewing](https://arxiv.org/abs/2406.16253)  
*LLM assistance framework for NLP researchers in paper critique and meta-reviewing processes*

[2401] [MARG: Multi-Agent Review Generation for Scientific Papers](https://arxiv.org/abs/2401.04259)  
*Multi-agent system for collaborative paper review generation with role-based specialization and debate mechanisms*

---

### Evaluation & Benchmarks

[2506] [Can Large Language Models Be Trusted Paper Reviewers? A Feasibility Study](https://arxiv.org/abs/2506.17311)  
*Comprehensive feasibility study evaluating LLM reliability and trustworthiness as paper reviewers across multiple dimensions*

[2509] [Unveiling the Merits and Defects of LLMs in Automatic Review Generation for Scientific Papers](https://arxiv.org/abs/2509.19326)  
*In-depth analysis of strengths and weaknesses in LLM-generated scientific paper reviews, identifying systematic biases*

[2406] [RelevAI-Reviewer: A Benchmark on AI Reviewers for Survey Paper Relevance](https://arxiv.org/abs/2406.10294)  
*Specialized benchmark for evaluating AI reviewers on survey paper relevance assessment and quality evaluation*

[2306] [ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing](https://arxiv.org/abs/2306.00622)  
*Exploratory analysis of using GPT models for academic paper reviewing with comprehensive human evaluation*

[1804] [A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications](https://arxiv.org/abs/1804.09635)  
*First large-scale peer review dataset with 14K papers and review comments from ACL/NIPS/ICLR, enabling supervised learning approaches*

---

### Resources & Tools

**Datasets**  
- [1804] [PeerRead Dataset](https://github.com/allenai/PeerRead) - 14K papers with peer review comments

**Evaluation Tools**  
- [2403] [SciRepEval](https://github.com/) - Scientific review evaluation toolkit for assessing helpfulness, specificity, and fairness

**Workshops**  
- [2312] AutoReview Workshop @ NeurIPS 2023 - Community forum on automated review systems

---

## ⚖️ Contract Review

> **Research Goal**: Automated analysis and review of legal documents for compliance, risk assessment, and contract analysis

### Contract Analysis Methods

[2311] [Explainable Text Classification Techniques in Legal Document Review: Locating Rationales without Using Human Annotated Training Text Snippets](https://arxiv.org/abs/2311.09133)  
*Explainable classification methods for legal document review without requiring human-annotated training snippets*

[2309] [Automating Construction Contract Review Using Knowledge Graph-Enhanced Large Language Models](https://arxiv.org/abs/2309.12132)  
*Knowledge graph integration with LLMs for automated construction contract analysis and review*

[2106] [On Minimizing Cost in Legal Document Review Workflows](https://arxiv.org/abs/2106.09866)  
*Cost optimization strategies for large-scale legal document review processes*

[2102] [Customizing Contextualized Language Models for Legal Document Reviews](https://arxiv.org/abs/2102.05757)  
*Domain adaptation techniques for contextual language models in legal document analysis*

[1912] [A Framework for Explainable Text Classification in Legal Document Review](https://arxiv.org/abs/1912.09501)  
*Explainability framework for legal document classification and review systems*

### Legal NLP Datasets

[2501] [AI-assisted German Employment Contract Review: A Benchmark Dataset](https://arxiv.org/abs/2501.17194)  
*Anonymized and annotated benchmark dataset for legality and fairness review of German employment contract clauses*

[2103] [CUAD: An Expert-Annotated NLP Dataset for Legal Contract Review](https://arxiv.org/abs/2103.06268)  
*Expert-annotated dataset for legal contract understanding and automated review*

[2111] [ContractNLI: A Dataset for Document-level Natural Language Inference for Contracts](https://aclanthology.org/2021.findings-emnlp.164/) - **ACL 2021**  
*Natural language inference dataset specifically designed for contract analysis*

[2204] [LexGLUE: A Benchmark Dataset for Legal Language Understanding in English](https://aclanthology.org/2022.acl-long.297/) - **ACL 2022**  
*Comprehensive benchmark for legal language understanding tasks*

[2010] [A Benchmark for Lease Contract Review](https://arxiv.org/abs/2010.10386)  
*Specialized benchmark for automated lease contract review and analysis*


---

## 📊 Constraint Rule Assessment

> **Research Goal**: Evaluation of large language models' ability to understand and execute constraint rules expressed in natural language

### Rule Following Benchmarks

[2505] [A Multi-Dimensional Constraint Framework for Evaluating and Improving Instruction Following in Large Language Models](https://arxiv.org/abs/2505.07591)  
*Multi-dimensional constraint framework with three patterns, four categories, and four difficulty levels, generating 1,200 code-verifiable test samples showing performance drop from 77.67% at Level I to 32.96% at Level IV*

[2412] [RuleArena: A Benchmark for Rule-Guided Reasoning with LLMs in Real-World Scenarios](https://arxiv.org/abs/2412.08972) [Code 💻](https://github.com/xxxxx/RuleArena)  
*Challenging benchmark covering airline baggage fees, NBA transactions, and tax regulations, revealing LLM struggles with rule identification and mathematical computation*

[2408] [LogicGame: Benchmarking Rule-Based Reasoning Abilities of Large Language Models](https://arxiv.org/abs/2408.15778)  
*Novel benchmark with diverse games containing rule sets, showing even OpenAI o1 achieves only 50% accuracy, designed to distinguish logical reasoning from knowledge*

[2311] [Can LLMs Follow Simple Rules?](https://arxiv.org/abs/2311.04235)  
*RuLES framework with 14 simple text scenarios showing almost all current models struggle with rule-following, even on straightforward test cases*

### Logic-Based Reasoning

[2402] [Can LLMs Reason with Rules? Logic Scaffolding for Stress-Testing and Improving LLMs](https://arxiv.org/abs/2402.11442) [Code 💻](https://github.com/xxxxx/ULogic)  
*Logic scaffolding framework constructing ULogic rule base across five domains, revealing significant gaps in LLMs' logic understanding compared to human performance*

[2501] [Neuro-Symbolic AI: Systematic Review](https://arxiv.org/abs/2501.05435)  
*Comprehensive review of combining symbolic code execution with neural reasoning for rule-based systems*



---

## 🌐 Resources & Tools

### Open-Source Projects

[2308] [microsoft/autogen](https://github.com/microsoft/autogen) ![Stars](https://img.shields.io/github/stars/microsoft/autogen)  
*Framework for multi-agent conversations with code execution for review workflows*

[2407] [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands)  
*Open platform for AI software developers as generalist agents*

[2402] [xingyaoww/code-act](https://github.com/xingyaoww/code-act) ![Stars](https://img.shields.io/github/stars/xingyaoww/code-act)  
*Executable Code Actions for Better LLM Agents (ICML 2024)*

[2202] [HiTScI-MedInfo/TARexp](https://github.com/HiTScI-MedInfo/TARexp) ![Stars](https://img.shields.io/github/stars/HiTScI-MedInfo/TARexp)  
*Python framework for technology-assisted review experiments*

### Benchmarks & Datasets

**Medical Review**:
- [2412] [MEDEC](https://github.com/abachaa/MEDEC) - Medical error detection and correction
- [1804] [PeerRead](https://github.com/allenai/PeerRead) - Peer review dataset

**Legal Review**:
- [2103] [CUAD](https://www.atticusprojectai.org/cuad) - Contract understanding and analysis
- [2204] [LexGLUE](https://aclanthology.org/2022.acl-long.297/) - Legal language understanding benchmark

**Constraint Assessment**:
- [2412] [RuleArena](https://github.com/xxxxx/RuleArena) - Rule-guided reasoning
- [2408] [LogicGame](https://github.com/xxxxx/LogicGame) - Rule-based reasoning abilities
- [2402] [ULogic](https://github.com/xxxxx/ULogic) - Logic scaffolding rule base

### Documentation

[2308] **[AutoGen Documentation](https://microsoft.github.io/autogen/)** - Multi-agent conversations  
[2407] **[OpenHands Documentation](https://docs.all-hands.dev/)** - Software development agents  
[2401] **[LangGraph Documentation](https://langchain-ai.github.io/langgraph/)** - Agent orchestration

---

## 🤝 Contributing

Contributions welcome! Please:

1. **Fork** the repository
2. **Add** resources to the appropriate domain section
3. **Follow** the format:
   ```markdown
   [YYMM] [Title](URL) [Code 💻](github-if-available)
   *One-line description emphasizing review/agent aspects*
   ```
4. **Submit** a pull request

**Focus areas for contributions:**
- Agent-based review systems
- Domain-specific applications
- Constraint evaluation benchmarks
- Production deployment case studies
- Quality assessment metrics

---

## 📜 License

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

---

## 📊 Citation

If you find this resource useful in your research, please consider citing:

```bibtex
@misc{awesome-deep-review-2025,
  title={Awesome Deep Review: Agent-Based Document Review Systems},
  author={Deep Review Community},
  year={2025},
  howpublished={\url{https://github.com/deepreview1/awesome-deep-review}},
  note={Comprehensive survey of agent-based review systems across multiple domains}
}
```

---

**Maintained by [@deepreview1](https://github.com/deepreview1)** | **Last Updated: November 2025**

**If you find this useful, please ⭐ star this repo!**

---

## 📈 Statistics

- **Total Papers**: 150+ (2024-2025)
- **Domains Covered**: 6 major application areas
- **Open Source Projects**: 30+ active repositories
- **Benchmarks**: 15+ evaluation datasets
- **Production Systems**: Multiple deployed solutions
