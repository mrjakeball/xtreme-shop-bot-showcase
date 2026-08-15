<p align="center">
  <img src="./assets/header.svg" alt="X-TREME Shop Bot" width="100%" />
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/РУССКИЙ-8B5CF6?style=for-the-badge" alt="Русский" height="29" /></a>
  &nbsp;
  <a href="./README_EN.md"><img src="https://img.shields.io/badge/ENGLISH-21262D?style=for-the-badge" alt="English" height="29" /></a>
</p>

<p align="center">
  <a href="https://t.me/XtremeShopBot"><img src="https://img.shields.io/badge/✈_ОТКРЫТЬ_БОТА-8B5CF6?style=for-the-badge&logo=telegram&logoColor=white" alt="Открыть бота" height="27" /></a>
  <a href="https://github.com/mrjakeball/portfolio"><img src="https://img.shields.io/badge/📚_ВСЕ_ПРОЕКТЫ-21262D?style=for-the-badge" alt="Все проекты" height="27" /></a>
  <a href="https://github.com/mrjakeball"><img src="https://img.shields.io/badge/↩_ПРОФИЛЬ-21262D?style=for-the-badge&logo=github&logoColor=white" alt="Профиль" height="27" /></a>
</p>

---

# 📦 X-TREME Shop Bot

> **Telegram-бот для предварительного расчёта и оформления заказов с китайских торговых платформ.**

<p>
  <img src="https://img.shields.io/badge/Python_3.11-21262D?style=flat-square&logo=python&logoColor=8B5CF6" alt="Python" />
  <img src="https://img.shields.io/badge/aiogram_3-21262D?style=flat-square&logo=telegram&logoColor=26A5E4" alt="aiogram" />
  <img src="https://img.shields.io/badge/SQLite-21262D?style=flat-square&logo=sqlite&logoColor=58A6FF" alt="SQLite" />
  <img src="https://img.shields.io/badge/Pillow-21262D?style=flat-square&logo=python&logoColor=8B5CF6" alt="Pillow" />
  <img src="https://img.shields.io/badge/HMAC-21262D?style=flat-square&logo=letsencrypt&logoColor=58A6FF" alt="HMAC" />
</p>

> ⚠️ Независимый проект. Он не связан с Poizon, Taobao или их владельцами и не является официальным сервисом этих платформ.

## 🎯 Задача проекта

Убрать ручной хаос из оформления заказа.

Пользователь последовательно указывает товар и параметры, получает расчёт, подтверждает данные и передаёт оператору уже структурированную заявку.

## 📌 Коротко

| | |
| :--- | :--- |
| 🤖 **Формат** | Telegram-бот |
| 🚦 **Статус** | Доступен |
| ✈️ **Бот** | [@XtremeShopBot ↗](https://t.me/XtremeShopBot) |
| 🧠 **Логика** | FSM-сценарии |
| 🗄️ **Хранение** | SQLite |
| 🔒 **Исходники** | Приватные; здесь публичная витрина |

## 🖼️ Интерфейс и материалы

<p align="center">
  <a href="./assets/screen-details.jpg"><img src="./assets/screen-details.jpg" alt="Заполнение данных товара" width="420" /></a>
</p>

<p align="center">
  <a href="./assets/screen-calculation.jpg"><img src="./assets/screen-calculation.jpg" alt="Расчёт стоимости заказа" width="420" /></a>
</p>

> 🖼️ Галерея содержит промо- и инструкционные материалы бота. Личные диалоги и реальные заказы пользователей здесь не публикуются.

## 🧭 Маршрут заказа

1. 🔗 пользователь отправляет ссылку на товар;
2. 📐 указывает необходимые параметры;
3. 🖼️ при необходимости добавляет изображения;
4. 🧮 бот рассчитывает стоимость, доставку и комиссии;
5. ✅ пользователь подтверждает заказ;
6. 📦 оператор получает структурированную заявку.

## ⚙️ Что реализовано

- пошаговые FSM-сценарии;
- работа с несколькими товарами;
- сбор ссылок и характеристик;
- расчёт доставки и комиссий;
- временная PNG-сводка;
- передача сформированной заявки в поддержку.

## 🔐 Целостность и состояние

### 🗄️ SQLite

Состояние длинных пользовательских сценариев не должно теряться между отдельными шагами диалога.

### 🔏 HMAC

Подпись используется для проверки целостности данных, связанных с QR-ссылками.

### 🧹 Публичная витрина

Реальные пользовательские данные, заявки и приватный исходный код в showcase-репозиторий не включены.

---

<p align="center">
  <a href="https://t.me/XtremeShopBot"><img src="https://img.shields.io/badge/✈_ОТКРЫТЬ_X--TREME_SHOP_BOT-8B5CF6?style=for-the-badge&logo=telegram&logoColor=white" alt="Открыть X-TREME Shop Bot" height="30" /></a>
</p>

<p align="center">
  <a href="https://github.com/mrjakeball/portfolio"><strong>← Каталог проектов</strong></a>
  &nbsp;·&nbsp;
  <a href="https://github.com/mrjakeball"><strong>Профиль GitHub ↑</strong></a>
</p>
