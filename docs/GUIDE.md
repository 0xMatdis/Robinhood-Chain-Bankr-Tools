# Robinhood Chain × Bankr Tools - User Guide

**Comprehensive guide to using the professional open-source toolkit for Bankr AI Agents on Robinhood Chain.**

## 📖 Table of Contents

- [Introduction](#introduction)
- [Quick Start](#quick-start)
- [Available Skills](#available-skills)
- [Installation Guide](#installation-guide)
- [Usage Examples](#usage-examples)
- [Best Practices](#best-practices)
- [Troubleshooting](#troubleshooting)
- [FAQ](#faq)

## Introduction

**Robinhood Chain × Bankr Tools** is a professional open-source collection of skills designed to empower **Bankr AI Agents** with advanced capabilities on Robinhood Chain.

The toolkit focuses on tokenized stocks (NVDA, AAPL, TSLA, etc.), cross-chain bridging, portfolio automation, yield optimization, and earnings strategies — all accessible through natural language.

## 🚀 Quick Start

1. Make sure you have an active **Bankr Agent** (via X, Telegram, or Web)
2. Install the skills you want using natural language commands
3. Start interacting with your agent

## 🛠️ Available Skills

| Skill Name                  | Description                                                      | Primary Use Case                     | Status |
|-----------------------------|------------------------------------------------------------------|--------------------------------------|--------|
| `rh-portfolio-manager`      | Intelligent portfolio rebalancing & DCA                          | Automated investing & risk control   | ✅ Ready |
| `rh-bridge-pro`             | Advanced LayerZero bridge + liquidity seeding                    | Cross-chain expansion                | ✅ Ready |
| `rh-stock-scanner`          | Real-time momentum & opportunity scanner                         | Market research & alpha hunting      | ✅ Ready |
| `rh-yield-optimizer`        | Yield optimization using tokenized stocks as collateral         | Maximizing APY on RWAs               | ✅ Ready |
| `rh-earnings-agent`         | Automated earnings plays & volatility strategies                 | Earnings season trading              | ✅ Ready |

## 🔧 Installation Guide

In your Bankr agent, simply say:

```text
install the rh-portfolio-manager skill from https://github.com/0xMatdis/Robinhood-Chain-Bankr-Tools/tree/main/skills/rh-portfolio-manager
```

You can install multiple skills by repeating the command.

## 💡 Usage Examples

### RH Portfolio Manager
- "Rebalance my portfolio to 40% NVDA, 30% AAPL, 20% TSLA on Robinhood Chain"
- "Set up weekly DCA of 150 USDC every Monday"
- "Analyze my current portfolio and suggest risk adjustments"

### RH Bridge Pro
- "Bridge 2500 USDC from Base to Robinhood Chain with liquidity"
- "Expand my token to Robinhood Chain with 8000 WETH liquidity"

### RH Stock Scanner
- "Scan strongest momentum stocks on Robinhood Chain right now"
- "Show top 5 stocks with volume spike over 200% today"

### RH Yield Optimizer
- "Optimize yield for my 15 NVDA holdings"
- "Find highest APY opportunities using tokenized stocks"

### RH Earnings Agent
- "Prepare earnings strategy for NVDA this week"
- "Show best earnings opportunities in the next 7 days"

## Best Practices

- Start with small amounts when testing new automations
- Be specific in prompts (include amounts, percentages, and frequency)
- Always review transaction details before confirming
- Regularly update your installed skills
- Combine multiple skills for powerful strategies

## Troubleshooting

- **Skill not found** → Ensure you copied the full GitHub link correctly
- **Command not working** → Use more natural and detailed prompts
- **Bridge failed** → Check gas balance and try a smaller amount first
- **Transaction rejected** → Review slippage and gas settings in Bankr

## ❓ FAQ

**Q: Is this free to use?**  
A: Yes, completely free under MIT License.

**Q: Can I use these skills on other chains?**  
A: Primarily built for Robinhood Chain. Some skills support Base for bridging.

**Q: How do I create my own skill?**  
A: Use the [Skill Template](SKILL_TEMPLATE.md) and follow [CONTRIBUTING.md](CONTRIBUTING.md).

**Q: Are these skills safe?**  
A: Skills only execute what you instruct. Always double-check transactions.

---

**Made for the Bankr & Robinhood Chain ecosystem**

Built by [0xMatdis](https://x.com/0xmatdis)  
Contributions welcome!

```
