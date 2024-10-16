---
title: Как фонд держит монеты с разных блокчейнов в одном месте? 
subtitle: Обернутые криптомонеты
description: Обернутые криптомонеты

date: 2024-07-24 00:00:00 +/-TTTT
categories: [Образование]
tags: [обернутые-криптомонеты]     # TAG names should always be lowercase

---

## Как собрать вместе активы из разных блокченов?

Существенная доля активов фонда хранится в **нативных** криптовалютах. 
Нативные криптовалюты обеспечивают работу соответствующих
блокчейнов. Они используются для оплаты транзакционных сборов и
стимулирования участников сети (майнеры), обеспечивающих ее
безопасность.

Наиболее капитализированные и известные примеры биткоин (BTC) и Эфириум (Ethereum, ETH). 
BTC - крупнейшая и наиболее известная криптовалюта, часто
рассматриваемая как \"золотой стандарт\" цифровых валют. ETH - ведущая
платформа для децентрализованных приложений (dApps) и смарт-контрактов.

Фонд размещен на смарт-контракте в блокчейне Эфириум. Как он может хранить биткоин? Ответ - **обернутые** монеты. 

## Как работают обернутые криптовалюты?

Обернутые криптовалюты позволяют активам одной блокчейн-сети использоваться в другой. Например, Wrapped Bitcoin (WBTC) позволяет биткоину использоваться в сети Эфириум, что дает держателям BTC возможность участвовать в экосистеме децентрализованных финансов (DeFi) на Эфириум.

Обернутые монеты дают держателям активов, не связанных с Эфириум, доступ к разнообразным DeFi-приложениям, доступным в этой сети, включая и наш фонд.

## Пример: как устроен WBTC?

**Wrapped Bitcoin (WBTC)** — это токен, представляющий биткоин на блокчейне Эфириум. WBTC позволяет пользователям использовать BTC в экосистеме децентрализованных финансов (DeFi) Эфириум. Вот как он работает:


- Обертывание биткоина означает создание токена ERC-20 [^1], который поддерживается реальными биткоинами в соотношении 1:1. Каждый WBTC полностью поддержан биткоинами, находящимся у хранителей. 

[^1]: Стандарт ERC-20 определяет набор правил и требований для токенов, чтобы обеспечить их совместимость с различными платформами и смарт-контрактами на Эфириум. Стандарт упрощает процесс создания и обмена токенов, обеспечивая единый формат для всех токенов, созданных на Эфириум.

- Когда пользователи хотят получить WBTC, они отправляют свои биткоины хранителю (например, BitGo). Хранитель затем создает  (ментит, to mint) эквивалентное количество WBTC на блокчейне Эфириум и отправляет их пользователю.

- Для погашения WBTC пользователи отправляют свои WBTC обратно хранителю, который уничтожает (сжигает) эти токены и возвращает эквивалентное количество биткоинов пользователю.

- Все транзакции WBTC и биткоинов, которые его поддерживают, могут быть проверены на публичных блокчейнах Эфириум и Bitcoin.

- Хранители регулярно проходят аудит, чтобы подтвердить, что каждый WBTC поддержан реальным биткоином.


## Риски обернутых криптовалют

- **Централизация**: Обернутые криптовалюты часто зависят от централизованного органа или группы хранителей для хранения основного актива (например, биткоина). Это вводит риски централизации, такие как доверие и риски хранения.

- **Риски смарт-контрактов**: Обернутые активы управляются смарт-контрактами, которые могут быть уязвимы для ошибок, хаков или эксплойтов. Если смарт-контракт, управляющий обернутой монетой, будет скомпрометирован, это может привести к значительным потерям.

- **Риски хранения**: Организация, которая хранит основной актив, может столкнуться с операционными рисками, неплатежеспособностью или мошенничеством. Например, если хранитель биткоина для WBTC потерпит неудачу или будет взломан, стоимость WBTC может резко упасть.

- **Регуляторные риски**: Регуляторные изменения могут повлиять на законность и функционирование обернутых активов. Изменения в законодательстве, касающемся услуг хранения, законов о ценных бумагах или операций между блокчейнами, могут повлиять на стоимость и удобство использования обернутых криптомонет.

- **Рыночные риски**: Как и любая криптовалюта, обернутые монеты подвержены рыночной волатильности. Стоимость обернутого актива может значительно колебаться, влияя на его стоимость и ликвидность.

- **Риски выкупа**: Могут возникнуть проблемы с выкупом обернутых монет в их оригинальный актив. Задержки, комиссии или сложности в процессе выкупа могут представлять риски для держателей обернутых активов.

## Дополнительные материалы

[Что такое Обёрнутые токены или Wrapped Tokens? Обзор с анимацией](https://youtu.be/QvOwbMyLUyI?si=dVe8EzDYa4N0Ofwt)

