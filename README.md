# 💳 Mijn Kaarten — Persoonlijke Klantenkaarten PWA

Een snelle, privacyvriendelijke Progressive Web App (PWA) om al je klantenkaarten, barcodes en QR-codes digitaal op te slaan en direct te scannen aan de kassa.

* **Privacy First:** Alle kaarten en gegevens worden 100% lokaal op je eigen apparaat bewaard (`localStorage`). Er worden geen persoonsgegevens doorgestuurd naar externe servers.
* **Offline Beschikbaar:** Werkt overal dankzij Service Worker caching, zelfs zonder internetverbinding in de winkel.
* **Retina Scherpte:** Scherm helderheid blijft actief tijdens het tonen van een code via Screen Wake Lock.

---

## 📲 Installatie op je Smartphone

Open de webapp in je browser:
👉 **`https://VanhoorewederP.github.io/Mijn-Kaarten/`**

### Op iPhone (iOS - Safari)
1. Open de link in **Safari** *(belangrijk: Chrome op iOS ondersteunt geen PWA-installaties)*.
2. Tik onderaan op de **Deel-knop** (het vierkantje met het pijltje omhoog).
3. Scroll naar beneden en kies **Zet op beginscherm**.
4. Tik rechtsboven op **Voeg toe**. De app verschijnt nu als volwaardige app zonder browserbalken op je startscherm.

### Op Android (Chrome)
1. Open de link in **Google Chrome**.
2. Tik rechtsboven op de **drie puntjes** (menu).
3. Tik op **App installeren** of **Toevoegen aan startscherm**.
4. Bevestig de installatie. De app staat nu tussen je reguliere apps.

---

## 🛠️ Functies & Knoppen

### Hoofdscherm
* **+ Nieuw (Rechtsboven):** Start de 2-staps wizard om een nieuwe kaart toe te voegen via scanner, fotobestand of handmatige invoer.
* **Zoekbalk:** Filter direct realtime door al je kaarten op winkelnaam of code.
* **Sorteerknop (A-Z / Z-A):** Wissel de weergavevolgorde van je kaarten alfabetisch om.
* **Kaart Aantikken:** Opent de kaart in vol ornaat met een grote, scanbare streepjescode of QR-code. Het scherm blijft automatisch aan zolang de kaart openstaat.

### Navigatiebalk (Onderaan)
* **🗂️ Alle Kaarten:** Toont je complete verzameling kaarten in een strak raster.
* **⭐ Vaakst Gebruikt:** Toont automatisch je top-meest geopende kaarten voor snelle toegang aan de kassa.
* **⚙️ Beheer:** Opent het beheer- en onderhoudsmenu.

---

## 💾 Beheer, Backups & Delen

Omdat gegevens lokaal op je toestel staan, kun je via het Beheer-menu eenvoudig backups maken en overzetten naar gezinsleden of een nieuwe telefoon.

### 1. Backup naar Cloud (`exportBackup`)
* Maakt een beveiligd `.json`-bestand aan met al je opgeslagen kaarten.
* Opent het standaard deelmenu van je telefoon zodat je de backup direct kunt opslaan in iCloud Bestanden, Google Drive, of doorsturen via WhatsApp/E-mail.

### 2. Herstel Opgeslagen Backup (`importBackup`)
* Laadt een eerder bewaard `.json`-bestand in.
* **Veilig samenvoegen:** De app wist je bestaande kaarten niet, maar voegt de nieuwe kaarten slim samen met je huidige collectie (dubbele kaarten worden automatisch overgeslagen).
* *Tip bij WhatsApp:* Tik niet zomaar op een ontvangen `.json`-bestand, maar bewaar het eerst in je **Bestanden / Downloads** map op je telefoon, en selecteer het vervolgens via deze herstelknop in de app.

### 3. Zoek naar Updates (`checkForAppUpdate`)
* Omzeilt Safari- en Chrome-browsercaches en controleert direct op GitHub of er een nieuwere versie van de app klaarstaat.
* Zodra er een nieuwe update is, herlaadt de app zichzelf automatisch naar de nieuwste versie.
