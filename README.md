# 🧠 GenAI Prompt Studio
### AI-Powered Prompt Template Generator

Create useful AI-generated content with ready-made prompt templates. **GenAI Prompt Studio** is a Python-based web application built with Gradio and powered by Groq's API. It helps users generate content for different purposes without having to write every prompt from scratch.

## ✨ Features

- 📝 **Blog Post Generator** — Create structured blog posts with titles, headings, introductions, and conclusions.
- 📣 **Social Media Content** — Generate captions, calls to action, and relevant hashtags.
- 📦 **Product Description Generator** — Write clear, audience-focused product descriptions.
- 👤 **Interview Question Generator** — Create interview questions with answers and explanations.
- 💬 **Feedback Generator** — Get constructive feedback, improvement suggestions, and strengths.
- ✉️ **Email Template Generator** — Draft professional emails with subject lines and clear calls to action.
- 📄 **Text Summarization** — Summarize longer text while preserving important ideas.
- 🌐 **Translation** — Translate text into a selected target language.
- 💭 **Sentiment Analysis** — Analyze text sentiment and receive a reason for the result.
- 🎨 **Interactive web interface** — Use a clean, responsive Gradio interface.
- ⚡ **AI-powered generation** — Generate responses through the Groq API using the `openai/gpt-oss-120b` model.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core application logic |
| Gradio | Interactive web interface |
| Groq API | AI text generation |
| GPT-OSS 120B | Language model used for generation |
| HTML and CSS | Interface styling |
| Google Colab | Notebook-based development and execution |

## 🏗️ How It Works

1. Choose a prompt template.
2. Enter the topic, text, or content you want to work with.
3. Specify the audience, tone, and desired length where applicable.
4. Generate the prompt-based AI response.
5. Review the generated content and use it for your workflow.

## 📋 Requirements

- Python 3.10 or later recommended
- A Groq API key
- Internet access for API requests
- Required Python packages

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

Replace the repository URL with your actual GitHub repository URL.

### 2. Install dependencies

```bash
pip install gradio groq
```

### 3. Configure your Groq API key

Create an API key through the [Groq Console](https://console.groq.com/).

**Option A — Google Colab**

1. Open your notebook in Google Colab.
2. Open the Secrets panel.
3. Add a secret named `GROQ_API_KEY`.
4. Paste your API key as the secret value.

**Option B — Run locally**

Set the environment variable before running the application.

Windows PowerShell:

```powershell
$env:GROQ_API_KEY="your_groq_api_key"
```

macOS/Linux:

```bash
export GROQ_API_KEY="your_groq_api_key"
```

Never commit your real API key to GitHub.

### 4. Run the application

Open `GenAI_Prompt_Studio_.ipynb` in Google Colab and run the notebook cells in order.

If you adapt the notebook into a Python application, run the corresponding script with:

```bash
python app.py
```

The Python script must contain the application code and read `GROQ_API_KEY` from your environment.

## 📁 Project Structure

```text
GenAI-Prompt-Studio/
├── GenAI_Prompt_Studio_.ipynb
├── README.md
```
## 🔐 Security Notes

- Keep API keys private.
- Use environment variables or Google Colab Secrets to manage credentials.
- Do not upload `.env` files containing secrets.
- Avoid sharing public application links that expose sensitive information.
- Review AI-generated content for accuracy before using or publishing it.

## 🎯 Use Cases

- Content creation and blogging
- Social media management
- Product copywriting
- Interview preparation
- Email drafting
- Text summarization
- Language translation
- Basic sentiment analysis

## 🔮 Future Improvements

- Add more customizable prompt templates.
- Support saving and exporting generated content.
- Add prompt history and reusable user presets.
- Improve error handling and loading indicators.
- Add download options for generated content.
- Deploy the application to a public hosting platform.

## ⚠️ Limitations

- AI responses depend on the selected model and the input provided.
- Results may contain inaccurate or incomplete information.
- API access, usage limits, and costs depend on your Groq account and current plan.
- Translation and sentiment analysis should be reviewed for important or high-stakes use.

---

⭐ If you find this project useful, consider giving the repository a star!
