<p>
<a href="README.md"><img src="https://raw.githubusercontent.com/mrjakeball/mrjakeball/main/assets/ui/ru-on.svg" height="32" alt="Русский · выбран"></a>
<a href="README_EN.md"><img src="https://raw.githubusercontent.com/mrjakeball/mrjakeball/main/assets/ui/en-off.svg" height="32" alt="English"></a>
<a href="https://github.com/mrjakeball/portfolio"><img src="https://raw.githubusercontent.com/mrjakeball/mrjakeball/main/assets/ui/catalog-ru.svg" height="32" alt="Каталог проектов"></a>
</p>

# X-TREME Shop Bot

Бот оформляет заявку на покупку с Poizon или Taobao. Покупатель передаёт ссылки и параметры товаров, видит предварительный расчёт и подтверждает состав заказа перед передачей оператору.

![Публичные инструкции](assets/social-preview.jpg)

[Открыть бота ↗](https://t.me/XtremeShopBot)

Опубликован в Telegram · Публичная витрина приватного проекта  
Python 3.11 · aiogram 3 · SQLite · Pillow

## Как заявка доходит до оператора

1. **Товар.** Бот собирает ссылку, характеристики и при необходимости изображения. В одну заявку можно добавить несколько товаров.
2. **Расчёт.** Клиент видит доставку и комиссии до подтверждения. Бот формирует временную PNG-сводку.
3. **Передача.** Оператор получает структурированную заявку. Состояния диалога организованы через FSM, данные хранятся в SQLite. Для проверки целостности QR-ссылок используется HMAC.

В галерее опубликованы инструкции бота. Проект независим от торговых площадок.

## Что видит покупатель до подтверждения

**[Детали товара](assets/screen-details.jpg)** · Инструкция показывает, какие сведения приложить к ссылке. Это помогает оператору различать варианты одного товара.

**[Как считается итог](assets/screen-calculation.jpg)** · Вторая памятка объясняет составляющие предварительной суммы. Её можно открыть отдельно и сверить расчёт до передачи заявки.

<details>
<summary>Развернуть галерею</summary>

<a href="assets/screen-details.jpg"><img src="assets/screen-details.jpg" width="560" alt="Инструкция по параметрам товара"></a>
<a href="assets/screen-calculation.jpg"><img src="assets/screen-calculation.jpg" width="560" alt="Инструкция по расчёту"></a>

</details>

[Примечание о проекте](NOTICE.md) · [Профиль](https://github.com/mrjakeball) · [Каталог проектов](https://github.com/mrjakeball/portfolio)
