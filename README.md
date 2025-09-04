# GenAI Educational Chatbot

An end-to-end Generative AI Agent Chatbot designed for interactive educational content delivery. The system combines a JavaScript-based frontend with MCP and LangGraph-powered agentic workflows, offering a responsive and engaging user experience.

## Features

- Interactive Frontend: Built with JavaScript, featuring dynamic UI components and responsive design.

- Agentic Workflow: Uses MCP and LangGraph for orchestrating multi-step reasoning and context management.

- Generative AI Integration: Powered by Gemini, enabling context-aware and adaptive responses to educational queries.

- Seamless Deployment: CI/CD via GitHub Actions, with automated builds and deployment to localhost for testing.

- Problem-Solving Focus: Designed for interactive problem-solving sessions in an educational setting.

## Getting Started
### Prerequisites

- Node.js (>= 18)

- Python (>= 3.9)

- GitHub account for CI/CD setup

### Installation
**Clone the repository**
```
git clone https://github.com/your-username/genai-edu-chatbot.git
cd genai-edu-chatbot
```

**Install dependencies**
```
npm install
pip install -r requirements.txt
```

### Run Locally
**Start frontend**
```
npm start
```
**Start backend**
```
python app.py
```

Visit http://localhost:3000 to access the chatbot.

## Deployment

- GitHub Actions pipeline included (.github/workflows/deploy.yml) for automated build and deployment.

- Default setup deploys to localhost; extendable to cloud platforms.

## Tech Stack

- Frontend: JavaScript, HTML, CSS

- Backend/Workflow: MCP, LangGraph

- AI Model: Gemini

- CI/CD: GitHub Actions

## Use Cases

- Interactive tutoring

- Problem-solving practice

- Personalized learning sessions



## License

MIT License
