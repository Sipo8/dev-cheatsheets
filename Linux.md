# Linux

## Файлы
```bash
ls -lah                        # подробно
find . -name "*.log"           # найти по имени
grep -r "текст" .              # рекурсивный поиск
df -h                          # место на дисках
```

## Процессы
```bash
ps aux | grep python           # найти процесс
top                            # живая статистика
kill -9 <pid>                  # убить жёстко
```

## Сеть
```bash
curl -I https://example.com    # заголовки
ss -tulpn                      # слушаемые порты
ip a                           # IP-адреса
```

## Хитрости
```bash
Ctrl+R                         # поиск по истории команд
history | grep ssh             # найти в истории
!!                             # повторить последнюю команду
```
