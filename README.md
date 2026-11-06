# 🟢 PortfolioTrackerNode — Live Portfolio Tracker (Node.js)

> Node.js port of my Angel One portfolio tracker: scheduled holdings sync with `node-cron`, MongoDB persistence and a live log stream to the browser over Socket.IO.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Angel One SmartAPI](https://img.shields.io/badge/Angel%20One%20SmartAPI-E4572E?style=flat-square)

## ✨ Features

- Angel One login via `smartapi-javascript` + `otplib` TOTP
- Cron-scheduled holdings fetch and P&L computation
- Live server-log streaming to `index.html` via WebSockets
- MongoDB upserts per client

## 🚀 Run

```bash
git clone https://github.com/optimus-node-js/PortfolioTrackerNode.git
cd PortfolioTrackerNode
```

```bash
npm install
node index.js     # open http://localhost:3000 for the live log view
```

Configure your own Angel One credentials and MongoDB URI via environment variables.

---

## 👤 Author

**Rahul Vishwakarma** — Senior Full Stack Developer · Ahmedabad, India

[![Portfolio](https://img.shields.io/badge/Portfolio-rahul--vishwakarma--portfolio.vercel.app-0A66C2?style=flat-square&logo=vercel&logoColor=white)](https://rahul-vishwakarma-portfolio.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Rahul%20Vishwakarma-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rahul-vishwakarma-101346192)
[![Email](https://img.shields.io/badge/Email-karmarahul67%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:karmarahul67@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-optimus--node--js-181717?style=flat-square&logo=github)](https://github.com/optimus-node-js)

If you find this project useful, consider giving it a ⭐.
