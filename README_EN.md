<p align="center">
  <img src="./assets/header.svg" alt="X-TREME Shop Bot" width="100%" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/РУССКИЙ-21262D?style=for-the-badge" alt="Русский" height="29" /></a>
  &nbsp;
  <a href="./README_EN.md"><img src="https://img.shields.io/badge/ENGLISH-8B5CF6?style=for-the-badge" alt="English" height="29" /></a>
</p>

<p align="center">
  <a href="https://t.me/XtremeShopBot"><img src="https://img.shields.io/badge/✈_OPEN_BOT-8B5CF6?style=for-the-badge&logo=telegram&logoColor=white" alt="Open bot" height="27" /></a>
  <a href="https://github.com/mrjakeball/portfolio/blob/main/README_EN.md"><img src="https://img.shields.io/badge/📚_ALL_PROJECTS-21262D?style=for-the-badge" alt="All projects" height="27" /></a>
  <a href="https://github.com/mrjakeball"><img src="https://img.shields.io/badge/↩_PROFILE-21262D?style=for-the-badge&logo=github&logoColor=white" alt="Profile" height="27" /></a>
</p>

---

# 📦 X-TREME Shop Bot

> **A Telegram bot for preliminary order calculation and structured requests from Chinese commerce platforms.**

<p>
  <img src="https://img.shields.io/badge/Python_3.11-21262D?style=flat-square&logo=python&logoColor=8B5CF6" alt="Python" />
  <img src="https://img.shields.io/badge/aiogram_3-21262D?style=flat-square&logo=telegram&logoColor=26A5E4" alt="aiogram" />
  <img src="https://img.shields.io/badge/SQLite-21262D?style=flat-square&logo=sqlite&logoColor=58A6FF" alt="SQLite" />
  <img src="https://img.shields.io/badge/Pillow-21262D?style=flat-square&logo=python&logoColor=8B5CF6" alt="Pillow" />
  <img src="https://img.shields.io/badge/HMAC-21262D?style=flat-square&logo=letsencrypt&logoColor=58A6FF" alt="HMAC" />
</p>

> ⚠️ Independent project. It is not affiliated with Poizon, Taobao or their owners and is not an official service of either platform.

## 🎯 Project goal

Reduce manual work during order preparation.

A user moves through a clear sequence: product information, parameters, calculation, confirmation and a structured request for the operator.

## 📌 At a glance

| | |
| :--- | :--- |
| 🤖 **Format** | Telegram bot |
| 🚦 **Status** | Available |
| ✈️ **Bot** | [@XtremeShopBot ↗](https://t.me/XtremeShopBot) |
| 🧠 **Flow** | FSM scenarios |
| 🗄️ **Storage** | SQLite |
| 🔒 **Source code** | Private; this repository is a public showcase |

## 🖼️ Interface and materials

<p align="center">
  <a href="./assets/screen-details.jpg"><img src="./assets/screen-details.jpg" alt="Product details flow" width="420" /></a>
</p>

<p align="center">
  <a href="./assets/screen-calculation.jpg"><img src="./assets/screen-calculation.jpg" alt="Order calculation" width="420" /></a>
</p>

> 🖼️ The gallery contains promotional and instructional material used by the bot. Private conversations and real customer orders are not published here.

## 🧭 Order flow

1. 🔗 the user sends a product link;
2. 📐 product parameters are entered;
3. 🖼️ supporting images can be added;
4. 🧮 the bot calculates price, delivery and fees;
5. ✅ the user confirms the request;
6. 📦 the operator receives structured order data.

## ⚙️ Implemented

- step-by-step FSM flows;
- multi-item scenarios;
- product link and parameter collection;
- delivery and fee calculations;
- temporary PNG summary;
- structured hand-off to support.

## 🔐 State and integrity

### 🗄️ SQLite

Long conversational flows need to preserve state reliably between separate interaction steps.

### 🔏 HMAC

Signatures are used to verify the integrity of data connected with QR links.

### 🧹 Public showcase

Real user data, orders and private application source code are not included in this repository.

---

<p align="center">
  <a href="https://t.me/XtremeShopBot"><img src="https://img.shields.io/badge/✈_OPEN_X--TREME_SHOP_BOT-8B5CF6?style=for-the-badge&logo=telegram&logoColor=white" alt="Open X-TREME Shop Bot" height="30" /></a>
</p>

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio/blob/main/README_EN.md"><strong>← Project directory</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/mrjakeball"><strong>GitHub profile ↑</strong></a>
</p>
