---
title: "Quickstart"
description: "Get up and running with Gigue in under 5 minutes"
---

Welcome to Gigue. This guide will walk you through the initial setup to get your multiplayer AI workspace fully operational.

## 1. Sign In
Navigate to [demo.gigue.app](https://demo.gigue.app/) and click **"Sign In With Google"**. Follow the prompts to create your account.

## 2. Connect Your Core Tools
Gigue needs access to your communication and data tools to provide intelligent insights. Navigate to the **Connections** tab to link your accounts:

- **Connect Slack**: Toggle Slack and follow the authorization flow.
- **Connect Gmail**: Toggle Gmail and click **Connect Account**.
  - *Note: If you see a "Google hasn't verified this app" warning, click **Advanced** and then **"Go to Gigue (unsafe)"** to proceed.*
- **Connect Google Calendar**: Click **Connect** next to Google Calendar to sync your schedule.
- **Connect Google Drive**: Ensure your Drive is connected to allow AI agents to reference your documents.

## 3. Sync & Ingest (Beta/Alpha Users)
If you are part of our closed alpha, you may need to manually trigger the initial data sync in the **Back Office** panel:
1. Navigate to the **Back Office** section.
2. Under **Sync Channels**, select Gmail and click **Run**.
3. Under **Ingest Messages**, select Gmail and click **Run** to process the data.
4. Use **Group Conversations** and **Generate Workstreams** to let Gigue's AI organize your data.

## 4. Explore Your Workspace
Once your data is synced, use the left sidebar and top navigation to explore:

- **Home (Daily Briefing)**: Your central hub. See AI-generated briefings on your day, upcoming meetings, and extracted action items.
- **Conversations**: View your multi-channel messages (Slack/Gmail) grouped by account or topic.
- **Workstreams**: Track specific deals or projects. Gigue automatically extracts tasks and updates from your conversations and links them here.
- **Unified Search (Cmd + K)**: Instantly find any message, document, or contact across all connected platforms.

---

### Need Help?
- [Detailed OAuth Setup Guide](/docs/setup/google-oauth)
- [Managing AI Agents](/docs/agents/setup)
- [Join our Slack Community](https://gigue.ai/community)
