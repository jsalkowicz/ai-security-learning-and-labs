# Anthropic AI Fluency: Framework & Foundations

**Status:** Complete  
**Platform:** Anthropic / Claude Academy  
**Course:** AI Fluency: Framework & Foundations  
**Completed:** November 2, 2026  
**Assessment:** 10/10 correct (100%)  
**Type:** Guided training / learning checkpoint

## Overview

I completed Anthropic's **AI Fluency: Framework & Foundations** course as part of my AI security engineering and analysis learning track.

This was guided training rather than an original software project. I am including it in GitHub to document the AI foundation I am building before moving into more technical AI security work.

The course focused on Anthropic's **4D AI Fluency Framework**:

- **Delegation**
- **Description**
- **Discernment**
- **Diligence**

The framework is designed around working with AI in ways that are effective, efficient, ethical, and safe.

## The 4D Framework

### Delegation

Delegation is about deciding what work should be done by a human, what work should be done by AI, when AI should be involved, and how responsibility should be divided.

From a security perspective, this connects to deciding when an AI system should be allowed to act autonomously and when human approval should be required.

### Description

Description is about clearly communicating goals, requirements, context, and desired behavior to an AI system.

The course also included effective prompting techniques.

For AI security, this is relevant because instructions and context are part of the attack surface. Prompt injection, instruction manipulation, and malicious context can influence model behavior.

### Discernment

Discernment is the process of critically evaluating AI outputs and behavior.

This includes deciding whether an output is accurate, relevant, appropriate, useful, and safe to rely on.

This is directly relevant to AI security because model output should not automatically be trusted simply because it was generated successfully.

### The Description-Discernment Loop

One concept I practiced was the relationship between giving better instructions and evaluating the result.

I understand this as an iterative cycle:

```text
Describe the task
      ↓
AI produces output
      ↓
Evaluate the output
      ↓
Improve instructions or context
      ↓
Try again
```

### Diligence

Diligence focuses on responsible use of AI and accountability for AI-assisted work.

This includes being thoughtful about how AI is used, what systems or data are involved, transparency about AI involvement, reviewing outputs before using or sharing them, and taking responsibility for the result.

For AI security, diligence connects strongly to governance, human oversight, risk management, and secure deployment practices.

## Human-AI Interaction Modes

The AI Fluency framework also distinguishes different ways humans can work with AI:

### Automation

AI performs a specific task based on human instructions.

### Augmentation

The human and AI work together as thinking partners.

### Agency

AI is configured to act more independently on behalf of the human.

The concept of agency is especially important to my AI security track because increased AI autonomy creates additional security concerns around permissions, tool access, identity, least privilege, approval gates, unintended actions, and excessive agency.

## What I Learned

This course helped me understand that AI fluency is more than writing prompts.

The larger process includes:

1. deciding whether AI should be involved
2. clearly describing the goal and expectations
3. evaluating the AI's output instead of automatically trusting it
4. taking responsibility for how AI is used and what happens with the result

That sequence has a strong connection to security engineering because secure AI systems require decisions about autonomy, instructions, trust, validation, accountability, and human oversight.

## Security Relevance

| AI Fluency Concept | AI Security Connection |
| --- | --- |
| Delegation | Human approval, autonomy, excessive agency, least privilege |
| Description | Prompt injection, system instructions, context manipulation |
| Discernment | Output validation, hallucination risk, unsafe model behavior |
| Diligence | Governance, accountability, responsible deployment, risk management |
| Agency | Agent permissions, tool security, identity, MCP security |

## Assessment

I completed the course assessment with:

```text
10 of 10 correct
100%
```

## Evidence

Completion evidence is stored in:

`evidence/anthropic-ai-fluency-assessment-100-percent.png`

The screenshot shows the Anthropic course assessment marked **passed** with a score of **10/10 (100%)**.

## Next Step

My next planned course is:

**Anthropic AI Capabilities and Limitations**

That course will add more focus on what AI systems can and cannot reliably do before I move into additional AI and security-specific material.
