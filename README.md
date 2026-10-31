# ARENA AI Safety Lab

Experimental research in AI safety, AI security, predictive threat modelling, model evaluation, interpretability, and agentic AI security.

## About This Repository

This repository documents my technical AI safety learning and experimental research using the ARENA (Alignment Research Engineer Accelerator) curriculum.

My objective is not simply to complete the ARENA exercises, but to use them as a foundation for developing and testing research ideas at the intersection of:

- AI Safety
- AI Security
- Predictive Threat Modelling
- AI Evaluations
- Mechanistic Interpretability
- Agentic AI Security
- AI Governance

The central theme of this work is the application of predictive security thinking to increasingly capable and autonomous AI systems.

## Research Direction

### Predictive Threat Modelling for AI Systems

Traditional cybersecurity threat modelling seeks to identify threats, attack surfaces, vulnerabilities, and potential failure conditions before they result in successful attacks.

My research explores a related question for advanced AI systems:

> **Can observable characteristics of an AI system, its environment, internal representations, tool interactions, or behaviour be used to predict elevated risk of unsafe or insecure actions before those actions occur?**

This repository will progressively investigate that question through increasingly sophisticated experiments.

## Research Questions

The work in this repository will explore questions such as:

1. Can model confidence or uncertainty predict model failure?

2. How does distribution shift affect the reliability of simple AI risk indicators?

3. Can adversarial inputs produce detectable signals before model failure occurs?

4. Can internal transformer activations provide early indicators of anomalous or unsafe behaviour?

5. Can AI evaluation results be transformed into predictive threat features?

6. Can behavioural and environmental signals predict unsafe actions by autonomous AI agents?

7. How should conventional cybersecurity threat-modelling methodologies evolve for agentic AI systems?

## Experimental Roadmap

The research will progress incrementally.

### Experiment 001
**Model Confidence as a Predictor of Failure**

Investigate whether model confidence and uncertainty signals can predict classification errors.

### Experiment 002
**Risk Prediction Under Perturbation**

Test whether predictive risk indicators remain useful under corrupted, shifted, or adversarial inputs.

### Experiment 003
**Transformer Activation Anomaly Detection**

Investigate whether internal transformer representations provide useful signals for identifying anomalous behaviour.

### Experiment 004
**LLM Behavioural Risk Evaluation**

Design systematic evaluations for model behaviours relevant to AI safety and security.

### Experiment 005
**Agentic AI Threat Prediction**

Investigate whether observable agent, environment, tool-use, and behavioural signals can predict elevated risk of unsafe actions.

These experiment definitions may evolve as empirical results generate new hypotheses.

## ARENA Learning Track

The experiments will develop alongside my study of the ARENA curriculum.

### Fundamentals

Focus areas include:

- PyTorch
- tensor operations
- neural network implementation
- optimisation
- backpropagation
- experimental ML workflows

### Transformer Interpretability

Focus areas will include:

- transformer architecture
- internal activations
- activation analysis
- model representations
- mechanistic interpretability

### Reinforcement Learning

This stage will provide foundations for reasoning about:

- sequential decision making
- agents
- environments
- rewards
- learned policies

### LLM Evaluations

Evaluation techniques will be used to investigate measurable indicators of model and agent behaviour.

### Alignment Science

Alignment research will provide the broader safety context for investigating model behaviour, misalignment, and emerging risks.

## From Cyber Threat Modelling to AI Threat Prediction

The long-term research programme can be represented as:

Traditional Cybersecurity Threat Modelling

↓

AI System Threat Modelling

↓

Behavioural and Internal Risk Signals

↓

AI Safety Evaluations

↓

Predictive Risk Models

↓

Agentic AI Threat Modelling

↓

Prediction of Unsafe Agent Behaviour

The objective is to move beyond identifying what *could* go wrong toward experimentally investigating whether we can estimate **when the probability of failure or unsafe behaviour is increasing**.

## Research Method

Where appropriate, experiments will follow a reproducible research structure:

1. Research question
2. Threat hypothesis
3. Experimental design
4. Baseline
5. Implementation
6. Measurement
7. Results
8. Analysis
9. Security interpretation
10. Limitations
11. Follow-up hypothesis

Failed hypotheses and negative results will also be documented where they provide useful research information.

## Reproducibility

Experiments should progressively include:

- documented dependencies
- reproducible code
- explicit experimental assumptions
- fixed random seeds where appropriate
- clearly defined metrics
- saved experimental results
- limitations
- follow-up research questions

As the repository develops, reusable research components will be separated from experiment-specific code.

## Repository Structure

The repository will progressively develop toward:

    arena-ai-safety-lab/
    │
    ├── README.md
    ├── LICENSE
    ├── requirements.txt
    │
    ├── experiments/
    │   ├── 001-confidence-risk/
    │   ├── 002-perturbation-risk/
    │   ├── 003-activation-anomaly/
    │   ├── 004-llm-evaluations/
    │   └── 005-agentic-threat-prediction/
    │
    ├── notebooks/
    ├── src/
    ├── results/
    │
    └── research-notes/
        └── arena-learning-log.md

Directories will be introduced as the corresponding experiments begin rather than populated with placeholder work.

## Long-Term Research Goal

The longer-term objective is to investigate:

> **Predictive Threat Modelling for Agentic AI Systems**

The research hypothesis motivating this direction is that observable signals from an AI agent, its environment, internal state, interaction history, permissions, tool use, and behaviour may contain information useful for estimating the probability of future unsafe actions.

This extends ideas from predictive cybersecurity threat modelling into the emerging security challenges created by autonomous and agentic AI.

## Background

I am a technology architect and researcher with more than two decades of experience spanning enterprise architecture, cybersecurity, digital platforms, and large-scale technology transformation.

I hold a **PhD in Computer Science**, with research focused on **Cybersecurity and Predictive Threat Modelling**.

My additional academic development includes:

- **University of Oxford** – Strategy and Innovation
- **London School of Economics and Political Science (LSE)** – AI: Law, Policy and Governance
- **Deakin University, Australia** – M.Sc. Data Science 


My current research interests combine technical AI safety with my existing work in cybersecurity, predictive threat modelling, architecture, and AI governance.

## Research Interests

`AI Safety`  
`AI Security`  
`Predictive Threat Modelling`  
`Agentic AI Security`  
`LLM Evaluations`  
`Mechanistic Interpretability`  
`AI Governance`

## Current Status

**Phase 1: ARENA Fundamentals + Experimental Foundations**

Current objective:

> Build the technical and experimental foundations required to investigate predictive threat modelling for advanced AI systems.

The first experiment will investigate whether simple model confidence signals can predict model failure.

## Author

**Dauda Olalere, PhD**

AI Safety | AI Security | Predictive Threat Modelling | Agentic AI | AI Governance

---

*This repository is a developing research portfolio. Experimental conclusions should be interpreted in the context of the methodology, assumptions, and limitations documented for each experiment.*
