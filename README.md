# Child Safety Guardian – Online Safety Filter for Kids

This repository contains a lightweight, rule-based safety module designed to protect children in online chat interactions. It identifies risks such as:
- Self-harm ideation
- Bullying or harassment
- Grooming / stranger-danger behaviors
- Sexual or explicit content
- Personal information (PII) sharing

The system returns structured `ChildSafetyIssue` objects and uses a `ChildSafetyPolicy` to decide whether a response should be **allowed**, **warned**, **blocked**, or **escalated to an adult**. A `ChatGuardian` wrapper simulates how these checks can sit between a chat model and a child user.

This project demonstrates:
- How to operationalize child-specific safety policies
- How rule-based systems can augment AI systems
- How to design transparent, explainable safety layers for online interactions

This project demonstrates my ability to formalize risks, design evaluation cases, and build explainable safety guardrails—skills I want to deepen through scalable oversight research.
