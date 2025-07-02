# Noma

Noma is a privacy-first local AI companion desktop app, inspired by LM Studio but with enhanced capabilities and user control.

## Key Features

- **Model Search & Download**: Easily search for and download AI models, similar to LM Studio.
- **Web Search Integration**: Models can optionally use web search to enhance responses. Supported search APIs include:
  - DuckDuckGo (default)
  - Brave Search
  - Google
  - Bing
- **Web Scraping (Optional)**: Users can enable or disable web scraping. When enabled, models can fetch and process content from any website for richer answers. The app works fully offline if web features are disabled.
- **Session Management**: All conversations are stored as JSON files in a user-selected folder, ensuring privacy and easy backup.
- **Privacy First**: All processing is local by default. No data is sent to external servers unless the user enables web features.

## Tech Stack

- **Electron**: Desktop application framework
- **SvelteJS**: UI framework
- **daisyUI (Tailwind CSS)**: UI components and styling
- **Puppeteer**: Web scraping backend
- **llama.cpp**: Local LLM backend (with support for Ollama, Hugging Face, and more planned)

## Planned Improvements

- Support for additional model providers
- Enhanced session management and search
- More customizable privacy controls

---

> Noma aims to be your private, local AI companion with the flexibility to go online when you want, and stay offline when you don't.
