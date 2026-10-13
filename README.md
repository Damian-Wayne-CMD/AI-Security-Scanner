# AI-Powered Python Security Scanner

AI-assisted security analysis for Python code, designed to help teams identify vulnerabilities, assess potential impact, and prioritize remediation.
---

## Project Overview

The AI-Powered Python Security Scanner is a command-line application that uses Google's Gemini AI to analyze Python source code for potential security vulnerabilities. It generates structured security insights, including threat-level rankings, vulnerability descriptions, potential impact assessments, and recommended fixes.

The goal is to make security findings easier to understand and act on by translating code-level risks into actionable information that supports developers and security teams.

This project represents my hands-on exploration of Python development, AI integration, application security, and configurable language model architectures.
---

## Why I Built This

Security vulnerabilities are not always easy to identify, interpret, or prioritize, particularly when teams need to balance technical risk against competing business priorities.

I built this tool to explore how AI can help bridge that gap by turning potential security issues into clear, contextual findings that support informed remediation decisions.

With over 10 years of business experience and a self-taught background in coding, I approach development with a focus on more than just making software work. I also consider usability, prioritization, operational efficiency, and how technical solutions can address practical problems.

## Key Features
- AI-Powered Code Analysis: Uses Google's Gemini models to examine Python source code for potential security issues.
- Threat-Level Prioritization: Ranks identified issues by their assessed level of risk to help guide remediation efforts.
- Vulnerability Classification: Identifies the type of security issue detected.
- Contextual Explanations: Describes the issue in understandable terms, including why it matters.
- Potential Impact Assessment: Explains the possible consequences of an identified vulnerability.
- Recommended Remediation: Provides suggested fixes to help developers address security concerns.
- Command-Line Workflow: Enables security analysis directly from the terminal.
- Model Flexibility: Designed to accommodate different AI models as the project evolves.

## How It Works
- Analyze: Provide Python source code for security analysis through the command-line workflow.
- Identify: Use the configured AI model to examine the code for potential vulnerabilities.
- Classify: Determine the type of security issue identified.
- Prioritize: Assign a threat level to help communicate relative risk.
- Explain: Generate a description of the issue and its potential impact.
- Remediate: Provide suggested fixes to help address the identified risk.

> The result is an AI-assisted workflow intended to make security findings more accessible, understandable, and actionable.


The project is developed using Visual Studio Code and Python's virtual environment tooling.

The local setup uses a .venv environment to isolate project dependencies and a .env file for API configuration, alongside the GOOGLE_API_KEY configuration in scanner.py as required by the current implementation.

See the setup instructions below to configure and run the project locally.