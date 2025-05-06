# 🔔 GitHub Actions – Discord Push Notifier

This repository uses a GitHub Actions workflow to send a notification to a Discord channel whenever a push is made to the `main` branch.

## 🛠 Setup

### 1. Create Discord Webhook
- Go to your Discord server → open any text channel settings.
- Go to **Integrations → Webhooks → New Webhook**
- Copy the webhook URL.

### 2. Add the Webhook as a GitHub Secret
- Go to your GitHub repository → **Settings → Secrets and variables → Actions**
- Click **"New repository secret"**
  - **Name**: `DISCORD_WEBHOOK_URL`
  - **Value**: your Discord webhook URL
