# AI-Agents-for-Medical-Diagnostics
Python project building specialized LLM-based AI agents to analyze complex medical cases. Each agent represents a medical specialty, contributing independent insights that are synthesized into comprehensive assessments and personalized treatment recommendations, demonstrating AI’s potential for multidisciplinary clinical decision support.
How It Works

This project uses three specialized LLM-based AI agents (GPT-5), each focused on a different aspect of medical analysis.

A medical report is provided as input and processed concurrently by all agents using parallel execution. Each agent independently analyzes the report and returns its findings. The system then aggregates these outputs and produces a summarized assessment highlighting three potential health issues with supporting reasoning.

AI Agents
Cardiologist Agent

Focus: Detection of cardiac conditions (e.g., arrhythmias, structural abnormalities)

Outputs: Cardiovascular risk assessment and diagnostic or management recommendations

Psychologist Agent

Focus: Identification of psychological conditions (e.g., anxiety, panic disorders)

Outputs: Mental health insights and therapy or medication considerations

Pulmonologist Agent

Focus: Evaluation of respiratory causes (e.g., asthma, breathing disorders)

Outputs: Pulmonary assessments and recommended respiratory tests or treatments
