README для бота-напоминалка в Telegram

Обзор
Это простой бот для Telegram, который позволяет пользователям устанавливать напоминания для различных типов задач, таких как экзамены, задания, лабораторные работы и коллоквиумы. Бот взаимодействует с пользователями пошагово в формате диалога, запрашивая их имя, тип напоминания, который они хотят установить, и конкретные детали для этого напоминания.

Функции
Приветствует пользователя и просит его имя.
Позволяет пользователям выбрать тип напоминания (например, Экзамен, Задание, Лабораторная работа, Коллоквиум).
Запрашивает детали напоминания (например, для чего напоминание и когда оно должно быть).
Позволяет пользователям отменить процесс в любой момент.
Очищает данные пользователя после того, как напоминание установлено.

Как это работает
Запуск бота:
Когда пользователь запускает бота с помощью команды /start, бот запрашивает имя пользователя.

Установка напоминания:
После того как пользователь введет свое имя, бот предложит выбрать тип напоминания (Экзамен, Задание, Лабораторная работа или Коллоквиум).
После того как пользователь выберет тип напоминания, бот попросит предоставить подробности о напоминании (например, "Экзамен по математике 15 июня в 9:00").

Подтверждение:
После того как пользователь предоставит все детали напоминания, бот подтвердит напоминание и сохранит информацию.

Отмена:
Пользователь может отменить процесс в любой момент, введя команду /cancel, что завершит разговор и очистит все сохраненные данные.
