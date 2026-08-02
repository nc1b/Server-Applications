# Server Applications

Server Applications is a Discord bot that forwards server-member applications to a designated channel for staff review. It keeps incoming requests in one place without requiring staff to manage applications from a separate dashboard.

For background on Discord's server-member applications, see the [official Discord support article](https://support.discord.com/hc/en-us/articles/29729107418519-Server-Member-Applications).

## Invite

[Add Server Applications to Discord](https://discord.com/oauth2/authorize?client_id=1326624940010639400)

## Preview

![Configuration preview](https://raw.githubusercontent.com/nc1b/Server-Applications/master/Assets/config.png)

![Application preview](https://raw.githubusercontent.com/nc1b/Server-Applications/master/Assets/app.png)

## Security

Keep bot credentials in environment variables or your hosting provider's secret manager. Never commit a bot token, webhook URL, or other credential to the repository. If a secret is exposed, revoke and rotate it immediately in the relevant provider dashboard.
