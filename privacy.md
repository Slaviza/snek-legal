# Privacy Policy

**App name:** Snek
**Last updated:** October 28, 2026

This policy explains what information Snek ("the App", "we", "us") collects, how it is used, and what choices you have. Snek is a Discord app for server security, moderation, community management, music, economy, and games, with a companion web dashboard.

## 1. Information we collect

**Discord data.** Depending on which features are used, Snek reads and/or saves:
- User IDs, usernames, global display names, and avatar URLs
- Server (guild) IDs, names, icon URLs, owner IDs, and member counts
- Channel IDs and names
- Role IDs, names, and colors
- Voice channel connection states (including mute/deafen status)
- Members' current game activity (via Discord presences)
- Audit log executor IDs and tags, when moderation or security events occur

**Message content.** Snek reads message content in real time, only in memory, to detect rule violations (phishing links, unauthorized Discord invites, duplicate-message spam, mass mentions, and excessive capital letters) and to award XP. Normal chat messages are **not** saved or logged. If a message triggers an auto-moderation rule, the message is deleted and only the reason (for example, the blocked domain or the number of mentions) is recorded in the security log.

**Per-user data we store:**
- Economy and leveling profile: User ID, username, wallet and bank balances, bank capacity, XP, level, daily streak, cooldown timestamps, purchased shop items, heist shield charges, and gameplay stats (games played, games won, net profit, successful robberies, messages sent)
- Security log entries: if a user triggers a security or auto-moderation rule, their username, User ID, and the action taken
- Temporary dashboard login sessions (kept in memory for up to 24 hours)

**Per-server data we store:**
- Anti-nuke and anti-raid thresholds, whitelisted User IDs, auto-moderation settings, and blocked domain lists
- Lockdown status and locked channel IDs
- Verification role names
- Welcome and goodbye channels and message templates
- Leveling multipliers and announcement channels
- Default music volume
- Reaction role panel records (message ID, channel ID and name, panel title, and mapped Role IDs)

**Not saved to disk:** member game activity (presence data) is only used to show live activity in the `/games` command and the dashboard, and is never stored. Rate-limit counters and active game sessions exist only in memory and are wiped when the App restarts.

We do **not** collect passwords, payment information, email addresses, or real-world personal information like addresses or phone numbers.

## 2. How we use information
We use this information only to:
- Run the App's features (moderation, security, leveling, economy, games, music, welcome messages, reaction roles, and the dashboard)
- Save server settings and user progress
- Detect and prevent abuse, raids, and spam
- Fix bugs and keep the App running

## 3. Third parties
We do **not** sell your data, and the App uses no analytics, tracking, telemetry, or third-party AI services. The only external services involved are:
- **Discord:** the App communicates with Discord's API, and the dashboard uses Discord OAuth2 for login. Discord's own [Privacy Policy](https://discord.com/privacy) applies.
- **YouTube and SoundCloud:** when someone uses `/music play`, the search query is sent to these services to find and stream audio.
- **Google Fonts:** the web dashboard loads fonts from Google in your browser.

We may also disclose information if required by law.

## 4. Storage and security
Persistent data is stored in plain files on the computer that hosts the App. The App and its dashboard run on that machine and are made reachable through a secure tunnel. We take reasonable steps to protect the data, but no system is completely secure, and we cannot guarantee absolute security.

## 5. Retention and deletion
- **Security logs:** only the 150 most recent entries are kept; older entries are automatically dropped. Server administrators can clear all security logs at any time from the dashboard.
- **Dashboard sessions:** expire automatically after 24 hours.
- **Rate limits and active games:** exist only in memory and are cleared when the App restarts.
- **Economy, leveling, and server settings:** kept until they are deleted. Removing Snek from a server does not currently delete that server's saved settings automatically.

You can ask us to delete your data, or your server's data, at any time by contacting us (see below). We will do this within a reasonable time.

## 6. Children
Snek follows Discord's minimum age requirement. We do not knowingly collect data from anyone below the age allowed to use Discord. If you believe such a person has used the App, contact us and we will delete their data.

## 7. Your rights
You can ask what data we hold about you, ask us to correct it, or ask us to delete it. If you are in South Africa, these rights are also protected by the Protection of Personal Information Act (POPIA). If you are in the EU or UK, GDPR rights apply.

## 8. Changes
We may update this policy from time to time. The "Last updated" date above shows the latest version. Continued use of the App after changes means you accept the updated policy.

## 9. Contact
For questions or data requests, email: **YOUR_EMAIL_HERE**
