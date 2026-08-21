# 🕋 Bot Quran | Holy Quran Completion Bot




<p align="center">
  <img src="https://github.com/user-attachments/assets/56f3c0ca-6e59-4896-a1ca-2718de3d11ea"
       width="200"
       height="200"
       alt="Bot Quran Logo" />
</p>

<p align="center">
  A free and open-source Discord bot designed to help communities complete the Holy Quran during Ramadan.
  <br>
  Includes Makkah Adhan alerts, Quran pages, personalized prayer notifications, and an interactive control panel.
</p>

<p align="center">
  <a href="https://quran-bot.netlify.app">
    <strong>➜ Add Bot to Discord</strong>
  </a>
</p>

<p align="center">
  <img alt="NPM" src="https://img.shields.io/badge/NPM-CB3837?style=flat-square&logo=npm&logoColor=white" />
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img alt="Node.js" src="https://img.shields.io/badge/Node.js-43853D?style=flat-square&logo=node.js&logoColor=white" />
  <img alt="Discord.js" src="https://img.shields.io/badge/Discord.js-v14-5865F2?style=flat-square&logo=discord&logoColor=white" />
</p>

---

## Features

### Makkah Adhan Notifications

* Live countdown to the next prayer.
* Automatically updates every minute.
* Displays Makkah prayer times.

### Holy Quran Completion

* Automatically sends Quran pages after each Adhan.
* Supports compensation for missed pages.
* Sends **4 Quran pages per message**.
* Mentions the designated Quran completion role.

### Personalized Prayer Notifications

* Select a country and city.
* Creates a dedicated channel for each user.
* Sends daily prayer times.
* Notifies users when prayer time begins.

### Interactive Control Panel

* Enable or disable Quran completion.
* Enable or disable personalized Adhan notifications.
* Enable or disable Makkah Adhan notifications.
* Simple button-based controls.

---

## Requirements

Before running the bot, make sure you have:

* [Node.js](https://nodejs.org/) **18+**
* Discord.js **v14**
* Axios
* Node-Cron
* Canvas
* Fetch
* File System (`fs`)
* Path

---

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/USERNAME/REPOSITORY.git
cd REPOSITORY
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure `config.json`

Create or edit the `config.json` file and add your Discord bot information:

```json
{
  "token": "YOUR_BOT_TOKEN",
  "clientId": "YOUR_CLIENT_ID",
  "guildId": "YOUR_GUILD_ID"
}
```

| Configuration | Description                                                |
| ------------- | ---------------------------------------------------------- |
| `token`       | Your Discord bot token                                     |
| `clientId`    | Your Discord application/client ID                         |
| `guildId`     | The ID of the Discord server where you want to use the bot |

> **Important:** Never share your bot token publicly or commit it to GitHub.

### 4. Start the Bot

```bash
node index.js
```

---

## 🔗 Add the Bot

<p align="center">
  <a href="https://quran-bot.netlify.app">
    <img src="https://img.shields.io/badge/Add%20to%20Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Add Bot to Discord" />
  </a>
</p>

---

## 📜 License

Bot Quran is a **free and open-source project**.

Feel free to use, modify, and improve the project.

---

## 🤲 Support

This project is completely free and open source.

**We only ask you to remember us in your prayers. 🤲**

<p align="center">
  Made with ❤️ for the Holy Quran
</p>
