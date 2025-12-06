⚖️ CPS Procedural Guide & Legal Term Simplifier

A free, supportive web application designed to help individuals navigate the complex procedural language and documentation associated with Child Protective Services (CPS) and Family Court in the United States.
Built as a simple, single-page utility using React and the Gemini API, this tool provides state-specific, simplified explanations of legal terms and court processes.

⚠️ MANDATORY DISCLAIMER
THIS IS AN EDUCATIONAL TOOL, NOT A LAW FIRM.
Every response provided by this guide explicitly states that the information is for procedural and educational purposes only and DOES NOT constitute legal advice. Users are mandatorily directed to consult a licensed attorney in their jurisdiction for advice specific to their individual case, deadlines, and legal strategy.

✨ Features
State-Specific Guidance: Users select their state to receive contextually grounded information based on current US legal frameworks.

Procedural Focus: Designed to simplify technical terms (e.g., Adjudication Hearing, Case Plan, Petition for Termination of Parental Rights) and complex sections of court paperwork.

Empathetic Tone: The AI model is instructed to provide answers in a supportive, trauma-informed, and non-judgmental tone.

Real-time Grounding: Uses Google Search to ensure the information and sources are up-to-date.

Zero-Cost Launch: Built as a single-file application for free deployment on platforms like GitHub Pages.

🚀 How it Works
User Input: The user selects a state and enters a procedural question or a legal phrase.
API Query: The application sends the request along with a strict system prompt (including the mandatory legal disclaimer) to the Gemini API.

Grounding & Simplification: The API uses Google Search to find relevant state-level information and simplifies it into clear, plain language.

Output: The simplified guidance and relevant source links are displayed to the user, always preceded by the legal warning.
🛠️ Tech Stack

Frontend: React (Single-file Component)

Styling: Tailwind CSS (via CDN)

Intelligence: Gemini 2.5 Flash API (for grounded, simplified content generation)

Hosting: GitHub Pages (or any static hosting platform)
