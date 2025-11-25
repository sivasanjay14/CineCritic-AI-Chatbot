# 🎬 CineCritic-AI-Chatbot

## About the Project
CineCritic AI is a domain-specific conversational agent designed to deliver structured, objective, and insightful movie reviews. It acts as a digital expert critic, providing detailed analysis, sentiment evaluation, and personalized recommendations for any film.

## About the Project
The core application is built using a resilient Python-Flask backend responsible for managing the API interface and the persistent chat session. The intelligence layer is powered by the Google Gemini API, specifically utilizing the stable gemini-2.5-pro model, which is meticulously tuned to embody the persona of a "Movie Review Expert."

This project successfully demonstrates the integration of modern AI capabilities into a focused web application, emphasizing
- Structured Output: Consistent delivery of analysis points (Sentiment, Highlights, Lowlights).
- Session Context: The ability to handle follow-up queries naturally within the conversation flow.
- Professional Tone – Focused strictly on the domain of cinema.

## Project Overview
The application combines a robust backend, a clean interface, and a powerful AI reasoning engine.
Core Components
- Backend: Python + Flask
- AI Model: Google Gemini gemini-2.5-pro
- Frontend: HTML + Tailwind CSS + JavaScript (developed using Claude AI & ChatGPT)
- Session Management: Persistent chat context
- Environment Handling: python-dotenv for secure API key usage

## Smart Query Handling
CineCritic AI is strictly configured via system instructions to act as a "Movie Review Expert." This ensures all responses are narrowly focused on the domain of cinema.
Every review provided adheres to a strict, structured output format, designed for clarity and quick consumption:
- Overall Sentiment: (e.g., Positive / Negative / Mixed)
- Reasoning: (One-sentence summary of the main takeaway)
- Highlights: (1-2 strong points, e.g., cinematography, acting)
- Lowlights: (1-2 weak points, e.g., pacing, plot holes)
- Suggestions: (Recommendations for similar films)

If a user asks a question unrelated to movies (e.g., historical facts or cooking recipes), the chatbot is instructed to reject the prompt cleanly, maintaining its specialized role and ensuring the integrity of the chat session.

## Snapshots
### Chat Interface
<img width="1915" height="1011" alt="image" src="https://github.com/user-attachments/assets/e971c047-4625-4761-9b2a-3fb491f9e86b" />

### Chatbot Response - Movie (RRR)
<img width="1919" height="1013" alt="image" src="https://github.com/user-attachments/assets/11688ed0-bc8e-48b3-8bd6-e63309bafbf3" />

### Chatbot Response - Movie (Hum Saath - Saath Hain)
<img width="1918" height="1013" alt="image" src="https://github.com/user-attachments/assets/c3d44c81-72ce-4e01-91a1-532fcb63c95e" />

## Acknowledgment
I would like to express my sincere gratitude to Lovely Professional University for providing the academic platform and necessary resources to complete this project.<br>
A special thanks to [Nagadevara Satya Sudheer](https://github.com/sudheernaidu42) for his dedication, technical support, and collaboration throughout the development of CineCritic AI.



