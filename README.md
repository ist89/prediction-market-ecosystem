# 📊 Prediction Market Ecosystem Directory

A **community-led directory** of all prediction market projects, tools, and protocols in the ecosystem.

🌐 **View the live directory:** [predictiondesk.xyz/ecosystem](https://predictiondesk.xyz/ecosystem)

---

## 🎯 What is this?

This is an open, community-maintained directory of projects building in the prediction markets space. Our goal is to help users discover tools, platforms, and services across the ecosystem—from trading terminals to analytics dashboards to DeFi protocols.

**Categories include:**

- 🏛️ Platforms (Polymarket, Kalshi, etc.)
- 📊 Analytics Tools
- 🤖 AI Agents
- 💬 Telegram Bots
- 💰 DeFi Protocols
- 📱 Mobile Apps
- 🔧 Trade Terminals
- 📡 Data Infrastructure
- And more...

---

## ➕ Add Your Project

Want to get your project featured? Submit a Pull Request!

### Step 1: Fork the Repository

Fork this repository to your GitHub account.

### Step 2: Edit the ecosystem.json file

Add your project to the `ecosystem.json` file.

Add a new entry to the `items` array with the following structure:

```json
{
  "key": "your-project-key",
  "name": "Your Project Name",
  "url": "https://your-project-url.com/",
  "description": "A clear, concise description of what your project does (1-2 sentences).",
  "tags": ["Category1", "Category2"],
  "supportedPlatforms": ["polymarket", "kalshi"],
  "imageUrl": "https://your-logo-url.com/logo.png",
  "heroImageUrl": "https://your-banner-image-url.com/banner.png",
  "twitterXUrl": "https://x.com/yourhandle",
  "discordUrl": "https://discord.gg/yourinvite",
  "telegramUrl": "https://t.me/yourchannel"
}
```

### Field Descriptions

| Field                | Required | Description                                                   |
| -------------------- | -------- | ------------------------------------------------------------- |
| `key`                | ✅ Yes   | Unique identifier (lowercase, hyphenated, e.g., `my-project`) |
| `name`               | ✅ Yes   | Display name of your project                                  |
| `url`                | ✅ Yes   | Main website URL                                              |
| `description`        | ✅ Yes   | Brief description (max ~200 characters recommended)           |
| `tags`               | ✅ Yes   | Array of categories (see available tags below)                |
| `supportedPlatforms` | ❌ No    | Prediction markets your tool supports                         |
| `imageUrl`           | ✅ Yes   | Square logo URL (400x400px recommended)                       |
| `heroImageUrl`       | ❌ No    | Banner image for detail page                                  |
| `twitterXUrl`        | ❌ No    | X (Twitter) profile URL                                       |
| `discordUrl`         | ❌ No    | Discord invite link                                           |
| `telegramUrl`        | ❌ No    | Telegram channel/group link                                   |

### Available Tags

Choose one or more tags that best describe your project:

- `Platform` - Prediction market exchanges
- `Trade Terminal` - Trading interfaces and terminals
- `Analytics Tools` - Data analytics and insights
- `AI Agents` - AI-powered trading or analysis tools
- `Telegram Bot` - Telegram-based tools
- `DeFi` - DeFi protocols (lending, yield, etc.)
- `Data Infra` - Data infrastructure and APIs
- `Mobile Trading App` - Mobile applications
- `Community` - Community tools and resources
- `Trade Tools` - Trade tools

### Supported Platforms

If your tool integrates with specific prediction markets, include them. Some examples of platforms are:

- `polymarket`
- `kalshi`
- `opinion`
- `predict`
- `limitless`
- `manifold`
- `myriad`

### Step 3: Submit a Pull Request

1. Commit your changes with a clear message (e.g., `Add [Project Name] to ecosystem`)
2. Push to your fork
3. Open a Pull Request to this repository
4. We'll review and merge it!

---

## ✏️ Make Corrections or Suggestions

Found incorrect information? Want to suggest an update?

### Option 1: Open a Pull Request

Follow the same steps above, but edit the existing entry instead of adding a new one.

### Option 2: Open an Issue

If you're not comfortable with PRs, [open an issue](https://github.com/predictiondesk/predictiondesk/issues/new) with:

- The project name
- What needs to be corrected
- The correct information

---

## 📋 Guidelines

To maintain quality, please ensure:

1. **Your project is live** - Only submit projects that are publicly accessible
2. **Accurate information** - Double-check all URLs and descriptions
3. **Appropriate category** - Choose tags that accurately represent your project
4. **No duplicates** - Check if your project is already listed
5. **Clear description** - Write a helpful, non-promotional description

---

## 🤝 Contributing

This directory is maintained by the community for the community. We welcome all contributions!

- **Add projects** - Help us grow the directory
- **Fix errors** - Spot something wrong? Fix it!
- **Improve descriptions** - Make entries more helpful
- **Suggest categories** - Need a new tag? Let us know!

---

## 📬 Contact

Questions? Reach out:

- Twitter/X: [@PredictionDeskX](https://x.com/predictiondeskx)
- Website: [predictiondesk.xyz](https://predictiondesk.xyz)

---

**Together, let's build the most comprehensive prediction market ecosystem directory!** 🚀
