мой проект представляет собой телеграм-бота, который помогает пользователям управлять своими проектами. Бот предоставляет функциональность для создания, обновления, удаления проектов, а также добавления навыков к проектам. Вот основные функции моего бота:
Основные функции:
1. Команда /start:
   Приветствует пользователя и сообщает о функционале бота.
2. Команда /info:
   Выводит список доступных команд и объясняет их использование.
3. Команда /new_project:
   Запускает процесс создания нового проекта.
   Пользователь вводит название проекта, ссылку на проект и текущий статус.
   Бот сохраняет проект в базе данных.
4. Команда /projects:
   Отображает все проекты пользователя.
   Предоставляет интерактивные кнопки для выбора проекта и получения информации о нем.
5. Команда /skills:
   Позволяет пользователю привязать навыки к определенному проекту.
   Пользователь выбирает проект и затем выбирает навык из предложенного списка.
6. Команда /delete:
   Позволяет пользователю удалить проект.
   Пользователь выбирает проект, который хочет удалить, и бот удаляет его из базы данных.
7. Команда /update_projects:
   Позволяет пользователю обновить информацию о проекте.
   Пользователь выбирает проект и затем атрибут (имя, описание, ссылка, статус), который хочет изменить.
   Пользователь вводит новое значение, и бот обновляет информацию в базе данных.

Пример использования:
 Пользователь отправляет команду /new_project.
 Бот просит ввести название проекта.
 Пользователь вводит название, бот просит ввести ссылку на проект.
 Пользователь вводит ссылку, бот предлагает выбрать статус из списка.
 Пользователь выбирает статус, бот сохраняет проект и подтверждает сохранение.
Таким образом, мой телеграм-бот помогает пользователям управлять своими проектами, предоставляя удобный интерфейс для взаимодействия и хранения информации.
