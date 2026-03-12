Unit file - это простой текстовый файл конфигурации в ОС Linux, используемый системой инициализации systemd для управления службами, устройствами, точками монтирования и сокетами.

``` ini
[Unit]
Description=My Simple Service

[Service]
ExecStart=/usr/local/bin/myscript.sh
Restart=always

[Install]
WantedBy=multi-user.target
```
