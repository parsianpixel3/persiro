<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=persiro%20Gateway&fontSize=60&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Multi-Protocol%20Management%20Panel&descAlignY=58&descSize=18" width="100%"/>

<a href="#-english"><img src="https://img.shields.io/badge/🇬🇧-English-0f2027?style=for-the-badge" /></a>
<a href="#-فارسی"><img src="https://img.shields.io/badge/🇮🇷-فارسی-203a43?style=for-the-badge" /></a>

<br/>


<br/>

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![FastAPI](https://img.shields.io/badge/FastAPI-Async-009688?style=for-the-badge&logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com)
[![Railway](https://img.shields.io/badge/Deploy-Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white)](https://railway.app)
[![License](https://img.shields.io/badge/License-Custom-red?style=for-the-badge)](./LICENSE)

![Stars](https://img.shields.io/github/stars/arvin341az-glitch/RVG?style=social)
![Forks](https://img.shields.io/github/forks/arvin341az-glitch/RVG?style=social)
![Last Commit](https://img.shields.io/github/last-commit/arvin341az-glitch/RVG?color=2c5364)
![Repo Size](https://img.shields.io/github/repo-size/arvin341az-glitch/RVG?color=0f2027)

</div>

<br/>

---

<div align="center">
<h1>🇬🇧 English</h1>
</div>

## 📖 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Supported Protocols](#-supported-protocols)
- [Architecture](#-architecture)
- [Project Structure](#-project-structure)
- [Quick Start (Railway)](#-quick-start-railway-deploy)
- [Local Development](#-local-development)
- [Environment Variables](#-environment-variables)
- [Dashboard Preview](#-dashboard-preview)
- [Roadmap](#-roadmap)
- [Contributing](#-contributing)
- [License](#-license)
- [Support the Project](#-support-the-project)

<br/>

## 🚀 Overview

**persiro Gateway** is a fast, modern, self-hosted **multi-protocol management panel**, built with **Python + FastAPI**, designed to deploy in minutes on **Railway**.

It gives you a beautiful admin dashboard to create, monitor, and manage  links across multiple protocols — with per-link traffic quotas, live connection stats, and QR code generation — all from a single lightweight service.

> 💡 Originally built around a simple perstro has evolved into a full multi-protocol gateway with authentication, quota tracking, and a polished management UI.

<br/>

## ✨ Features

<table>
<tr>
<td width="50%">

### 🔌 Core Gateway


</td>
<td width="50%">

### 📊 Management Dashboard


</td>
</tr>
<tr>
<td width="50%">

### 🛡️ Security & Reliability


</td>
<td width="50%">

### 🤖 Automation


</td>
</tr>
</table>

<br/>

## 🌐 Supported Protocols



<br/>

## 🏗️ Architecture


<br/>

## 📂 Project Structure

```

<br/>


<table>
<tr>
<td width="60px" align="center">1️⃣</td>
<td>

**Fork this repository**


```

</td>
</tr>
<tr>
<td align="center">2️⃣</td>
<td>

**Deploy on Railway**

1. Go to [Railway.app](https://railway.app)
2. Click **New Project → Deploy from GitHub repo**
3. Select your forked repository
4. Railway auto-builds and deploys 🎉

</td>
</tr>
<tr>
<td align="center">3️⃣</td>
<td>

**Enable a public domain**

Railway → Settings → Networking → **Generate Domain**
(this sets `RAILWAY_PUBLIC_DOMAIN` automatically)

</td>
</tr>
<tr>
<td align="center">4️⃣</td>
<td>

**Open your dashboard**

```
https://your-app.up.railway.app/dashboard
```



</td>
</tr>
</table>

<br/>

## 💻 Local Development

```bash
# Clone your fork
git clone https://github.com/<your-username>/persiro.git
cd persiro

# Create a virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the server
python main.py
```

The dashboard will be available at `http://localhost:8000/dashboard`.

<br/>

## ⚙️ Environment Variables

| Variable | Description | Default |
|---|---|---|
| `PORT` | Port the service runs on | `8000` |
| `SECRET_KEY` | Internal security key | Randomly generated |
| `RAILWAY_PUBLIC_DOMAIN` | Public Railway domain (auto-set) | `localhost` |

<br/>

## 📸 Dashboard Preview

<div align="center">

> Traffic overview • Live connections • Link manager • QR export

<img src="https://img.shields.io/badge/📊_Traffic_Charts-live-2c5364?style=for-the-badge" />
<img src="https://img.shields.io/badge/🔗_Link_Manager-unlimited-203a43?style=for-the-badge" />
<img src="https://img.shields.io/badge/📱_QR_Export-per_link-0f2027?style=for-the-badge" />

</div>

<br/>

## 🗺️ Roadmap


<br/>

## 🤝 Contributing

Pull requests are welcome for bug fixes, optimizations, and documentation.
> ⚠️ Please read the [LICENSE](./LICENSE) before contributing — modification and redistribution of modified versions is restricted. Open an issue first if you'd like to discuss a change.

<br/>

## 📄 License

This project is distributed under a **custom license**:
✅ Free to use, deploy, and fork
❌ Modifying and redistributing a modified version is **not permitted**

See the full [LICENSE](./LICENSE) file for details.

<br/>

## ❤️ Support the Project

If this project helped you, consider supporting its development:

<div align="center">




</div>

<br/>

---

<br/>

<div align="center" dir="rtl">
<h1>🇮🇷 فارسی</h1>
</div>

## 📖 فهرست مطالب

- [معرفی](#-معرفی)
- [ویژگی‌ها](#-ویژگیها)
- [پروتکل‌های پشتیبانی‌شده](#-پروتکلهای-پشتیبانیشده)
- [معماری](#-معماری)
- [ساختار پروژه](#-ساختار-پروژه)
- [شروع سریع (دیپلوی روی Railway)](#-شروع-سریع-دیپلوی-روی-railway)
- [توسعه محلی](#-توسعه-محلی)
- [متغیرهای محیطی](#-متغیرهای-محیطی)
- [نقشه راه](#-نقشه-راه)
- [مشارکت](#-مشارکت)
- [لایسنس](#-لایسنس)
- [حمایت از پروژه](#-حمایت-از-پروژه)

<br/>

##
</div>

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" width="100%"/>
