# Выбрать мастерскую
## История
Я как клиент сервиса "Мастерская для души" хочу выбрать мастерскую, чтобы дальше пользоваться сервисом данной мастерской.

## Действия
1. Нахожу в telegram бота `@soul_workshop_bot`
2. Набираю команду `/start`
3. Выбираю кнопку "Выбрать мастерскую"
4. Из списка нажимаю кнопку с той мастерской которая мне нужна
5. Нажимаю кнопку "Сделать текущим"

## Условия
**Предусловия: **
- нет

**Постусловия:**
- пользователь должен быть зарегистрирован как клиент

## Альтернативные сценарии
2.1 Шаги 2, 3 можно выполнить за раз набрав команду /select_workshop;  
3.1 Начиная с шага 3 могу отменить выбор мастерской нажав на кнопку "Отменить";  
4.1 Могу нажать кнопку "Изменить город";  
- Из списка выбираю город и продолжаю с шага 4;

4.2 Могу нажать кнопку "Далее...", если все мастерские города не поместились в один список;  
5.1 Могу нажать кнопку "Детали", чтобы посмотреть подробную информацию о мастерской;
- На сообщении с деталями мастерской нажимаю кнопку "Вернуться", чтобы попасть на шаг 5;

## Результат
**Система:**
- В систему добавился новый клиент;

**Пользователь:**
- Получает сообщение: "Поздравляю, вы успешно зарегестрировались в сервисе 'Мастерская для души'.\n\nЧтобы начать работу, наберите команду /start.";
