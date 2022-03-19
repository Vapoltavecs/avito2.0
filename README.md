## 1. Стек
- vue3
- Django
- FastApi 
- PostgreSQL

## 2. Цель проекта
- Построить удобную платформу для продажи онлайн-товаров (как на funpay) между людьми, с возможностью чата и отзывов.

## 3. Описание системы
Система состоит из следующих основных функциональных блоков:
- Регистрация, аутентификация и авторизация
- Стена продуктов
- Страничка пользователя
- Чат

## 4. Типы пользователей
- Продавец
- Покупатель

## 5. Материалы
- [гитхаб проекта](https://github.com/hoopengo/avito2.0)
- [таски](https://trello.com/b/tLa3atSw/%D0%B0%D0%B2%D0%B8%D1%82%D0%BE-20)
- [телеграм](https://t.me/+RmgPB8zcBGw1N2Iy)
- [дискорд](https://discord.gg/P38ZgXGwJq)
- [дизайн](https://www.figma.com/file/EhMj6JSdAPo24TrVvxiriq/oceanplace)

## Работа сервиса
Клиент A выкладывает свой товар на наш сервис. Клиент Б выбирает его товар и нажимает кнопку "Начать сделку". Сервис уведомляет Клиента А в чате с клиентов Б о начале сделки. Клиент А подтверждает или же отклоняет её. При подтверждении Сервис предоставляет Клиенту Б реквизы Клиента А. После оплаты, Клиент Б подтверждает её, нажав на кнопку "Готово", после чего Клиент А должен подтвердить перевод денежных средст на свой счёт. После этого сервис пишет в чат заранее предоставленные данные. 
