# Node-RED Cursusavond
Materiaal voor de Node-RED cursusavond

# Voordat je naar de cursusavond komt
Als je tijdens de avond zelf op je laptop mee wil doen, voer dan onderstaande handelingen thuis al uit.
Dit bespaard heel veel tijd op de avond zelf.

## Installatie Docker Desktop en Node-RED container
Voor Docker Dektop, volg deze link voor de installatie voor jouw OS en systeem:
https://docs.docker.com/desktop/setup/install/windows-install/

Na installatie en het starten van Docker Desktop, ga naar een terminal (cmd.exe in Windows)
Voer daar dit commando uit:     docker run -it -p 1880:1880 -v node_red_data:/data --name mynodered nodered/node-red
Docker gaat nu het juiste image downloaden en installeren.
Na een tijdje zie je dat de installatie klaar is.
Ga naar je browser en tik in: http://127.0.0.1:1880/
Kom je nu in een Node-RED scherm, dan is de installatie gelukt en ben je klaar voor de cursusavond.

