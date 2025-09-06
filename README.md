

## AI Interactive Courses

🚀 Features

Gamification of Learning → Add fun elements like rewards, achievements, and challenges to keep learners motivated.

Quiz Generation using AI Models → Automatically create quizzes from study materials for better practice.

RAG-based Learning (Retrieval-Augmented Generation) → Get smarter, context-aware answers by combining local data with AI.

Theming & Customization → Personalize the look and feel of the learning assistant.

Progress Tracking → Monitor learning outcomes and track performance over time.

🛠️ Installation & Setup

Follow these steps to set up the project locally:

1. Clone the repository
git clone https://github.com/Snehagupta13/Learning_Assistant.git
cd Learning_Assistant

2. Create a virtual environment
# On Linux / Mac
python -m venv .venv
source .venv/bin/activate

# On Windows
python -m venv .venv
.venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

4. Set up environment variables

Create a .env file in the root directory of the project and add your API keys:

GROQ_API_KEY=your_api_key_here
HF_TOKEN=your_huggingface_token_here


⚠️ Never commit your .env file to GitHub. It contains sensitive API keys. Instead, use .gitignore and share an .env.example file for reference.

▶️ Usage
Run the app
python app.py

Run the CLI script
python main.py

📌 Example .env.example

Provide an example file without real secrets so contributors know what variables are needed:

# Example environment variables for Learning Assistant
GROQ_API_KEY=your_api_key_here
HF_TOKEN=your_huggingface_token_here

🤝 Contributing

Contributions are welcome! 🎉

Fork the repository.

Create a branch for your feature (git checkout -b feature/your-feature-name).

Commit your changes (git commit -m "Add new feature").

Push to your branch (git push origin feature/your-feature-name).

Open a Pull Request for review.

📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute this project with proper attribution.

✨ That’s a clean, professional, and detailed README that GitHub will render beautifully.

Would you like me to also add badges (Python version, License, Last Commit, etc.) at the top so the README looks more polished and professional?


