📌 Kawasaki-CommandBlocker

Kawasaki-CommandBlocker is a lightweight Minecraft plugin that gives you full control over which commands can be used on your server.
It allows you to block specific commands for all players, while still letting trusted admins (defined in the config) use them freely.

⚙️ Features:

🔒 Block any commands listed in the config.

👤 Define specific admins who can bypass blocked commands.

📝 Customizable block message when a player tries to use a forbidden command.

🚀 Simple and clean configuration via config.yml.

📂 Example config.yml:
# List of blocked commands (without the leading slash)
blocked-commands:
  - rg i spawn
  - kill
  - op
  - deop
  - gamemode
  - ban
  - pl
  - plugins

# List of admin usernames who are allowed to use blocked commands
allowed-admins:
  - Admin1
  - Admin2

# Message players will see when trying to use a blocked command
block-message: "§cThis command is blocked!"

🛡 How it works:

If a regular player tries to run a blocked command, they’ll see: “This command is blocked!”

Players listed under allowed-admins can use the blocked commands without restrictions.


RU:

📌 Kawasaki-CommandBlocker

Kawasaki-CommandBlocker – это плагин для Minecraft, который позволяет полностью контролировать использование команд на сервере.
С его помощью можно запретить выполнение определённых команд всем игрокам, кроме тех, кто указан в конфиге.

⚙️ Возможности:

🔒 Блокировка любых команд, перечисленных в конфиге.

👤 Возможность назначить администраторов, которые могут обходить блокировку.

📝 Настройка собственного сообщения при попытке использования запрещённой команды.

🚀 Простая и понятная настройка через config.yml.

📂 Пример конфига:
# Список заблокированных команд (без начального слеша)
blocked-commands:
  - rg i spawn
  - kill
  - op
  - deop
  - gamemode
  - ban
  - pl
  - plugins

# Список ников администраторов, которым разрешено использовать заблокированные команды
allowed-admins:
  - Admin1
  - Admin2

# Сообщение, которое увидит игрок при попытке использовать заблокированную команду
block-message: "§cЭта команда заблокирована!"

🛡 Как работает:

Любой игрок, который попытается выполнить команду из списка blocked-commands, получит сообщение: "Эта команда заблокирована!".

Игроки из списка allowed-admins смогут выполнять команды без ограничений.
