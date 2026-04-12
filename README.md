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


