# Pwnbox

![htb screenshot](pwnbox.png?raw=true "Pwnbox")

¿Quieres tener tu propio pwnbox pero no tienes VIP?
¡Crea tu propio!
¡Puedes hacer todo esto en Parrot OS!

```bash
     ▄▄▄▀▄▄▄
▄▄▀▀▀       ▀▀▄▄▄
█▀▀▄▄         ▄▄▀▀█    █  █         ▐▌     ▄█▄ █          ▄▄▄▄
█    ▀▀▀▄▄▄▀▀▀    █    █▄▄█ ▀▀█ █▀▀ ▐▌▄▀    █  █▀█ █▀█    █▌▄█ ▄▀▀▄ ▀▄▀
█        █        █    █  █ █▄█ █▄▄ ▐█▀▄    █  █ █ █▄▄    █▌▄█ ▀▄▄▀ █▀█
█        █        █
█        █        █    P  E  N   -   T  E  S  T  I  N  G     L  A  B  S
▀▀▄▄     █     ▄▄▀▀
    ▀▀▀▄▄█▄▄▀▀▀
```
## DESCARGO DE RESPONSABILIDAD
`¡Esto solo se ha hecho en Parrot OS y no está destinado a otros sistemas! Por favor, intente bajo su propio riesgo`

`p.s: administradores de Hackthebox. Por favor no me mates por hacer esto ... `

## Paso 1: Abra una nueva Terminal y clone el repositorio.

`git clone https://github.com/xxxtentacion/Pwnbox.git`

## paso 2: iniciar install.sh

`cd Pwnbox`

`chmod +x install.sh`

`./install.sh`

Abra una nueva terminal y luego su terminal personalizada debería estar allí.

> Cuando te conectes a tu HTB VPN, aparecerá en tu terminal.
---
## Step 3: Selecting theme

Search up "Appearance" in "Menu". Double click "Custom" then click Customize. A new box should appear. Click the "Icons" tab and double click "Pwnbox"


## Step 4: Customising the Panel

On the top panel of your system, right click the three system monitors graphs (the ones with all those lines). Select "Remove from Panel".

### To get the 'ping panel'

Right click on a blank space on the top panel and choose "Add to Panel". In the search bar, type "command", select it and then click add. The time should show on the top panel. Right click on it, click Prefereces and in the command section, paste in `/opt/panel.sh` and change the interval to 5 seconds. It should show "HTB VPN: Disconnected" unless you're on a HTB VPN.

### To get the "processor" menu

Right click on a blank space on the top panel and search for "System monitor". Select it and add it. Right click on the little black box that appeared, select "preferences" and under "System monitor width", update it to "135" pixels, and update "System monitor update interval" "100" milliseconds. Under Monitor Resources. Check Network and Load.

## Step 5: Background

Saving the best for last!

Double click htb.jpg which is inside the github repo we installed. Click the image tab and click "Set as Desktop Background"

## Enjoy!

Hope this tutorial was easy for you!

---

## Common Issues
1.tun0: error fetching interface information: Device not found

This means that you have not connected to hackthebox's VPN. 

## More issues?

Report them to any one of these:

Twitter: https://twitter.com/ProjectFeds

Discord Taylor#1337
