# Ansible Rolle "telegraf"

Installiert und konfiguriert die Software "Telegraf" auf einem Server.

Es gilt die Anleitung:
https://docs.influxdata.com/telegraf/latest/introduction/installation/

## Anforderungen

- Ordnungsgemäß konfigurierter NTP-Service auf dem Host. Andernfalls könnten
  die von Telegraf generierten Zeitstempel ungenau sein.

## Variablen

Keine.

## Abhängigkeiten

Keine.

## Beispiel

    - hosts: servers
      roles:
        - telegraf

## Lizenz

MIT
