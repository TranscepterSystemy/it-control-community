# ИТ.Контроль Community RC1

Локальная система учёта оборудования и инвентаризации для Windows с Docker Desktop.

[Скачать RC1](releases/ITControl_Community_RC1.zip?raw=true) · [SHA-256](releases/ITControl_Community_RC1.zip.sha256)

Версия 2.0.0-RC1. Кандидат для тестирования с исправленной аутентификацией и подбором свободного порта Windows.

Распакуй ZIP и запусти START.cmd. Первый запуск предлагает создать пароль администратора. Инструкция по новой установке и обновлению находится в docs/QUICK_START_RC1.md внутри архива.

При обновлении сохрани .env, папку updates, пользовательские фоны карт и существующий том PostgreSQL. Предварительно сделай резервную копию базы.

Проверены приложение на Windows и Linux, подготовка запуска через cmd.exe и Windows PowerShell 5.1, Chromium и Docker с PostgreSQL. Эмиль подтвердил запуск на своей Windows и разрешил раздачу RC1.

Условия использования находятся в LICENSE.txt.
