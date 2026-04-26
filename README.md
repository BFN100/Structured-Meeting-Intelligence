<b>Structured Meeting Intelligence (Phase 1)</b>

<b>Project Overview</b>
This project was born from a desire to dive deep into Artificial Intelligence through hands-on execution. The inspiration came from observing a common pain point: many people use AI transcription tools but still find themselves spending significant time manually organizing data, creating reports, and assigning tasks.

I believe that repetitive, time-consuming tasks are perfect candidates for automation. To me, the ability to automate these processes is "magical", and this project serves as my playground to gain experience in prompt engineering, API integration, and AI logic.

<b>The Learning Journey (Phase 1)</b>
Instead of just building a tool, I am documenting the learning process behind instructing an AI effectively.

<u>1. From Draft to Structure</u>
Evolution: I started with a basic, raw-text prompt.

The Shift to JSON: After studying data structures and collaborating with ChatGPT and Gemini, I refactored the prompt to utilize JSON schema. This ensures the output is predictable and ready for future system integrations.

<u>2. Experimental Methodology</u>
To test the framework without using sensitive real-world data:

I designed a fictional meeting scenario and tasked ChatGPT with generating a realistic meeting transcript (simulating the Google Transcript style).

I conducted comparative tests using ChatGPT and Google Gemini across different environments: standard browser sessions and incognito tabs.

<u>3. Key Technical Insights (NotebookLM Analysis)</u>
By centralizing my data and test results in NotebookLM, I discovered a fascinating reality: even with the same prompt and model in identical environments (incognito), results vary.

<b>Probabilistic vs. Deterministic:</b> This led me to research why AI behaves this way. Since I am not yet using APIs to lock "Temperature" settings, I learned that the prompt itself must be the "anchor."

Prompt Optimization: I worked on filling "instructional gaps" to minimize unwanted variance. The goal is to create a prompt so detailed that it provides high-quality, consistent results even within a probabilistic system.

<b>Future Roadmap</b>
This project is divided into phases to ensure a solid foundation:

<b>Phase 1:</b> Research, Prompt Engineering, and Comparative Testing (Current).

<b>Phase 2:</b> Refining Logic and Integration Preparation.

<b>Phase 3:</b> Development of a standalone application (executable) to automate the entire workflow.

Note on Visibility: To protect the unique logic of this framework for the future application, the full source code and raw prompts are not public at this stage. Documentation focus remains on methodology, test reports, and architectural learnings.

---
<b>## License & Copyright</b>

Copyright (c) 2026 Bianca Fernandes Nascimento

All rights reserved. 

This project and its associated files (including prompt engineering structures, 
methodology, and analysis) are the exclusive property of Bianca Fernandes Nascimento.
No part of this repository may be reproduced, distributed, or transmitted in any form 
or by any means for commercial purposes or public redistribution without 
prior written permission.
