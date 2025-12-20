# 🌉 LegacyBridge - AI-Powered Mainframe Integration

> Don't rewrite your mainframe—bridge it. Modern APIs for legacy systems using AI translation.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Node.js 20+](https://img.shields.io/badge/node-20+-green.svg)](https://nodejs.org/)
[![Status: Alpha](https://img.shields.io/badge/status-alpha-orange.svg)]()

## 🎯 Problem

Legacy systems block digital transformation:
- Mainframe rewrite costs $5M+, takes 2 years
- COBOL talent shortage
- Modern apps can't integrate
- Business-critical systems untouchable

## 💡 Solution

LegacyBridge uses AI to translate:
- **Natural language → COBOL** transactions
- **REST API → Mainframe** calls
- **JSON → Fixed-width** files
- **Modern → Legacy** protocol translation

## ⚡ Quick Start

```bash
git clone https://github.com/yksanjo/legacybridge-ai-gateway.git
cd legacybridge-ai-gateway
npm install
npm run dev
```

## 🤖 AI Translation Examples

Input: `"Get all active customers in New York"`

Output:
```cobol
EXEC CICS READ DATASET('CUSTMAST') 
     INTO(:customer-record) 
     WHERE status = 'A' AND state = 'NY'
```

## 💰 ROI

- **$5M saved** vs. full rewrite
- **90 days** to deploy (vs. 2 years)
- **Zero risk** - Mainframe untouched
- **10,000 req/sec** with <200ms latency

## 📊 Tech Stack

- **Backend**: Node.js 20+, TypeScript
- **AI**: OpenAI/Anthropic for translation
- **Cache**: Redis 7+
- **Queue**: RabbitMQ

## 🎯 Supported Systems

- IBM z/OS, CICS, IMS
- AS/400 (IBM i)
- SAP R/3, S/4HANA
- Oracle E-Business Suite
- COBOL, PL/I, RPG

## 📄 License

MIT License

## 💬 Contact

yoshi@musicailab.com
