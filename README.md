https://t.me/TGOrchestra_Bot

# tg-orchestra-docs
Docs for TG Orchestra.

# TG Orchestra – Manage Employee Access to Telegram Work Chats

TG Orchestra is a corporate Telegram chat management tool that gives HR managers, IT admins, and business owners full visibility over their team's group memberships. Connect your Telegram bot once, and TG Orchestra will automatically track which employees are members of which work chats in real time. From a single dashboard, you can view all your Telegram groups and their members side by side — no need to open Telegram manually or check each chat one by one. When an employee leaves the company or loses access rights, you can remove them from any Telegram group directly from the dashboard. It is the simplest way to manage Telegram workspace access control across your entire organization.

---

## Getting Started

1. Create a bot via @BotFather
2. Add the bot to your work chats and grant it admin rights
3. Ask your existing employees to send any message to the bot (a single DM is enough to register them)
4. New employees will be added to the system automatically once they appear in any chat the bot is monitoring

### Safety Requirements

- Keep your bot token secure — store it in a password manager
- Make sure Group Privacy is enabled in BotFather settings so the bot cannot read chat messages (this is the default — just verify it is on)
- When granting the bot admin rights, disable all permissions except "Add/Remove Members"

---

## FAQ

**Who is this app for?**
Any business that uses Telegram for internal group chats. It is designed for whoever manages corporate access control — such as an HR manager, IT admin, or office manager.

**Why do I need to grant the bot admin rights?**
Telegram only notifies bots of join and leave events if they have admin rights in the group. Without admin access, the bot cannot detect membership changes or remove users on your behalf. Only the "Add/Remove Members" permission is needed — all other admin permissions should be left disabled.

**I already have chats with employees. How do I set up tracking for them?**
Add the bot to each chat, grant it admin rights, and ask your employees to send the bot any DM. The bot will check which employees are already present in each chat and bring everything up to date automatically.

**I want to create a new work chat. What is the best way to add the bot?**
Add it when you create the chat and grant it admin rights right away. This ensures the bot tracks membership from day one.

**I hired a new employee. Do they need to interact with the bot?**
No. Once they join any chat the bot is monitoring, they will be registered automatically. If they were already in a chat before the bot was added, ask them to send the bot any DM to get registered.

**How does the bot know who is in each chat?**
The bot watches every join and leave event in real time. When it is first added to an existing chat, it goes through your registered employees one by one and checks whether each person is already a member. It also runs this check whenever a new employee registers by DMing the bot.

**Do I need to do anything after an employee is dismissed?**
Just remove them from all relevant chats. The system will automatically update their membership status and remove their profile — no manual cleanup needed.

**Can I remove an employee from a chat directly in the app?**
Yes. Open the chat in the dashboard, find the employee, and click the Delete button next to their name. They will be kicked from the Telegram chat immediately.

**Can I manage multiple Telegram work chats from one place?**
Yes. TG Orchestra connects to all your Telegram groups through a single registered bot, giving you a unified dashboard where you can view and manage memberships across every connected chat.

**Do employees need to install anything to be tracked?**
No app or installation is required. However, employees who were already in your chats before the bot was added will need to send the bot one DM to register. After that, any new employee who joins a monitored chat is tracked automatically.

**Is TG Orchestra suitable for companies that onboard and offboard staff frequently?**
Yes. TG Orchestra tracks group memberships in real time and lets you remove employees from chats directly from the dashboard, making it easy to manage access as your team changes.
