# Telegram Alert Bot

This bot sends alerts to a Telegram channel.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/telegram_alert_bot.git
   cd telegram_alert_bot
2. Create a .env file in the project root directory and add the following content:
    ```bash
    TOKEN=your_bot_token_here
    BOT_USERNAME=your_bot_username_here
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
4. Run the bot:
   ```bash
   python bot.py
   
### Podsumowanie

- **Plik `.env`**: Przechowuje poufne informacje i jest dodany do `.gitignore`, więc nie jest przesyłany do repozytorium.
- **Plik `.env.example`**: Przykładowy plik, który nie zawiera rzeczywistych wartości, ale wskazuje, jakie zmienne są potrzebne.
- **Dokumentacja w `README.md`**: Instrukcje dotyczące tworzenia pliku `.env` i uruchamiania projektu.

### Kompletna struktura projektu:

telegram_alert_bot/
├── bot.py
├── .env.example
├── .gitignore
├── README.md
└── requirements.txt