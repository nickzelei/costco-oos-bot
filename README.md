# Costco Out-of-stock Bot

Checks Costco to see if an item is in stock and sends text if it is.

Uses Twilio for texting

# Setup
```bash
pip3 install -r requirements.txt
```
## Environment
```bash
touch .env
```

```
SEND_PHONE_NUMBER=<phone-number>
RECEIVE_PHONE_NUMBER=<phone-number>
TWILIO_ACCOUNT_SID=<account-sid>
TWILIO_AUTH_TOKEN=<account-auth-token>
```

The .env file must be in the CWD dir to be properly loaded.
```bash
python3 bot.py
```

Update `PAGE_URL` in the script to change the page to ping.

Based off of [this blog post](https://aryaboudaie.com/python/technical/educational/2020/07/05/using-python-to-buy-a-gift.html)
