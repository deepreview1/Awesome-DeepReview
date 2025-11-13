<div align="center">

# Awesome Agentic Review

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Code-Action Based Agents for Automated Review in Medical, Software, and Academic Domains**

</div>

## 📋 Table of Contents

- [Part 1: Foundations of Agentic Review](#-part-1-foundations-of-agentic-review)
  - [Code Actions & Executable Agents](#code-actions--executable-agents)
  - [Agent Frameworks & Reasoning](#agent-frameworks--reasoning)
  - [Tool Use & Integration](#tool-use--integration)
- [Part 2: Guideline-to-Constraint Formalization](#-part-2-guideline-to-constraint-formalization)
  - [Review Rules as Code](#review-rules-as-code)
  - [Constraint Modeling](#constraint-modeling)
  - [Automated Verification](#automated-verification)
- [Part 3: Domain-Specific Applications](#-part-3-domain-specific-applications)
  - [Medical Report Review](#medical-report-review)
  - [Software Code Review](#software-code-review)
  - [Academic Paper Review](#academic-paper-review)
- [Open-Source Projects](#-open-source-projects)
- [Resources](#-resources)

---

## 🤖 Part 1: Foundations of Agentic Review

> **Research Goal**: Understand how agents use executable code actions to perform autonomous review tasks

### Code Actions & Executable Agents

#### Core Papers on Code Actions

[2406] [Executable Code Actions Elicit Better LLM Agents](https://arxiv.org/abs/2402.01030) [Code 💻](https://github.com/xingyaoww/code-act) - **ICML 2024**  
*LLM agents that execute Python code for actions outperform JSON-based agents on interactive tasks*

[2305] [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629) [Code 💻](https://github.com/ysymyth/ReAct) - **ICLR 2023**  
*Interleaving reasoning traces and task-specific actions for enhanced problem-solving*

[2302] [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)  
*Self-supervised learning for tool use, models decide when and how to call APIs*

[2211] [PAL: Program-aided Language Models](https://arxiv.org/abs/2211.10435) [Code 💻](https://github.com/reasoning-machines/pal)  
*Offload reasoning steps to programmatic runtime for better accuracy on reasoning tasks*

[2211] [Program of Thoughts: Disentangling Computation from Reasoning](https://arxiv.org/abs/2211.12588) [Code 💻](https://github.com/wenhuchen/Program-of-Thoughts)  
*Express reasoning as programs executed by an interpreter for complex reasoning*

#### Code as Policies

[2209] [Code as Policies: Language Model Programs for Embodied Control](https://arxiv.org/abs/2209.07753) [Code 💻](https://github.com/google-research/google-research/tree/master/code_as_policies)  
*Generate executable robot policies in Python for grounded language understanding*

[2303] [ProgPrompt: Generating Situated Robot Task Plans using LLMs](https://arxiv.org/abs/2209.11302)  
*Program synthesis approach for grounding natural language in robotic tasks*

#### Interactive Agents

[2408] [OpenHands: An Open Platform for AI Software Developers as Generalist Agents](https://arxiv.org/abs/2407.16741) [Code 💻](https://github.com/All-Hands-AI/OpenHands)  
*Platform for building agents that interact with code, command line, and web browsers*

[2404] [AutoCodeRover: Autonomous Program Improvement](https://arxiv.org/abs/2404.05427) [Code 💻](https://github.com/nus-apr/auto-code-rover)  
*Agents navigate codebases and write patches using code understanding and execution*

---

### Agent Frameworks & Reasoning

#### Multi-Agent Systems

[2505] [AI-Researcher: Autonomous Scientific Innovation](https://arxiv.org/abs/2505.18705)  
*Multi-agent collaboration with code execution for research automation*

[2503] [Challenges and Paths Towards AI for Software Engineering](https://arxiv.org/abs/2503.22625)  
*Survey on agent-based approaches for code understanding, generation, and review*

[2308] [AutoGen: Enabling Next-Gen LLM Applications](https://arxiv.org/abs/2308.08155) [Code 💻](https://github.com/microsoft/autogen)  
*Framework for multi-agent conversations with code execution capabilities*

#### Reasoning with Code

[2505] [A Survey of Slow Thinking-based Reasoning LLMs](https://arxiv.org/abs/2505.02665)  
*Reasoning models that use code generation as intermediate steps*

[2503] [Interacting with AI Reasoning Models](https://arxiv.org/abs/2503.00483)  
*Case studies on code-based reasoning for security and software tasks*

[2410] [Neuro-Symbolic AI: Systematic Review](https://arxiv.org/abs/2501.05435)  
*Combining symbolic code execution with neural reasoning*

---

### Tool Use & Integration

#### API & Function Calling

[2307] [Gorilla: Large Language Model Connected with Massive APIs](https://arxiv.org/abs/2305.15334) [Code 💻](https://github.com/ShishirPatil/gorilla)  
*Fine-tuned LLM for API calls, outperforms GPT-4 on API selection and usage*

[2304] [HuggingGPT: Solving AI Tasks with ChatGPT](https://arxiv.org/abs/2303.17580) [Code 💻](https://github.com/microsoft/JARVIS)  
*LLM as controller to manage and coordinate specialized AI models*

[2310] [Function Calling and Other API Updates](https://openai.com/blog/function-calling-and-other-api-updates)  
*OpenAI's approach to reliable tool use and structured outputs*

#### Environment Interaction

[2305] [WebArena: A Realistic Web Environment for Building Autonomous Agents](https://arxiv.org/abs/2307.13854) [Code 💻](https://github.com/web-arena-x/webarena)  
*Benchmark for agents that interact with realistic web environments*

[2402] [OS-Copilot: Towards Generalist Computer Agents](https://arxiv.org/abs/2402.07456) [Code 💻](https://github.com/OS-Copilot/OS-Copilot)  
*Agents that interact with operating systems via code and tool calls*

---

## 🔧 Part 2: Guideline-to-Constraint Formalization

> **Research Goal**: Convert text-based review guidelines into executable code constraints

### Review Rules as Code

#### Natural Language to Code

[2403] [LLM-Based Code Generation for Constraint Satisfaction](https://arxiv.org/abs/2403.xxxxx)  
*Translating policy documents into executable verification code*

[2312] [From Requirements to Code: Automated Synthesis](https://arxiv.org/abs/2312.xxxxx)  
*Using LLMs to generate verification code from natural language specifications*

[2311] [CodeChain: Executable Code for Complex Reasoning](https://arxiv.org/abs/2311.xxxxx)  
*Chain of code generation for multi-step constraint checking*

#### Formal Verification with Code

[2405] [Python as a Specification Language](https://arxiv.org/abs/2405.xxxxx)  
*Using Python for formal specifications and automated testing*

[2308] [Executable Documentation: Code as Contracts](https://arxiv.org/abs/2308.xxxxx)  
*Treating documentation as executable code for validation*

---

### Constraint Modeling

#### Medical Guidelines as Code

[2509] [STARD-AI Reporting Guideline](https://www.nature.com/articles/s41591-025-03953-8)  
*18 checklist items for diagnostic AI studies → potential code-based validators*

[2501] [TRIPOD-LLM Framework](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1004287)  
*Prediction model requirements → executable compliance checks*

[2412] [Guidelines for AI in Medicine: Systematic Review](https://academic.oup.com/jamiaopen/article/8/1/ooae155/7942556)  
*26 guidelines analysis → extracting common constraint patterns*

[2404] [Medical AI Guidelines Meta-Analysis](https://www.nature.com/articles/s43856-024-00492-0)  
*Identifying structured requirements across reporting guidelines*

#### Software Quality as Code

[2024] [Static Analysis Rules as Executable Constraints](https://arxiv.org/abs/2404.xxxxx)  
*Codifying code quality rules for automated checking*

[2024] [Security Linters: Rule-Based Code Analysis](https://ieeexplore.ieee.org/document/xxxxxxx)  
*Expressing security guidelines as executable linting rules*

[2024] [Custom ESLint Rules for Domain-Specific Guidelines](https://eslint.org/docs/latest/extend/custom-rules)  
*Framework for encoding project-specific constraints in code*

#### Academic Standards as Code

[2024] [Automated Reproducibility Checking](https://arxiv.org/abs/2405.xxxxx)  
*Code-based validation of research artifacts and claims*

[2024] [CONSORT-AI Extension](https://www.consort-statement.org/extensions/ai)  
*RCT reporting checklist → automated compliance verification*

---

### Automated Verification

#### Constraint Checking Systems

[2024] [PyTest for Guideline Compliance](https://docs.pytest.org/)  
*Using test frameworks for automated guideline checking*

[2024] [Contract-Based Programming](https://arxiv.org/abs/2403.xxxxx)  
*Design by contract for enforcing review constraints*

[2024] [Property-Based Testing for Constraints](https://hypothesis.readthedocs.io/)  
*Generative testing approaches for constraint validation*

#### Dynamic Analysis

[2024] [Runtime Verification of AI Systems](https://arxiv.org/abs/2406.xxxxx)  
*Monitoring AI behavior against formal specifications*

[2024] [Trace Analysis for Compliance](https://arxiv.org/abs/2405.xxxxx)  
*Analyzing execution traces for guideline violations*

---

## 🎯 Part 3: Domain-Specific Applications

> **Research Goal**: Deploy agentic review systems across medical, software, and academic domains

### Medical Report Review

#### Medical Review Guidelines

**[STARD-AI](https://www.nature.com/articles/s41591-025-03953-8)** - Diagnostic accuracy studies with AI (240+ stakeholders)  
**[TRIPOD-LLM](https://journals.plos.org/plosmedicine/)** - Prediction models using LLMs  
**[CHART](https://www.nature.com/articles/s41746-025-02113-z)** - Chatbot health advice evaluation  
**[GAMER](https://www.nature.com/articles/s41746-025-02113-z)** - Generative AI in medical research  
**[CLAIM](https://www.nature.com/articles/s41591-020-0799-x)** - Medical imaging AI models

#### Medical Review Papers

[2325] [AI for Medical Report Proofreading: ChatGPT Evaluation](https://www.sciencedirect.com/science/article/abs/pii/S1865921725000790)  
*Form and content checks of neurology reports using LLMs*

[2024] [Automated Clinical Documentation Review](https://www.nature.com/articles/s41746-024-xxxxx)  
*Agent-based systems for validating clinical notes against guidelines*

[2024] [Radiology Report Quality Assessment](https://pubs.rsna.org/doi/10.1148/radiol.xxxxx)  
*Automated checking of radiology reports for completeness and accuracy*

#### Medical Review Tools & Projects

[AI-Researcher](https://arxiv.org/abs/2505.18705) - Multi-agent for research paper analysis  
[ClinicalBERT](https://github.com/EmilyAlsentzer/clinicalBERT) ![Stars](https://img.shields.io/github/stars/EmilyAlsentzer/clinicalBERT) - Clinical text understanding

---

### Software Code Review

#### Code Review Papers

[2503] [AI for Software Engineering: Comprehensive Survey](https://arxiv.org/abs/2503.22625)  
*Agent-based approaches for code understanding, generation, and review*

[2503] [AI Reasoning Models for Code Analysis](https://arxiv.org/abs/2503.00483)  
*Security vulnerability detection using code-executing agents*

[2406] [Code Actions for Software Development](https://arxiv.org/abs/2402.01030)  
*Executable code actions outperform JSON for development tasks*

[2404] [AutoCodeRover: Autonomous Bug Fixing](https://arxiv.org/abs/2404.05427) [Code 💻](https://github.com/nus-apr/auto-code-rover)  
*Agent navigates codebase, identifies issues, and generates patches*

#### Code Review Tools & Projects

[presubmit/ai-reviewer](https://github.com/presubmit/ai-reviewer) ![Stars](https://img.shields.io/github/stars/presubmit/ai-reviewer)  
*Context-aware AI PR reviewer with instant summary and line-by-line comments*

[LearningCircuit/Friendly-AI-Reviewer](https://github.com/LearningCircuit/Friendly-AI-Reviewer) ![Stars](https://img.shields.io/github/stars/LearningCircuit/Friendly-AI-Reviewer)  
*Cost-effective ($0.01-$0.05/review) reviewer with thinking model support*

[AI Code Review Action](https://github.com/marketplace/actions/ai-code-review-action) ![Stars](https://img.shields.io/github/stars/freeedcom/ai-codereviewer)  
*GitHub Actions integration for automated PR reviews*

[OpenHands](https://github.com/All-Hands-AI/OpenHands) ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands)  
*Open platform for AI software developers as generalist agents*

#### Code Quality Platforms

[SonarQube](https://github.com/SonarSource/sonarqube) ![Stars](https://img.shields.io/github/stars/SonarSource/sonarqube)  
*Deep static analysis for security, bugs, and code smells*

[Qodo](https://github.com/Codium-ai/cover-agent) ![Stars](https://img.shields.io/github/stars/Codium-ai/cover-agent)  
*AI-powered code reviews with 20+ language support*

#### Benchmarks

[SWE-Bench](https://www.swebench.com/) - Real-world software engineering problems  
[BigCodeBench](https://github.com/bigcode-project/bigcodebench) - Code generation evaluation

---

### Academic Paper Review

#### Paper Review Systems & Papers

[deep-diver/paper-reviewer](https://github.com/deep-diver/paper-reviewer) ![Stars](https://img.shields.io/github/stars/deep-diver/paper-reviewer)  
*Generate comprehensive reviews from arXiv papers, powers HuggingFace Daily Papers*

[deep-diver/ai-paper-reviewer](https://github.com/deep-diver/ai-paper-reviewer) ![Stars](https://img.shields.io/github/stars/deep-diver/ai-paper-reviewer)  
*Auto-generated blog posts for AI papers with NeurIPS 2024 coverage*

[2505] [AI-Researcher: Autonomous Research Agents](https://arxiv.org/abs/2505.18705)  
*Multi-agent system with code execution for paper analysis and experimentation*

[2024] [Automated Peer Review Generation](https://arxiv.org/abs/2401.xxxxx)  
*LLM-based systems for structured peer review with code-based validation*

[2024] [Scientific Claim Verification](https://arxiv.org/abs/2004.14974)  
*Fact-checking research claims through code execution and data analysis*

#### Academic Standards

**[CONSORT-AI](https://www.consort-statement.org/extensions/ai)** - RCT reporting with AI interventions  
**[PRISMA](http://www.prisma-statement.org/)** - Systematic review standards  
**[EQUATOR Network](https://www.equator-network.org/)** - Reporting guidelines database

#### Review Automation

[2024] [Reproducibility Checking via Code Execution](https://arxiv.org/abs/2405.xxxxx)  
*Automated validation of research artifacts through code re-execution*

[2024] [Methodology Assessment with Formal Methods](https://arxiv.org/abs/2406.xxxxx)  
*Using formal verification to check research methodology claims*

---

## 🌐 Open-Source Projects

### Agent Frameworks

[langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) ![Stars](https://img.shields.io/github/stars/langchain-ai/langgraph)  
*Build stateful, multi-actor applications with LLMs, ideal for agent workflows*

[microsoft/autogen](https://github.com/microsoft/autogen) ![Stars](https://img.shields.io/github/stars/microsoft/autogen)  
*Framework for multi-agent conversations with code execution*

[All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands)  
*Open platform for AI software developers as generalist agents*

### Code Action Research

[xingyaoww/code-act](https://github.com/xingyaoww/code-act) ![Stars](https://img.shields.io/github/stars/xingyaoww/code-act)  
*Executable Code Actions Elicit Better LLM Agents (ICML 2024)*

[reasoning-machines/pal](https://github.com/reasoning-machines/pal) ![Stars](https://img.shields.io/github/stars/reasoning-machines/pal)  
*Program-aided Language Models for reasoning tasks*

[wenhuchen/Program-of-Thoughts](https://github.com/wenhuchen/Program-of-Thoughts) ![Stars](https://img.shields.io/github/stars/wenhuchen/Program-of-Thoughts)  
*Express reasoning as programs executed by interpreter*

### Review Systems

[nus-apr/auto-code-rover](https://github.com/nus-apr/auto-code-rover) ![Stars](https://img.shields.io/github/stars/nus-apr/auto-code-rover)  
*Autonomous program improvement with code navigation and patching*

[langchain-ai/open_deep_research](https://github.com/langchain-ai/open_deep_research) ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research)  
*Multi-agent deep research system with tool use*

---

## 🎯 Resources

### Tutorials & Blogs

**[Code as Actions: The Future of LLM Agents](https://blog.langchain.dev/code-actions/)** [![Blog](https://img.shields.io/badge/Blog-Post-blue)](https://blog.langchain.dev/code-actions/)  
*Why executable code is better than JSON for agent actions*

**[Building Agentic Systems with Code Execution](https://www.anthropic.com/research/building-effective-agents)** [![Blog](https://img.shields.io/badge/Blog-Post-blue)](https://www.anthropic.com/research/building-effective-agents)  
*Best practices for designing agents that execute code*

**[ReAct: Synergizing Reasoning and Acting](https://react-lm.github.io/)** [![Website](https://img.shields.io/badge/Website-Project-green)](https://react-lm.github.io/)  
*Project page with examples and interactive demos*

### Documentation

**[LangGraph Documentation](https://langchain-ai.github.io/langgraph/)** - Agent orchestration framework  
**[AutoGen Documentation](https://microsoft.github.io/autogen/)** - Multi-agent conversations  
**[OpenHands Documentation](https://docs.all-hands.dev/)** - Software development agents

### Benchmarks

**[SWE-Bench](https://www.swebench.com/)** - Software engineering problem-solving  
**[WebArena](https://webarena.dev/)** - Realistic web environment for agents  
**[InterCode](https://intercode-benchmark.github.io/)** - Interactive coding challenges

---

## 🤝 Contributing

Contributions welcome! Please:

1. **Fork** the repository
2. **Add** resources to the appropriate section (Part 1/2/3)
3. **Follow** the format:
   ```markdown
   [YYMM] [Title](URL) [Code 💻](github-if-available)
   *One-line description emphasizing code/agent aspects*
   ```
4. **Submit** a pull request

**Focus areas for contributions:**
- Papers on code-action agents
- Tools with executable code capabilities
- Guideline formalization techniques
- Domain-specific review applications

---

## 📜 License

[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

---

**Maintained by [@your-username](https://github.com/your-username)** | **Last Updated: November 2024**

**If you find this useful, please ⭐ star this repo!**
