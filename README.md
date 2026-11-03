<!-- Copyright © 2026 David Wright und Inviatec GmbH
     Author: David Wright <david.wright@inviatec.de>
     SPDX-License-Identifier: Apache-2.0 -->
<div align="center">

# OrbitOne Client

**Deine Workspaces. Mehrere Server. Ein vertrauter Arbeitsplatz.**

[Website](https://orbitone.io) · [Downloads](https://dist.orbitone.io) · [Server](https://github.com/dwrightdev/orbitone-server) · [Kontakt](mailto:david.wright@inviatec.de)

**Electron · Windows & macOS · Apache-2.0**

</div>

Der OrbitOne-Desktop bringt Wissen, Aufgaben, Notizen und Dateien in eine ruhige,
gemeinsame Oberfläche. Verbinde deine Server, wechsle schnell zwischen Workspaces
und greife auf die Inhalte zu, die für dich freigegeben sind.

## Ein Arbeitsplatz für verbundene Inhalte

- **Mehrere Server:** Getrennte Verbindungen und Sitzungen mit schnellem Wechsel.
- **Workspaces und Spaces:** Navigation, Farben und Icons machen den aktuellen Kontext sichtbar.
- **Globale Suche:** Erlaubte Inhalte über verbundene Server und Workspaces finden, mit Herkunft im Ergebnis.
- **Persönlicher Überblick:** Eigene Aufgaben, Notizen, Favoriten, zuletzt bearbeitete Inhalte und Erwähnungen.
- **Seiten und Notizen:** Rich-Text, Dateien, Bilder, Erwähnungen, Diagramme und Verknüpfungen.
- **Optionale Plugins:** Funktionen passend zur Server- und Space-Konfiguration nutzen.
- **Desktop-Dateien:** Unterstützte Anhänge extern bearbeiten und mit der verbundenen Instanz synchronisieren.

Der Server entscheidet über Freigaben und verfügbare Plugins. Eine Client-Anbindung
erteilt keine zusätzlichen Rechte auf Inhalte oder separat lizenzierte Dienste.

## Installation

Veröffentlichte Pakete gibt es unter **[dist.orbitone.io](https://dist.orbitone.io)**.

### Windows

Den Installer herunterladen, ausführen und OrbitOne starten. Alternativ das
portable ZIP vollständig in einen eigenen Ordner entpacken und `OrbitOne.exe`
starten. Der gesamte entpackte Anwendungsordner gehört zusammen.

### macOS

Der Client ist für Windows und macOS vorgesehen. Ein macOS-Download wird erst
angeboten, wenn ein entsprechender Mac-Build erstellt wurde. Ein vorhandener
Windows-Download ist kein macOS-Paket.

## Erste Verbindung

1. Beim Start zwischen **Server verbinden** und **Demo laden** wählen.
2. Die HTTPS-Adresse der eigenen OrbitOne-Instanz eintragen und anmelden.
3. Workspace und Bereich auswählen; die verfügbaren Inhalte folgen deinen Rechten.
4. Weitere Server über **Server & Profil** hinzufügen.

Die kompakte Statusleiste zeigt im entsprechenden Client-/Serverstand den aktuellen
Server, Workspace und Space. Farben folgen dezent dem jeweiligen Kontext.

Die lokale Demo enthält fiktive Beispieldaten und speichert ihre Änderungen im
lokalen Benutzerprofil. Sie ersetzt keine vereinbarte lokale Produktivinstallation
mit Sicherungs- und Mehrbenutzerkonzept. Bestehende lokale Nutzerdaten werden
durch neue Demo-Vorlagen nicht absichtlich überschrieben.

## Updates

OrbitOne prüft den signierten Updatekatalog und bietet verfügbare Pakete an.
Eine Aktualisierung wird dadurch nicht stillschweigend auf deinen Servern
installiert. Client und Server können für neue Funktionen gemeinsam zu
aktualisieren sein. Persönliche Verbindungen und lokale Daten bleiben im
Benutzerprofil; vor Eingriffen in produktive Instanzen gehören deren Daten und
Schlüssel gesichert.

## Lizenz und Abhängigkeiten

Der eigene, eigenständige Desktop-/Clientcode ist **Open Source unter
Apache License 2.0**. Diese Lizenz enthält keine Hostingbeschränkung.
Der PHP-/MySQL-Server ist davon getrennt und verwendet ELv2 (Source Available).
Plugins und Drittanbieter-Bibliotheken behalten ihre jeweiligen Bedingungen.

Die vollständigen Lizenztexte und Drittanbieterhinweise liegen den Desktop-Paketen
bei und sind in **Info → Über OrbitOne** auch offline lesbar. NAPS2-/OCR-, HEIC-,
Electron-/Chromium- und weitere Abhängigkeiten werden dadurch nicht pauschal
unter Apache-2.0 neu lizenziert.

Für die jeweiligen Softwarekomponenten gelten die in ihren Lizenzbedingungen
enthaltenen Gewährleistungs- und Haftungsregelungen. Zwingende gesetzliche Rechte
bleiben unberührt. Für gesondert vereinbarte Hosting- und Serviceleistungen gelten
zusätzlich die jeweiligen Vertragsbedingungen.

## Plugins und Beiträge

Das eigenständige SDK ermöglicht freie und kommerzielle Plugins mit eigener
Lizenz. Die Lizenz einer Client-Anbindung gibt keine proprietäre serverseitige
Funktion frei. Mobilapps und Browser-Erweiterungen werden bei ihrer Entwicklung
gesondert zugeordnet; dieses Repository enthält dafür keine vorweggenommenen
Lizenzzusagen.

Bei Beiträgen bleiben Urheberrechte und vorhandene Hinweise erhalten. Bitte die
jeweiligen Beitragsregeln und Lizenzgrenzen beachten.

---

**Entwickelt von David Wright · dwrightdev · Inviatec GmbH**  
Copyright © 2026 David Wright und Inviatec GmbH  
[dwrightdev](https://github.com/dwrightdev) · [david.wright@inviatec.de](mailto:david.wright@inviatec.de) · [inviatec.de](https://inviatec.de)

[Impressum der Projektwebsite](https://orbitone.io/impressum/) · [Datenschutz der Projektwebsite](https://orbitone.io/datenschutz/)
