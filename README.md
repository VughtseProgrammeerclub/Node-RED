# Node-RED Cursusavond
Materiaal voor de Node-RED cursusavond

# Voordat je naar de cursusavond komt
Als je tijdens de avond zelf op je laptop mee wil doen, voer dan onderstaande handelingen thuis al uit.
Dit bespaart heel veel tijd op de avond zelf.

## Installatie Docker Desktop en Node-RED container
Voor Docker Dektop, volg deze link voor de installatie voor jouw OS en systeem:
https://docs.docker.com/desktop/setup/install/windows-install/

Na installatie en het starten van Docker Desktop, ga naar een terminal (cmd.exe in Windows)
Voer daar dit commando uit:     docker run -it -p 1880:1880 -v node_red_data:/data --name mynodered nodered/node-red.
Docker gaat nu het juiste image downloaden en installeren.
Na een tijdje zie je dat de installatie klaar is.
Ga naar je browser en tik in: http://127.0.0.1:1880/
Kom je nu in een Node-RED scherm, dan is de installatie gelukt en ben je bijna klaar voor de cursusavond.

## Toevoegen Node-RED dashboard
We gaan ook werken met een node-RED dashboard.
Deze is standaard niet aanwezig in Node-RED, maar kunnen we toevoegen.
Dit kun je doen als je in de webinterface van Node-RED zit. (http://127.0.0.1:1880/)
Ga rechtsboven naar het hamburger-menu en kies "Manage palette" (of gebruik shift-Alt P)
Kies de tab "INSTALL" en type in de searchbar "dashboard"
De bovenste keuze is direct het dashboard wat we gaan gebruiken. (node-red-dashboard)

![image](https://github.com/user-attachments/assets/eb9e4006-661f-47ce-b992-db8ed9cc0134)

Klik op "install".
Nu worden er een aantal modules geïnstalleerd. En als dit gebeurd is heb je in het menu links een aantal keuzes extra gekregen.
Het "dashboard" tab.

![image](https://github.com/user-attachments/assets/05523825-3bb4-4d10-890d-1d372cd76bc6)

Je kan nu testen of je dashboard installatie geukt is. 
Ga naar http://localhost:1880/ui/ en kijk of je iets van een webpagina krijgt met een welkombericht.

Als dit allemaal gelukt is ben je helemaal klaar voor de cursusavond.
Je kan de container veilig afsluiten door in Docker desktop op de stopknop van de container te klikken.
Op deze plaats kan je hem ook weer starten als je verder wil gaan met Node-RED.

![image](https://github.com/user-attachments/assets/8a0d78e8-708e-41cb-a3ef-72fb021de4e0)




