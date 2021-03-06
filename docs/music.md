# Музыка

## Конфигурация

Конфигурация модуля музыки **KerdokuBot** осуществляется при помощи команды `music-settings`.

Структура команды такая: `<prefix>music-settings <настройка> (значение)`

**Посмотреть текущие настройки можно командой `<prefix>music-settings config`.**

В данный момент модуль музыки **KerdokuBot** подразумевает наличие следующих настроек:

| Настройка  | Возможное Значение |
| ------------| ---------|
| `Диджей` | `@Роль | Администратор`  |
| `Продвинутый Поиск` | `Включено/Выключено (1/0)` |
| `Средство Поиска` | `Youtube` |

#### Диджей

Диджей имеет право пропускать музыку, останавливать, а также делать все прочие действия без согласия других участников.

| Аргументы  | Значения |
| ------------| ---------|
| `<настройка>` | `didjey-role`  |
| `<значение>` | `@Роль | Ничего` |

#### Продвинутый поиск

Поиск бывает 2-х видов - обычный и продвинутый.

**При обычном поиске** выбирается самый первый трек.

**При продвинутом поиске** появляется меню выбора трека из предложенных.

| Аргументы  | Значения |
| ------------| ---------|
| `<настройка>` | `advanced-search`  |
| `<значение>` | `1 (Включено) / 0 (Выключено)` |

## 