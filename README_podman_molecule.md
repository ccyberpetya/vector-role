# Vector Role

Эта роль устанавливает и настраивает [Vector](https://vector.dev) на хостах под управлением AlmaLinux 9 (или других RHEL-систем).
## Переменные роли 

Основные переменные находятся в `defaults/main.yml`. Вы можете переопределить их при вызове роли:
| Переменная | Описание | Значение по умолчанию |
|------------|----------|-----------------------|
| `vector_version` | Версия Vector для установки | `0.34.1` |

## Использование

```yaml
- name: Install Vector
  hosts: vector
  become: true
  roles:
    - vector-role

## License

MIT

# РАБОТА С MOLECULE PODMAN



<img width="1116" height="174" alt="version" src="https://github.com/user-attachments/assets/f0ec67c9-5905-4c25-8ff2-5bfa89dd57ac" />






