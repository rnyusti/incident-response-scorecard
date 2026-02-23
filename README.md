# Incident Response Scorecard 2026

An interactive web-based scorecard for tracking and evaluating incident response performance throughout 2026.

## 🚀 Quick Start

1. **View the Scorecard**: Open `Incident_Response_Scorecard_2026.html` in your browser
2. **Read-Only Access**: Anyone can view the data without authentication
3. **Edit Access**: Connect your GitHub account to make changes

## 🔑 Authentication Setup

To edit data, you'll need a GitHub Personal Access Token:

1. Go to GitHub Settings → Developer settings → Personal access tokens → Tokens (classic)
2. Click "Generate new token (classic)"
3. Give it a name (e.g., "Incident Scorecard")
4. Select scopes: **`repo`** (Full control of private repositories)
5. Generate and copy the token
6. Click "Connect GitHub" in the scorecard and paste your token

## 📊 Features

- **Monthly Views**: Track incidents across all months of 2026
- **Pagination**: Navigate through incidents 6 at a time for comfortable viewing
- **Auto-Sync**: Authenticated users' changes automatically sync to GitHub
- **Real-time Collaboration**: All users see the same data from GitHub
- **Read-Only Mode**: Unauthenticated users can view but not edit
- **Export Options**: Download as CSV or JSON

## 🔒 Security

- Only authenticated GitHub users can modify data
- All changes are tracked with timestamps and usernames
- Data is stored in `scorecard-data.json` in this repository

## 📝 Usage

1. Select a month using the month tabs
2. Enter scores (0 or 1) for each criterion
3. For Statuspage items, select Yes/No/N/A as appropriate
4. Data auto-saves every 5 seconds when authenticated
5. Use "Save Progress" button for immediate sync

## 🎯 Scoring System

- **1 (Pass)**: Criterion met - gets 100% of weight
- **0 (Fail)**: Criterion not met - 0% score
- **N/A**: Not applicable (excluded from scoring)

Compliance levels:
- 🟢 **Excellent**: 80%+ (Green)
- 🟡 **Good**: 60-79% (Yellow)
- 🔴 **Needs Improvement**: <60% (Red)

## 🛠️ Maintenance

- Data is automatically backed up to GitHub
- Access the raw data in `scorecard-data.json`
- Historical data is preserved through Git commits

---

**Note**: This application uses GitHub as both authentication provider and data storage. Make sure your repository remains accessible to your team.
