# LLM_QA_Chat-bot

A small local question-answering chatbot built around LLMs with both a CLI and a simple web UI.

**Purpose:** Provide a lightweight interface to ask questions of a local/hosted LLM-backed QA system.

**Quick Start**
- **Prerequisites:** Python 3.8+ and `pip`.
- **Install dependencies:**

```bash
python -m venv venv
source venv/bin/activate    # on Windows (bash): venv\Scripts\activate
pip install -r requirements.txt
```

- **Run CLI:**

```bash
python LLM_QA_CLI.py
```

- **Run Web UI (local):**

```bash
python app.py
# then open http://127.0.0.1:5000 in your browser
```

**Files & Structure**
- **`app.py`**: Flask web app entrypoint for the web UI.
- **`LLM_QA_CLI.py`**: Command-line interface for asking questions.
- **`templates/`**: HTML templates (includes `index.html`).
- **`static/`**: Frontend assets (`app.js`, `style.css`).
- **`requirements.txt`**, **`runtime.txt`**, **`Procfile`**, **`render.yaml`**: dependency/runtime/deployment config files.
- **`LLM_QA_hosted_webGUI_link.txt`**: If present, contains a hosted web GUI link.

**Deployment**
- This repo includes `Procfile` and `render.yaml` for simple deployments (Heroku/Render or similar). Follow your provider's instructions and ensure `requirements.txt` and `runtime.txt` are honored.

**Notes**
- No license file is included; check with the project owner for licensing.
- If you use a hosted LLM or external API keys, keep credentials out of the repository and use environment variables.

**Contributing**
- Send pull requests or open issues for bugs and feature requests.

**Contact**
- Repository owner: `Xstatic72` (local workspace).
