# Divine Discord Bot — GitHub Pages policy website

This folder contains a small, responsive static website with:

- `index.html` — policy landing page
- `terms.html` — Terms of Service
- `privacy.html` — Privacy Policy
- `assets/styles.css` — shared styling

## Important: complete the operator details first

Before publishing, open **both** `terms.html` and `privacy.html` and replace:

- `[BOT OPERATOR / ORGANIZATION NAME]` with the real person or organization responsible for operating the bot.
- `[CONTACT EMAIL]` with a working email address that is monitored for privacy and support requests.

Do not publish the placeholders. The policy text must accurately describe the bot's actual code, database, logs, hosting services, permissions and data lifecycle. In particular, verify whether your bot or hosting provider stores command logs, message content, interaction payloads, IP addresses or additional Discord data. Update the Privacy Policy if it does.

The supplied policy reflects the storage categories provided for this draft: Discord user IDs, usernames, server IDs and configuration settings. It is a practical starting template, not legal advice or a guarantee of Discord verification approval. Have the final text reviewed for the laws applicable to the operator and users.

## Publish with GitHub Pages

1. Sign in at <https://github.com/> and create a **public** repository, for example `divine-discord-bot-policies`.
2. Upload the contents of this folder to the repository's top level. The repository root should contain `index.html`, `terms.html`, `privacy.html`, `README.md` and the `assets` folder.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish the site. GitHub will show the public website address in the Pages settings.

Your links will have this format (replace the username and repository name with your actual values):

- Policy home: `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/`
- Terms of Service: `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/terms.html`
- Privacy Policy: `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY/privacy.html`

## Add the links to Discord

1. Open the [Discord Developer Portal](https://discord.com/developers/applications) and choose **Divine Discord Bot**.
2. Open **General Information**.
3. Paste the published `terms.html` address into **Terms of Service URL**.
4. Paste the published `privacy.html` address into **Privacy Policy URL**.
5. Save your changes and confirm both links open publicly in a private/incognito browser window.

## Updating the documents

Edit the relevant HTML file, commit the change to the `main` branch, and GitHub Pages will publish the update. Keep the “Last updated” date accurate whenever you materially change either policy.
