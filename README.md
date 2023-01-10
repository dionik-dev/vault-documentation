# Welcome bij je nieuwe Vault!

Op deze pagina vindt je alle informatie die je nodig hebt om je nieuwe wachtwoordmanager (Dionik Vault) te installeren en configureren!


## 1. Wireguard VPN installeren en configureren
Dionik Vault gebruikt Wireguard om verbinding te maken met de server van de wachtwoordmanager. Wireguard is VPN software die het mogelijk maakt om op een veilige manier verbinding te maken met een externe server, zoals deze wachtwoordmanager. Wireguard maakt gebruik van geavanceerde encryptietechnologie om de communicatie tussen jouw apparaat en de server te beschermen. Dit betekent dat als iemand probeert mee te luisteren op jouw verbinding, ze niet zullen kunnen zien wat je aan het doen bent.

Om verbinding te kunnen maken met de VPN, heb je speciale software nodig. Klik hieronder op het type apparaat dat je aan het instellen bent om naar de juiste instructies te gaan.

* [Wireguard VPN installeren op Windows](wireguard/wireguard_windows_nl.md)
* [Wireguard VPN installeren op macOS](wireguard/wireguard_macos_nl.md)
* [Wireguard VPN installeren op Android](wireguard/wireguard_android_nl.md)
* [Wireguard VPN installeren op iOS](wireguard/wireguard_ios_nl.md)

Wanneer je problemen ondervindt bij het bereiken van Dionik Vault, controleer dan altijd als eerste of Wireguard actief is en of je verbonden bent met de VPN.

## 2. Bitwarden installeren
Dionik Vault is gebaseerd op Bitwarden. Je kunt dus gebruik maken van de Bitwarden software om toegang te krijgen tot jouw wachtwoordmanager. Bitwarden software is beschikbaar voor desktops (bijv. Windows of macOS), browsers (bijv. Mozilla Firefox of Google Chrome) en telefoons (bijv. Android of iOS). Voor gebruik op een desktop raden we in ieder geval de Bitwarden browser extensie aan. Het installeren van de desktop applicatie is in de meeste gevallen overbodig.

Het installeren van Bitwarden gaat als volgt.

1. Ga naar de downloadpagina van Bitwarden: https://bitwarden.com/download
2. Download de installer voor het apparaat dat je aan het instellen bent. Als je dit vanaf je telefoon doet kan het zijn dat je vrij ver omlaag moet scrollen om de Android en iOS installers te vinden.
3. Voer de installer uit en volg de instructies (je kunt alle standaardinstellingen aanhouden)


## 3. Bitwarden configureren
De laatste stap is het configureren van Bitwarden. Standaard probeert Bitwarden verbinding te maken met een server op het internet. Dionik Vault bevindt zich echter niet op het open internet, maar is afgeschermd en alleen toegankelijk door middel van de VPN die je eerder hebt ingesteld.

Het configureren van Bitwarden gaat als volgt.

1. Open de door jouw geïnstalleerde versie van Bitwarden
2. Klik op "Instellingen" (Windows & macOS) of het tandwieltje (browser, Android & iOS)
3. Er opent nu een venster met daarin het kopje "Zelfgehoste omgeving". Onder dit kopje staat één invoerveld met de titel "Server-URL". Voer hier de `Vault URL` uit je email in, deze eindigt op `.dionik.ink`. Let op: zorg ervoor dat alle invoervelden onder het kopje "Aangepast omgeving" leeg zijn.
4. Klik op "Opslaan"


## 4. Bitwarden gebruiken
Zo, het moeilijke werk zit erop. Het enige wat je nu nog moet doen, is een account aanmaken. Hiervoor heb je de uitnodiging van Bitwarden nodig die je per email hebt ontvangen.

1. Zoek je persoonlijke uitnodigingsemail (de afzender van deze email is `noreply@vault.dionik.ink`)
2. Klik op de link in de email
3. Maak een account
4. Verifieer je emailadres
5. Log in!

**Let op**: je hoeft niet continu verbonden te zijn met de VPN om gebruik te maken van de wachtwoordmanager (dat zou betekenen dat hij zonder internetverbinding niet te gebruiken is). Er wordt een kopie naar je apparaat gedownload, zodat hij ook offline beschikbaar is. Wanneer je een nieuw wachtwoord toevoegt, dan wordt dat nieuwe wachtwoord automatisch naar de server verzonden zodat hij ook op al je andere apparaten beschikbaar is. Voor dit verzenden naar de server is de VPN verbinding wel nodig, dus zorg ervoor dat de VPN verbinding geactiveerd is in Wireguard wanneer je een nieuw wachtwoord toevoegt.

## 5. Belangrijke opmerkingen
Gefeliciteerd, als je tot hier bent gekomen dan heb je nu een werkende wachtwoordmanager! Je kunt Dionik Vault bereiken via de door jou geinstalleerde applicatie (browser, desktop of telefoon), maar je kunt er ook via de `Vault URL` uit je email bij.

Er zijn nog een aantal belangrijke zaken waarop ik je wil wijzen.

1. Kies een veilig wachtwoord voor je account. Je Dionik Vault account is de sleutel tot al je wachtwoorden; iemand die dat wachtwoord achterhaalt kan bij al je wachtwoorden. Een veilig wachtwoord voldoet aan de volgende eisen:
  * Minimaal 12 karakters lang
  * Minimaal 1 kleine letter
  * Minimaal 1 hoofdletter
  * Minimaal 1 cijfer
  * Minimaal 1 leesteken

2. Toegang tot Dionik Vault is alleen mogelijk via een beveiligde VPN verbinding met Wireguard. Wireguard maakt bij het opstarten van je apparaat een beveiligde verbinding met Dionik Vault, waardoor je in kunt loggen. Deze beveiligde verbinding maakt het voor een hacker erg moeilijk om de wachtwoordkluis binnen te dringen. Echter: wanneer hij of zij toegang kan krijgen tot een apparaat dat verbonden is met de VPN (zoals jouw computer, laptop of telefoon) wordt dit een stuk gemakkelijker. Het is daarom erg belangrijk dat je alle apparaten waarop je toegang hebt tot Dionik Vault goed beveiligt.  
 Gebruik in het geval van een laptop of computer altijd een inlogwachtwoord (of pincode) en zorg ervoor dat je je apparaat nooit ontgrendeld achterlaat. In het geval van een telefoon geldt ook dat je een pincode of ander ontgrendelingsmechanisme (bijv. vingerafdruk) moet instellen.  

 **Neem in het geval van inbraak of diefstal van een van je apparaten direct contact op. Hiermee kan je voorkomen dat een hacker via jouw apparaat de wachtwoordkluis kan bereiken.**
 

## Tot slot
Als je naar aanleiding van alles hierboven nog vragen of opmerkingen hebt, neem dan gerust contact op. Je kunt mijn contactgegevens in je email vinden.
