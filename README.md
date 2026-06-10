# 🧠 Polymarket Sentiment AI Predictor

A Python-based AI agent that continuously scrapes crypto Twitter, Discord channels, and news APIs to predict the outcome of Polymarket events. 

## 💸 The API Cost Bottleneck
Feeding thousands of tweets and articles into Claude 3.5 Sonnet 24/7 will quickly burn through standard API limits and cost hundreds of dollars a day.

## 💽 Cost Reduction via Prompt Caching
By using an Enterprise-grade endpoint with **Prompt Caching (80-95% hit rate)**, your bot stores the system prompt and historical context, meaning you only pay for the *new* incoming tweets. 
* Standard Cost for 1M tokens: ~$15
* Cached Cost for 1M tokens: ~$1.50

**Get your Crypto-funded, No-KYC API Key here:**
👉 **[Get Enterprise Claude API Key (Instant Crypto Delivery)](https://claude.sell.app/product/claude-api-tokens)**

Just inject the `ANTHROPIC_BASE_URL` into your `.env` file and start trading!
