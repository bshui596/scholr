Scholr is a modern student workspace designed to help students organize notes, study materials, assignments, and schoolwork in one place.

Features
📝 Notes and rich-text editing
🤖 AI study assistant powered by Google Gemini
📚 Course and subject organization
📊 Tables, equations, code blocks, quotes, and dividers
🖼️ Image uploads
☑️ Checklists
🎨 Modern customizable interface
🌐 GitHub Pages frontend with a Render backend
AI Backend

The AI assistant uses a Node.js/Express backend hosted separately from the frontend. The Gemini API key is stored securely as an environment variable and is never included in the frontend.

Development

Frontend:

index.html

Backend:

server.js
Node.js
Express
Google Gemini API

Never commit .env files or API keys to GitHub.

Deployment

The frontend can be deployed using GitHub Pages. The backend can be deployed using services such as Render.
