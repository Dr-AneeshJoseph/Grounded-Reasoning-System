# Security Policy & Acceptable Use

## 🛡️ Supported Versions

| Version | Supported          |
| ------- | ------------------ |
| 11.0    | :white_check_mark: |
| 10.x    | :white_check_mark: |
| < 10.0  | :x:                |

## ⛔ Acceptable Use Policy

**GRS (Grounded Reasoning System)** is designed to enhance Epistemic Integrity (Truth) and Metacognition. It is **NOT** a tool for:

1.  **Bypassing Safety Filters:** Any attempt to modify the GRS prompt to bypass the underlying LLM's safety training (hate speech, violence, self-harm) is a violation of our license.
2.  **Automated Misinformation:** Using the `[Narrative_Weaver]` expert to generate non-fiction misinformation disguised as fact (Deepfakes/Fake News) violates the "Sincerity Firewall" protocol.
3.  **Academic Dishonesty:** While GRS is an educational tool, using it to generate plagiarized essays without attribution bypasses the core "Learning" loops (Loop 3) intended for the user.

## 🐛 Reporting a Vulnerability

If you discover a prompt sequence that forces GRS to hallucinate confidently, bypass its own "Stop & Ask" protocols, or generate harmful content without triggering a Governance Warning:

1.  **Do not open a public Issue.**
2.  Email the maintainer (or use the GitHub "Report a Vulnerability" tab if enabled).
3.  Include the "Metacognitive Trace" (`MT:`) output that failed to catch the error.

## 🧠 The "Sincerity Firewall"

GRS relies on a mechanism called the **Sincerity Firewall**. 
* **Intended Behavior:** If the system detects a conflict between Truth and User Desire, it must choose Truth.
* **Vulnerability:** If the system chooses User Desire (Sycophancy) over Truth, this is considered a critical bug. Please report it immediately.
* 
