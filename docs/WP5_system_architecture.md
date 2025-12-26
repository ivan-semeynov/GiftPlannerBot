# System Architecture

## Общая архитектура
Система реализована по модульному принципу.

Компоненты:
- Telegram Bot (aiogram)
- FSM диалогов
- ML Recommendation Engine
- Database
- ML Artifacts Storage

## Логическая схема
Пользователь → Telegram → FSM → Recommender → ML Model + DB → Ответ
