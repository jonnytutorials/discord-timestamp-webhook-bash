## Mit bash den aktuellen Timestamp über einen Discord-Webhook senden

### Für den Timestamp benötigt man:
``` bash
date=$(date +"%s")
timestamp="<t:$date:R>"
```
In der Variable `$timestamp` ist der formatierte Timestamp gespeichert. Diesen kannst du direkt in die Webhook-Nachricht einsetzen.
<p align="center">
<img src="https://i.ibb.co/yFRqJQr/Webhook-Message.png" alt="Webhook-Message">
</p>

### Fertig! Fehler kannst du [hier](https://github.com/jonnytutorials/discord-timestamp-webhook-bash/issues/new) melden. Für Verbesserungsvorschläge steht mein [Discord Server](https://discord.gg/s9tD46Fwh8) zur verfügung.
