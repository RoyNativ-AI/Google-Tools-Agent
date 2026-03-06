# Google Tools Agent

AI agent for interacting with Google services (Gmail, Calendar) using natural language. Powered by OpenAI.

## Features

- **Gmail Integration** - Search, read, and send emails with natural language
- **Calendar Management** - View, create, and manage Google Calendar events
- **Google Search** - AI-powered search simulation
- **Interactive CLI** - Natural conversation interface
- **OAuth 2.0** - Secure authentication with Google

## Quick Start

```bash
# Clone and setup
git clone https://github.com/RoyNativ-AI/Google-Tools-Agent.git
cd Google-Tools-Agent

# Create virtual environment
python -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Configure
cp .env.example .env
# Add your OpenAI API key to .env
```

## Google Cloud Setup

1. Create project at [Google Cloud Console](https://console.cloud.google.com/)
2. Enable APIs: Gmail API, Google Calendar API
3. Create OAuth 2.0 credentials (Desktop app)
4. Download `credentials.json` to project root

## Usage

```bash
python main.py
```

Example commands:
- "Show my unread emails"
- "Schedule a meeting tomorrow at 2pm"
- "Send an email to john@example.com"

## Configuration

| Variable | Description |
|----------|-------------|
| `OPENAI_API_KEY` | Your OpenAI API key |
| `GOOGLE_CLIENT_ID` | OAuth client ID |
| `GOOGLE_CLIENT_SECRET` | OAuth client secret |

## Requirements

- Python 3.7+
- Google Cloud account
- OpenAI API key

## License

MIT
