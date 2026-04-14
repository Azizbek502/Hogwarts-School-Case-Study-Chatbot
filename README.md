# Hogwarts-School-Case-Study-Chatbot
Getting Started

1. Clone/Download the Project

   git clone <your-repo-link>
   cd <project-folder>

Or just download the files if you're not using Git.

2. Open in Botpress
  - Go to Botpress Dashboard
  - Create a new bot (or open existing)
  - Import the project (if exported as `.bpz`)  
   OR manually recreate flows and KBs
3. Set Up Knowledge Bases

Add PDF Documents
- Go to Knowledge Bases
- Click Add Source
- Upload your PDF files
- Wait for indexing
Add Website (Wikipedia)
- Add https://wikipedia.org as a source
- Botpress will crawl and index content

Enable Web Search
- Turn on Web Search in integrations/settings
- This allows real-time answers beyond stored knowledge
4. Configure the Bot

- Set system instructions (tone, behavior)
- Connect KBs to your bot
- Define fallback responses if needed
5. Run the Bot

- Use the built-in emulator in Botpress  
- Or deploy to:
  - Web chat
  - Telegram / WhatsApp (if integrated)

