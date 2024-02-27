# Сканер TCP портов
## Описание
Сканер открытых TCP/UDP портов c определением некоторых протоколов
## Help
```commandline
usage: portscanner.py [-h] [--host HOST] ports

TCP port scanner.

positional arguments:
  ports        port or range of ports example: 1..100

optional arguments:
  -h, --help   show this help message and exit
  --host HOST  host to scan
```
## Запуск
```commandline
python portscanner.py --host 8.8.8.8 50..55
```
или
```commandline
python portscanner.py --host 8.8.8.8 53
```
