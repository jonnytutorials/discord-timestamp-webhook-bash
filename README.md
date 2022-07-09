## Mit bash den aktuellen Timestamp über einen Discord-Webhook senden

### Für den Timestamp benötigt man:
``` bash
date=$(date +"%s")
timestamp="<t:$date:R>"
```
In der Variable `$timestamp` ist der formatierte Timestamp gespeichert. Diesen kannst du direkt in die Webhook-Nachricht einsetzen.
<img src="https://i.ibb.co/HYRfZFh/Webhook-Message.png" alt="Webhook-Message" border="5">
