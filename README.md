# Smart SimSimi API Bot

This is a **powerful SimSimi-style chatbot API** that supports **Telegram, Messenger, and Discord**.  
It features **smart chatting**, **auto teach**, **edit teach**, and **message management**, making it easy to build an intelligent and interactive bot.

---

## Features

- **Smart Talking:** The bot responds intelligently to user messages.  
- **Auto Teach:** Automatically learns new messages from users.  
- **Edit Teach:** Admins can manually edit or update responses.  
- **Message Management:** Tracks all incoming and outgoing messages.  
- **Multi-Platform Support:** Works seamlessly on Telegram, Messenger, and Discord.  

---

## Command Triggers

The bot responds to specific trigger names. By default, it uses:

```javascript
const matchPrefix = /^(bebe|janu|xan|bbz|mari|arshi)\s+/i;
```
You can add or remove names as you like.
The bot will only respond when a message starts with one of these triggers.
Example:


mari hello bot
The bot will respond because mari is a valid trigger.
You can also set your own name as the trigger for personal use.
Setup Instructions
Place the bot's command file in your project (e.g., commands/ folder).
Update the trigger names in the command file if needed.
Control and manage the bot from the website:
https://rx-baby.netlify.app/
From the website, you can:
Teach new responses
Edit existing messages
Monitor all bot activity in real-time
Use your own custom trigger names
Notes
Make sure your bot has the necessary permissions for Telegram, Messenger, or Discord.
Keep the command file updated to access new features.
Using the website makes managing the bot easy even for beginners.
