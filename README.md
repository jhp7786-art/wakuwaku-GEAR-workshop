# WakuWaku - Custom AI Companion

## Project Overview
This project was built upon the foundation of the Google Developers "AI Companion" workshop to explore the Antigravity CLI and Agent Development Kit (ADK). It features Waku, a witty, highly-intelligent AI companion.

## Custom Architecture & Engineering
To maintain a strict zero-cost perimeter and adapt the framework to specific operational constraints, I engineered several custom modifications to the original framework:

* **Bypassed Paid Infrastructure:** Refactored the core agent capabilities to bypass the paid Gemini Google Search Grounding requirement.
* **Custom Tool Integration:** Engineered a custom Python tool utilizing the `duckduckgo-search` library, providing the agent with free, real-time web access.
* **Credential Management:** Implemented strict `.gitignore` vaults and environment variable management to secure all API credentials prior to repository deployment.

## Acknowledgements
Foundational architecture based on the Google AI Companion Codelab.
