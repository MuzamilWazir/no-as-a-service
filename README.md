Here is the full, raw Markdown code for your GitHub `README.md`. I have optimized the layout, fixed the broken links, and kept that stubborn, rebellious energy you wanted.

```markdown
# ❌ No-as-a-Service (NaaS)

<p align="center">
  <img src="https://raw.githubusercontent.com/hotheadhacker/no-as-a-service/main/assets/imgs/naas-with-no-logo-bunny.png" width="800" alt="No-as-a-Service Banner" style="max-width: 100%;"/>
</p>

<p align="center">
  <strong>"Because 'Yes' is a bug, not a feature."</strong>
</p>

---

Ever needed a graceful way to say “no”?  
This tiny API returns random, generic, creative, and sometimes hilarious rejection reasons. It's perfectly suited for any scenario: personal life, professional avoidance, dev life, or just because you don't feel like it.

**Built for humans, excuses, and the art of being unbothered.**

<p align="center">
  <a href="https://docs.gitads.dev/">
    <img src="https://gitads.dev/assets/images/sponsor/camos/camo-3.png" alt="Sponsored by GitAds" />
  </a>
</p>

<p align="center">
  This project is <strong>grudgingly sponsored by <a href="https://docs.gitads.dev/docs/getting-started/publishers">GitAds</a></strong>.<br>
  You can get your GitHub repository sponsored too — <a href="https://docs.gitads.dev/docs/getting-started/publishers">create your account now</a>.
</p>

---

## 🚀 API Usage

**Base URL**
```text
[https://naas.isalman.dev/no](https://naas.isalman.dev/no)

```

| Detail | Specification |
| --- | --- |
| **Method** | `GET` |
| **Rate Limit** | `120 Requests / min / IP` (Don't be needy) |
| **Format** | `JSON` |

### 🔄 Example Request

```http
GET /no

```

### ✅ Example Response

```json
{
  "reason": "This feels like something Future Me would yell at Present Me for agreeing to."
}

```

Use it in apps, bots, Slack integrations, rejection letters, or wherever you need a polite (or witty) way to decline.

---

## 🛠️ Self-Hosting

Want to run it yourself? It’s lightweight, fast, and highly dismissive.

### 1. Clone this repository

```bash
git clone [https://github.com/hotheadhacker/no-as-a-service.git](https://github.com/hotheadhacker/no-as-a-service.git)
cd no-as-a-service

```

### 2. Install dependencies

```bash
npm install

```

### 3. Start the server

```bash
npm start

```

The API will be live at: `http://localhost:3000/no`

*Pro tip: Change the port using an environment variable:*

```bash
PORT=5000 npm start

```

---

## 📁 Project Structure

```bash
no-as-service/
├── index.js          # The Rejection Engine (Express API)
├── reasons.json      # 1000+ universal rejection reasons (The Attitude)
├── package.json      # Dependencies and scripts
├── .devcontainer.json # VS Code / Github devcontainer setup
└── README.md         # This document. Stop reading it.

```

---

## ⚓ Devcontainer

If you open this repo in **GitHub Codespaces**, it will automatically use `.devcontainer.json` to set up your environment. If you're using **VS Code**, it will prompt you to reopen the project in a container. It’s the fastest way to start saying no.

---

## 🌍 The "No" Ecosystem

These brave souls have integrated **NaaS** into their own projects. Check them out:

1. **[no-as-a-service-rust](https://github.com/ZAZPRO/no-as-a-service-rust)** - Rust implementation for memory-safe rejections.
2. **[No as a Service - Raycast Extension](https://www.raycast.com/nedini/no-as-a-service)** - Get a random "No" directly from your Mac launcher.
3. **[FunnyAnswers](https://www.funnyanswers.lol/no)** - A humor-focused API playground.
4. **[NoAsAnApp](https://github.com/omar-jarid/NoAsAnApp)** - A native Android app for on-the-go avoidance.
5. **[CSG Admins](https://csg-admins.de)** - System administration hub using NaaS for playful admin responses.
6. **[How About No?](https://github.com/lloyd094/How-About-No-)** - A Docker-ready GUI for NaaS.
7. **[no-as-a-service-asp](https://github.com/sapph42/no-as-a-service)** - An implementation in ASP.NET Core.

> **Your Project Here?** If you're using NaaS in your project, open a pull request. I might say yes to adding it.

---

## 👤 Author

Created with creative stubbornness by **[hotheadhacker](https://github.com/hotheadhacker)**.

## 📄 License

**MIT** — Do whatever you want, just don’t say "yes" when you should say "no".

```

Would you like me to generate 10 more "Hacker-Tier" rejection reasons to add to your `reasons.json`?

```
