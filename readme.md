# Инструкция по Git!
## 1. Проверка наличия установленного Git
В терминале выполните команду `git --version`.
Если Git установлен, появится сообщение с информацией о версии программы. Иначе будет сообщение об ошибке.
## 2. Установка Git
Загружаем последнюю версию Git с сайта: https://git-scm.com/downloads. Устанавливаем с настройками по умолчанию
## 3. Настройка Git
При первом использовании Git необходимо представиться. Для этого нужно ввести в терминале две команды:

```
git config --global user.name «Ваше имя английскими буквами»
git config --global user.email ваша почта@example.com
```
## 4. Инициализация репозитория
Для создания репозитория нужно выполнить команду `git init`, и у вас появится здастся скрытая папка .git

## 5. Создание коммитов
### Git add
Для добавления изменений в коммит, используется комнада `git add`. Чтобы воспользоваться этой командой, нужно написать `git add <имя файла>`

### Просмотр состояния реопзитория
Чтобы увидеть были ли изменения в файле напишите `git status`. Там вы увидите состояние репозитория.