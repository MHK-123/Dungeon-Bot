# DungeonKeeper – Discord Report System Bot 🛡️

DungeonKeeper is a Discord moderation bot that allows users to report issues through DMs while staff manage cases using interactive moderation buttons.

It is designed to keep reports organized, transparent, and easy for moderators to handle.

---

# Features

## 📩 DM Report System

Users can DM the bot to report rule violations.

The report should include:

- 👤 Username of the member
- 📜 What they did
- 📸 Screenshot evidence

The report is automatically forwarded to the staff channel.

---

## 🚨 Case System

Each report creates:

- Unique Case ID
- Moderation Embed
- Dedicated Case Thread

Example:

🚨 New Report Case #12  
Reporter: username  
Status: OPEN

---

## 👮 Moderator Actions

Staff can manage reports using buttons.

Available actions:

- Reply
- Warn
- Mute
- Ban
- Close Case
- Blacklist Reporter

Moderators can specify which user the action should apply to.

---

## 🔔 Staff Role Pings

When a report is submitted, the bot pings configured staff roles.

Example:

@Moderator @Admin 🚨 New Report Case

---

## 📬 Reporter Updates

The reporter receives updates when:

- Staff replies
- A moderation action is taken
- The case is closed

---

# Setup

## 1. Clone Repository

```bash
git clone https://github.com/yourusername/dungeonkeeper
cd dungeonkeeper
```bash
git clone https://github.com/yourusername/dungeonkeeper
cd dungeonkeeper
