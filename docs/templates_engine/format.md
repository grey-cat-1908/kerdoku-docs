# Форматирование Текста

## Переменные шаблонов тоже поддаются форматированию.
Пример:

    Привет, **{{member.name}}**. 
    *Твой id: {{member.id}}*.
    Данный сервер принадлежит ~~{{guild.owner}}~~ нашему комьюнити.
    Кстати, ты `{{guild.memberCount}}` на данном сервере.

Результат будет примерно такой: 

> Привет, Марио. Твой id: 01020304050607. Данный сервер принадлежит Вася Петров нашему комьюнити. Кстати, ты 567 на данном сервере

## Способы Форматирования.

| Ввод  | Результат |
| ------| ---------|
| \*Курсив\* | *Курсив* |
| \*\*Жирный\*\* | **Жирный** |
| ~~Зачеркнутый~~ | ~~Зачеркнутый~~ |
| \`Однострочный блок\` | `Однострочный блок` |


### А что по поводу дат?
| Ввод  | Результат |
| ------| ---------|
| `<t:время-unix:R>` | `in n days` |


И это все? нет конечно! Более подробно с форматированием Вы можете ознакомиться [тут!](https://discord.com/developers/docs/reference#message-formatting)