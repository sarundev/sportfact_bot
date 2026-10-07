# Sportfact Bot 🧠

Telegram bot (Khmer): sport facts with buttons + a quick quiz.

- **🧠 ចំណេះដឹងកីឡា** / **🔄 ចំណេះដឹងមួយទៀត** — random sport fact
- **❓ សាកល្បងចំណេះដឹង** — 4-choice quiz with score
- **🏠 ទំព័រដើម** — back to the welcome screen

## Run
```bash
cp .env.example .env        # paste your token from @BotFather
python3 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/python bot.py
```

Edit content in `facts.py` and `questions.py`.
