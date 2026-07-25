# 🎨 Guess The Drawing. The #1 Multiplayer Drawing Game & Clan Wars Discord Bot

<p align="center">
  <a href="https://discord.com/api/oauth2/authorize?client_id=1530031497174585475&permissions=277025778688&scope=bot%20applications.commands">
    <img src="https://img.shields.io/badge/🤖_ADD_BOT_TO_DISCORD-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="42" alt="Add Bot to Discord">
  </a>
  <a href="https://discord.gg/F5yKuwZfhJ">
    <img src="https://img.shields.io/badge/💬_JOIN_SUPPORT_SERVER-7289DA?style=for-the-badge&logo=discord&logoColor=white" height="42" alt="Join Support Server">
  </a>
</p>

> ### 🚀 [**👉 CLICK HERE TO INVITE GUESS THE DRAWING TO YOUR DISCORD SERVER 👈**](https://discord.com/api/oauth2/authorize?client_id=1530031497174585475&permissions=277025778688&scope=bot%20applications.commands)

---

## 🚀 About Guess The Drawing

**Guess The Drawing** is a feature-packed multiplayer drawing guessing minigame, trivia engine, and Clan Wars Discord Bot designed to bring your Discord server to life!

Watch drawings appear in your server chat, race against your friends to guess the correct words in real time, earn XP to level up through **21 custom badge ranks**, flex your **custom 2D Canvas profile cards**, and build or lead your **Clan to global dominance in 5-round head-to-head Clan Wars**!

---

## 🔥 Key Features

* 🎯 **Fast-Paced Drawing Gameplay**: Endless drawing challenges with automated hint reveals every 30 seconds.
* 🖼️ **Cyberpunk 2D Canvas Profile Cards (`/profile`)**: Generate high-definition, dynamic 2D Canvas graphics with custom avatar frames, stats, rank tags, and auto-fitting text scaling.
* 📊 **XP Progression Dashboard (`/xp`)**: Track your level, progress bar, overall score, and unlocked badges.
* 🎉 **Instant Level-Up Celebrations**: Real-time chat announcements whenever players level up during gameplay.
* 🛡️ **Global Clan System & 5-Round Clan Wars (`/clan`)**:
  * **Global Unique Clan Names**: Guaranteed unique clan names worldwide.
  * **Clan Roles**: `👑 Leader`, `⭐ Co-Leader`, and `👤 Member`.
  * **DM Invites**: Direct message invites with automatic game channel fallback if user DMs are closed.
  * **⚔️ Clan Wars (`/clan fight`)**: 5-round head-to-head battles featuring **Live Score Headers** (`⚔️ CLAN WAR: Kings (2) vs Titans (1) — Round 4/5`) and **Clan War MVP Highlights**!
* 🏆 **Global & Server Leaderboards**: Compete against members in your local server or rank on the global worldwide leaderboards!

---

## 🎮 Categorized Command Guide

### 🛡️ Server Setup & Admin Commands
| Command | Description | Permission |
| :--- | :--- | :--- |
| `/config setup [channel]` | Set up the dedicated game channel for drawing games in your server. | Administrator |
| `/config view` | View current server game configuration and channel settings. | Administrator |
| `/config reset` | Reset server settings back to default. | Administrator |
| `/start` | Start an active game session in your server game channel. | Admin / Game Setup |
| `/end` | End the active game session in your channel. | Admin / Game Setup |
| `/pause` | Temporarily pause active drawing games in your server. | Admin / Game Setup |
| `/resume` | Resume paused drawing games in your server. | Admin / Game Setup |

---

### 🎮 Player Profile & Stats Commands
| Command | Description | Usage |
| :--- | :--- | :--- |
| `/profile [user]` | View your high-definition 2D Canvas profile card with rank and stats. | `/profile` or `/profile @user` |
| `/xp` | View your XP dashboard, level progression bar, and current badge tier. | `/xp` |
| `/leaderboard server` | View the top 10 players in your Discord server. | `/leaderboard server` |
| `/leaderboard global` | View the global top 10 players worldwide across all servers. | `/leaderboard global` |
| `/gameinfo` | View current active round information and drawing game rules. | `/gameinfo` |

---

### ⚔️ Clan System & Clan Wars Commands (`/clan`)
| Command | Description | Role Access |
| :--- | :--- | :--- |
| `/clan create [name]` | Create a new clan with a globally unique name. | Anyone (not in a clan) |
| `/clan invite @user` | Invite a user to your clan via DM (max 5 members). | Leader / Co-Leader |
| `/clan fight [name]` | Challenge an opposing clan to a 5-round Clan War! | Leader / Co-Leader |
| `/clan promote @user` | Promote a regular Member to Co-Leader. | Leader Only |
| `/clan demote @user` | Demote a Co-Leader back to regular Member. | Leader Only |
| `/clan kick @user` | Remove a member from your clan. | Leader / Co-Leader |
| `/clan transfer @user` | Transfer clan leadership to another member (1-day cooldown). | Leader Only |
| `/clan disband` | Permanently delete your clan via confirmation button. | Leader Only |
| `/clan leave` | Leave your current clan (Leaders must disband). | Member / Co-Leader |
| `/clan info [name]` | View clan level, total XP, war victories, and member roster. | Everyone |
| `/clan leaderboard` | View global top 10 clans ranked by War Victories (`🏆`) and Clan XP. | Everyone |

---

### ⚙️ Information & Utility Commands
| Command | Description | Usage |
| :--- | :--- | :--- |
| `/help` | Show complete interactive command menu and guide. | `/help` |
| `/ping` | Check bot latency and Discord API WebSocket response time. | `/ping` |
| `/invite` | Get the official Discord bot invite link for your server. | `/invite` |
| `/support` | Get a link to join the official Discord support server. | `/support` |
| `/vote` | Vote for the bot on Top.gg to earn bonus XP rewards. | `/vote` |
| `/about` | Learn about the bot features and game rules. | `/about` |
| `/changelog` | Read the latest version release notes and new features. | `/changelog` |

---

## 🎖️ 21-Tier Rank & Badge Progression

Players earn XP for every correct drawing guess ($\text{Level} = \lfloor\sqrt{\text{XP} / 100}\rfloor + 1$):

| Level Range | Rank Title | Badge Category |
| :--- | :--- | :--- |
| **Level 1 – 4** | `Novice` | 🥉 Bronze Tier |
| **Level 5 – 9** | `Apprentice` | 🥈 Silver Tier |
| **Level 10 – 14** | `Adept` | 🥇 Gold Tier |
| **Level 15 – 19** | `Expert` | 💎 Cyan Tier |
| **Level 20 – 29** | `Master` | 🔮 Purple Tier |
| **Level 30 – 39** | `Grandmaster` | 🔴 Red Tier |
| **Level 40 – 49** | `Legend` | 🔥 Orange Tier |
| **Level 50 – 74** | `Mythic` | ⚡ Yellow Tier |
| **Level 75 – 99** | `Immortal` | 🌌 Deep Violet Tier |
| **Level 100 – 149** | `Divine` | ✨ Bright Gold Tier |
| **Level 150 – 199** | `Celestial` | 🌠 Sky Blue Tier |
| **Level 200 – 299** | `Ascended` | 💫 Platinum Tier |
| **Level 300 – 399** | `Titan` | 🛡️ Metallic Gray Tier |
| **Level 400 – 499** | `Overlord` | 👑 Royal Crimson Tier |
| **Level 500 – 599** | `Vanguard` | ⚔️ Emerald Green Tier |
| **Level 600 – 699** | `Apex` | 🏔️ Ice Blue Tier |
| **Level 700 – 799** | `Sovereign` | 🎖️ Imperial Amber Tier |
| **Level 800 – 899** | `Ethereal` | 👻 Ghost White Tier |
| **Level 900 – 999** | `Omnipotent` | 🌌 Void Black Tier |
| **Level 1000 – 1499**| `Godlike` | ⚡ Electric Crimson Tier |
| **Level 1500+** | `Infinite` | ♾️ Cosmic Rainbow Tier |

---

## 📖 How to Start Playing in 3 Simple Steps

1. **[👉 Add Bot to Your Discord Server](https://discord.com/api/oauth2/authorize?client_id=1530031497174585475&permissions=277025778688&scope=bot%20applications.commands)**: Click the invite link to add Guess The Drawing to your server.
2. **Setup Game Channel**: Server Admins run `/config setup #channel-name` to designate a game channel.
3. **Start Playing**: Run `/start` in the game channel to launch your first drawing game session!

---

<p align="center">
  <a href="https://discord.com/api/oauth2/authorize?client_id=1530031497174585475&permissions=277025778688&scope=bot%20applications.commands">
    <img src="https://img.shields.io/badge/🤖_ADD_BOT_TO_DISCORD-5865F2?style=for-the-badge&logo=discord&logoColor=white" height="42" alt="Add Bot to Discord">
  </a>
</p>
