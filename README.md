DoubtGPT is an interactive web application that leverages OpenAI’s GPT models to help users ask questions and receive AI-powered answers in real‑time.

🚀 Features
-Ask-anything interface — Users can type in any query and receive an AI-generated response.

-Conversation history — Tracks previous questions and answers for context.

-Instant response — Powered by OpenAI API for fast and accurate replies.

-Clean UI — Minimal, user-friendly frontend built with JavaScript/HTML/CSS.

🛠️ How It Works
Frontend: Captures user input and sends it to the server via fetch/AJAX.

Backend: Receives queries, calls OpenAI API, and returns model-generated responses.

API integration: Uses openai.completions.create({ ... }) to get AI-generated answers.

Smart chat: Maintains context to allow follow-up questions.
