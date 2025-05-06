# Telegram Uncensored Bot

بوت تيليجرام بدون رقابة يرد بشكل ساخر ومفتوح باستخدام OpenRouter و نموذج Mythomax.

## المتطلبات

- Python 3.10+
- حساب في [OpenRouter.ai](https://openrouter.ai/)
- بوت تيليجرام وتوكن من BotFather

## طريقة التشغيل

1. أنشئ ملف `.env` من `.env.example` وضع فيه التوكنات:

```
BOT_TOKEN=توكن_البوت
OPENROUTER_API_KEY=مفتاح_API
```

2. ثبّت المكتبات:

```bash
pip install -r requirements.txt
```

3. شغّل البوت:

```bash
python bot.py
```

## ملاحظة

لا ترفع ملف `.env` إلى GitHub!
