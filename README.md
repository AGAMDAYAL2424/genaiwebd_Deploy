\# RAD AI - GenAI Exchange Hackathon Prototype Submission



\## Team: RAD AI



Welcome, esteemed judges, to our submission for the GenAI Exchange Hackathon. This document provides a comprehensive overview of our project, \*\*RAD AI\*\*, a solution designed to demystify complex legal documents for everyone using Google's powerful Generative AI technology.



---



\## 1. The Problem We Are Solving



Navigating legal documents like rental agreements, freelance contracts, or terms of service is a daunting task for the average person. The language is often dense, filled with jargon, and carries hidden risks and obligations that are easy to miss. This "information asymmetry" can lead to significant legal and financial consequences.



\*\*RAD AI directly tackles this problem by transforming convoluted legal text into simple, understandable, and actionable insights.\*\*



---



\## 2. Our Solution: An Overview



RAD AI is a web-based platform that acts as a personal AI legal assistant. Users can simply paste the content of a legal document into our application, and our system, powered by Google's Gemini models, provides a comprehensive analysis in seconds.



Our core mission is to empower users to make informed decisions by highlighting potential risks, explaining complex clauses in plain language, and summarizing key obligations.



---



\## 3. What We Have Implemented (The Prototype)



For this hackathon, we have built a functional prototype that demonstrates the core user experience and our primary analysis features. The prototype you are viewing is a single, self-contained HTML file that communicates with a backend AI service.



\### Implemented Features:



\*\*Innovative "Fairness Meter":\*\* This is our flagship innovative feature. The system will compare key clauses from the user's document (e.g., a rental agreement) against a database of standard, fair-practice clauses. A simple visual meter will instantly show the user how their document stacks up, flagging clauses that are unusually harsh or one-sided.

\*   \*\*Direct Redlining and Annotation:\*\* Allow users to select specific sentences or paragraphs and ask questions directly about that highlighted section, providing a more granular and interactive analysis experience.

\*   \*\*Multi-Lingual Support:\*\* Integrate Google's translation APIs to allow users to analyze documents and receive explanations in multiple languages, dramatically increasing accessibility.



\*   \*\*Document Ingestion \& Analysis:\*\* Users can paste legal text into the application. Clicking "Analyze" sends the text to our AI backend for processing.

\*   \*\*Split-Screen UI:\*\* A clean, intuitive interface that displays the original document on the left and the AI-generated analysis on the right, allowing for easy comparison.

\*   \*\*Core Analysis Panel:\*\* The right-hand panel displays a clear, concise breakdown of the document, including a high-level summary and a list of automatically detected risks.

\*   \*\*Interactive Clause Highlighting:\*\* The prototype identifies and visually highlights potentially risky or important clauses directly within the document text on the left.

\*   \*\*AI-Powered Chat Module:\*\* A fully functional chat interface where users can ask specific questions about the document and receive conversational answers from our Gemini-powered backend.



\### Technology Stack Used in the Prototype:



\*   \*\*Frontend:\*\* Vanilla JavaScript (ES6+), HTML5, CSS3, and the pdf.js library. We chose a framework-less approach to create a lightweight, fast, and dependency-free user experience.

\*   \*\*Backend \& AI:\*\* Google's \*\*Gemini Pro model\*\* accessed via its API. The backend logic processes the text and generates all summaries, risk analyses, and chat responses.



---



\## 4. What We Are Yet to Implement (Our Roadmap)



This prototype serves as a strong foundation. Given more time, we plan to build out a full-fledged, production-ready platform with the following key features outlined in our presentation:



\### High-Priority Features for Future Implementation:



\*   \*\*Action Planner:\*\* Automatically identify and extract all user obligations, deadlines, and key dates from the document and present them as a clear, actionable checklist or timeline.

\*   \*\*Secure User Accounts \& Document Storage:\*\* Implement a secure authentication system (e.g., Google OAuth) and an encrypted database (PostgreSQL) to allow users to save, manage, and track their analyzed documents over time.

\*   \*\*Advanced Risk Control ("Temperature Setting"):\*\* Introduce a user-facing setting to control the AI's "creativity vs. factual accuracy" (temperature). A lower setting would ensure the AI provides only conservative, fact-based legal information, while a higher setting could allow for more generalized advice, always with a clear disclaimer.



---



\## 5. Vision and Impact



Our vision for RAD AI is to democratize legal understanding. By leveraging the power of Generative AI, we can provide a crucial service that protects individuals from legal and financial risks, helps them negotiate better terms, and gives them the confidence to understand the documents that govern their lives.


This is our protype demo video link:
https://youtu.be/5AASjes54UE

Thank you for your time and consideration. We are excited about the future of RAD AI and believe it has the potential to make a significant positive impact.

```

\##How to see our project in action##

[Deployed project](https://agamdayal2424.github.io/genaiwebd_Deploy/)

\* Ctrl+Click on the above link and use our project \*

\*\*\*We are using our free gemini API currently so the tokens are limited currently\*\*\*

thank u
