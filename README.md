# Tinder Swiping Bot

A Selenium bot that logs into Tinder (via Facebook) and automatically swipes right — inspired by the classic Tinder automation exercise.

## How It Works

1. Opens Tinder and clicks **Log in**
2. Logs in through the Facebook popup using `FB_EMAIL` / `FB_PASSWORD`
3. Dismisses the location, notification, and cookie prompts
4. Clicks the "like" button up to 100 times
5. Handles the "It's a Match!" popup when it appears

## Setup

Fill in your credentials at the top of `main.py`:

```python
FB_EMAIL = "your_facebook_email"
FB_PASSWORD = "your_facebook_password"
```

Then run:

```bash
python main.py
```

> Note: credentials are left blank for safety. Automation may violate Tinder's
> Terms of Service — use at your own risk.

## Requirements

```
selenium
```