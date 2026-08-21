# Privacy Policy — Sorasaki Hina Bot

**Last updated:** August 21, 2026

This Privacy Policy explains what data the Sorasaki Hina Discord bot ("the Bot," "we," "us") collects, how it is used, and your rights regarding that data. By adding the Bot to your Discord server or interacting with it, you agree to the practices described here.

## 1. Data We Collect

We collect and store the following data, only as needed to operate the Bot's features:

| Data | Purpose | Where it's used |
|---|---|---|
| Discord User ID | Identify who sent a command/message | AI chat, warnings, reminders, economy features |
| Discord Guild (Server) ID | Keep data scoped per-server | AI chat history, warnings, reminders, AutoMod config |
| Discord Channel ID | Deliver reminders and AutoMod alerts to the correct channel | `/remind`, `/automod setup` |
| Message content you send to the Bot | Generate AI responses | AI chat feature (Gemini) |
| Image attachments you send to the Bot | Analyze images when requested | AI chat feature (Gemini) |
| Conversation history (your messages + Bot's replies) | Maintain context across a conversation | AI chat feature |
| Moderation records (warnings, reason, moderator tag) | Track moderation history per server, including warnings logged automatically by AutoMod | `/mod warn`, AutoMod |
| AutoMod configuration | Store which rules are enabled, the alert channel, violation thresholds, and any auto-punishment settings (auto-timeout, auto-kick, auto-ban) configured by the server owner | `/automod` |
| Reminder text, target time | Deliver scheduled reminders | `/remind` |
| Economy/game data (currency, cooldowns, inventory) | Support gacha/work game features | `/gacha`, `/work` |

We do **not** collect passwords, payment details, or Discord account credentials. We do not access private messages you send to other users, only messages sent directly to/mentioning the Bot in servers it's added to.

## 2. Third-Party Services

- **Google Gemini API**: When you use the AI chat feature or `/summarize`, your message text and any attached images are sent to Google's Gemini API to generate a response. This is subject to [Google's Privacy Policy](https://policies.google.com/privacy). Do not send sensitive personal information (financial data, health information, government ID numbers, etc.) through this feature.
- **SoundCloud / Lavalink audio nodes**: When you use `/play`, search queries and track URLs are sent to resolve and stream audio. No personal data beyond the query itself is transmitted.
- **YouTube oEmbed**: When a YouTube link is provided to `/play`, we fetch only the public video title via YouTube's oEmbed endpoint (no account data).

## 3. Data Storage & Retention

- Conversation history, warnings, reminders, economy data, and AutoMod configuration are stored in our database, scoped to your Discord User ID and the Guild ID where the interaction happened.
- Conversation history is retained until you clear it (see Section 4) or until the Bot is removed from the server.
- Reminders are automatically deleted once they are delivered.
- Warnings are retained as part of a server's moderation record unless removed by server staff.
- AutoMod configuration is retained for as long as the Bot remains in the server, or until reconfigured/disabled.

## 4. Your Rights & Controls

- **Clear your AI chat history** at any time using the `/reset` command.
- **Server administrators** can request removal of moderation records, AutoMod configuration, or all stored data for their server by contacting us (see Section 7).
- **Server owners** can view or disable automatic warning-based punishment at any time using `/automod warnpunish view` or `/automod warnpunish disable`.
- You may stop all data collection related to the Bot by no longer interacting with it, or by having a server admin remove the Bot from the server.

## 5. Data Sharing

We do not sell, rent, or share your data with third parties, except:
- As required to operate the features above (Google Gemini, SoundCloud/Lavalink, YouTube oEmbed).
- If required by law, legal process, or to protect the rights, safety, and property of the Bot's operators or others.

## 6. Children's Privacy

The Bot is intended for use in accordance with [Discord's Terms of Service](https://discord.com/terms), which require users to be at least 13 years old (or the minimum age in their jurisdiction). We do not knowingly collect data from users below this age beyond what Discord itself provides through normal bot operation.

## 7. Contact

For data deletion requests, questions, or concerns about this policy, contact: **[YOUR CONTACT EMAIL OR DISCORD SUPPORT SERVER LINK]**

## 8. Changes to This Policy

We may update this Privacy Policy from time to time. Material changes will be reflected by updating the "Last updated" date above. Continued use of the Bot after changes constitutes acceptance of the revised policy.
