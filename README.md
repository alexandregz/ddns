# DDNS dinahosting

tira contra dns para mudar zona DNS via shell

## Uso

- cambiar datos en .example
- meter en cron (crontab -e): `*/30 * * * * /home/alex/ddns/actualizar_dns.sh >> /var/log/ddns.log 2>&1`
