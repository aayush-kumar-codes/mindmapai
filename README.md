# MindMapAI ![Build Status](https://img.shields.io/badge/build-passing-brightgreen) ![Version](https://img.shields.io/badge/version-1.0.0-blue) ![License](https://img.shields.io/badge/license-MIT-yellowgreen)

## Project Description
MindMapAI is an innovative web application that leverages AI to assist users in creating and organizing their thoughts visually through mind maps. By integrating real-time collaboration and AI-generated suggestions, it enhances brainstorming sessions for teams and individuals alike.

## Features
- 🧠 **AI-assisted mind mapping**: Users can input topics and the AI generates a structured mind map with related concepts.
- 🤝 **Collaborative brainstorming**: Multiple users can work on the same mind map in real-time, with chat functionality powered by LangChain.
- 📤 **Export options**: Users can export their mind maps in various formats (PDF, image, text) for presentations or sharing.

## Tech Stack
### Frontend
- 🌐 **Next.js**: A React framework for building server-side rendered applications.

### Backend
- ⚡ **FastAPI**: A modern, fast (high-performance) web framework for building APIs with Python 3.6+ based on standard Python type hints.
- 🤖 **LangChain**: A framework for developing applications powered by language models.

### Database
- 🗄️ **PostgreSQL**: A powerful, open-source object-relational database system.

### AI Integration
- 🧠 **OpenAI**: Leveraging OpenAI's models for generating mind map suggestions.

## Installation
To set up MindMapAI locally, follow these steps:

- Clone the repository
bash
git clone https://github.com/aayush-kumar-codes/mindmapai
- Navigate to the project directory
bash
cd mindmapai
- Install the backend dependencies
bash
pip install -r requirements.txt
- Install the frontend dependencies
bash
cd frontend
npm install
- Set up the PostgreSQL database and update the configuration
- Run the backend server
bash
uvicorn main:app --reload
- Run the frontend development server
bash
npm run dev
## Usage
1. Open your browser and navigate to `http://localhost:3000`.
2. Create a new mind map by entering a topic.
3. Collaborate with others by sharing the link and brainstorming together.
4. Export your mind map in your desired format.

## API Documentation
For detailed API documentation, please refer to the [API Docs](https://github.com/aayush-kumar-codes/mindmapai/docs/api.md).

## Testing
To run the tests for the backend, execute the following command:
bash
pytest
## Deployment
To deploy MindMapAI, follow these steps:
- Build the frontend for production
bash
npm run build
- Deploy the backend using a service like Heroku, AWS, or DigitalOcean.
- Ensure the database is properly configured in the production environment.

## Contributing
We welcome contributions! Please follow these steps:
- Fork the repository.
- Create a new branch (`git checkout -b feature/YourFeature`).
- Make your changes and commit them (`git commit -m 'Add some feature'`).
- Push to the branch (`git push origin feature/YourFeature`).
- Open a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/aayush-kumar-codes/mindmapai/LICENSE) file for details.

## Acknowledgments
- Thanks to the contributors and the open-source community for their support and inspiration.
- Special thanks to the creators of FastAPI, Next.js, LangChain, PostgreSQL, and OpenAI for their amazing tools and frameworks.