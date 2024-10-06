# zGroup-IT тестовое задание

## Основная задача
Реализовать нижеописанный функционал, если кажется, что вы можете дополнить это тестовое другим функционалом, то будем рады увидеть ваши творческие стороны.

Возможные стеки:
1. Django DRF + PSQL
2. **FastAPI + PSQL** (выбранный) 

Endpoints:
1. /upload/ - принимает файл и имя претендента, сохраняет их
2. /delete/<>/ - удаляет резюме из базы и удаляет файл
3. /list/ - выводит пагинированный список резюме с абсолютным путем до файла резюме и именем

## EXTRA задача
Реализовать систему рейтинга для резюме проставляемого пользователем.

## Плюс балл факторы:
1. Документация написанная академическим языком
2. Чистота кода, использование максимума возможного в конкретном кейсе, функционала используемого стека
3. Заполненный и переданный APIDOG по тестовому проекту
