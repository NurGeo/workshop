# Зарегестрировать новую мастерскую
## История
Я как потенциальный владелец будущей мастерской хочу зарегестрировать новую "Мастерскую", чтобы оказывать услуги "Мастерской для души" для потенциальных клиентов.

## Действия
1. Нахожу в telegram бота `@soul_workshop_service_bot`
2. Набираю команду `/register_workshop`
3. Ввожу сообщение в ответ на приглашение: "Введите наименование города где будет находиться ваша мастерская".
4. Ввожу сообщение в ответ на приглашение: "Введите наименование мастерской чтобы клиенты могли опознавать вашу мастерскую из списка мастерских. Например: 'На тверской' или 'На динамо'."
5. Ввожу сообщение в ответ на приглашение: "Введите адрес мастерской, чтобы клиенты могли найти вашу мастерскую".
6. Ввожу сообщение в ответ на приглашение: "Введите свое имя, чтобы мы знали как к вам обращаться".

## Условия
**Предусловия: **
- нет

**Постусловия:**
- мастерская с таким именем в данном городе не должен быть зарегистрирован ранее;

## Альтернативные сценарии
- шаг 6 не выполняется, если пользователь с таким telegramId уже зарегестрирован в системе как владелец мастерской;

## Результат
**Система:**
- В системе появилась новая заявка на регистрацию мастерской;
- Всем пользователям техподдержки приходит сообщение о новой заявке;
- Для техподдержки по заявке становится доступна пользовательская история "Одобрение регистрации мастерской"

**Пользователь:**
- Получает сообщение: "Ваша заявка под номером `<<номер_заявки>>` для регистрации новой мастерской для города <<имя_города>> принята.\n\nОтвет по вашей заявке будет предоставлена позже, после обработки вашей заявки.";
