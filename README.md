# Ansible role example

Ansible роль для примера, на основе установки и настройки nginx.

## Role Variables

Переменные для nginx.

* `nginx_port` - порт на котором запускается nginx.
* `nginx_error_log_output` - путь куда будет выводиться ошибки nginx.
* `nginx_access_log_output` - путь куда будет выводиться логи nginx.
* `nginx_error_log_level` - тип уровня вывода ошибок (emerg/alert/crit/error/warn/notice/info/debug).
