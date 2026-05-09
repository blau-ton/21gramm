# Datenschutzerklärung · 21 Gramm

**Stand:** Mai 2026

Diese Datenschutzerklärung beschreibt, welche Daten die App „21 Gramm"
(im Folgenden „die App") verarbeitet — und welche nicht.

Die kurze Antwort: **fast keine.** Die App ist so konzipiert, dass deine
persönlichen Inhalte (Tagebuch, Mood-Werte, Foundation-Fortschritt,
Mantra-Sammlung) ausschließlich auf deinem Gerät gespeichert sind. Es
gibt **kein Konto, keine Cloud-Sync, kein Tracking, keine Werbung**.

---

## 1 · Verantwortlicher

Verantwortlich für die Datenverarbeitung im Sinne der DSGVO ist:

> **Alessandro Emrich**
> Salzstrasse 58
> 82110 Germering
> Deutschland
> E-Mail: blau.ton@icloud.com

## 2 · Welche Daten lokal auf dem Gerät bleiben

Folgende Daten werden ausschließlich in den iOS-Speicher (`UserDefaults`)
und Core Data deines Geräts geschrieben — sie verlassen dein Gerät zu
keinem Zeitpunkt:

- Sprach- und Stimmpräferenz
- Standard-Dauer einer Session
- Hintergrundklang-Auswahl & Lautstärke
- Foundation-Fortschritt (welche Pflicht-Lektion als nächste kommt)
- Tagebuch-Einträge (Highlight, Gedanke, Gefühl)
- Mood-Werte vor/nach Sessions
- Gesehene und favorisierte Mantras
- Session-Historie (Datum, Skript-ID, Dauer, Pillar)
- Reminder-Einstellungen (Morgens / Mittags / Abends)
- Theme-Auswahl

Wenn du die App löschst, werden diese Daten unwiderruflich gelöscht.

## 3 · Verbindungen, die die App nach außen aufbaut

Damit die App funktioniert, lädt sie Inhalte von zwei Diensten:

### 3.1 · Supabase (Content-Datenbank)

Beim Öffnen des Heute-Tabs ruft die App Texte (Tagesfaden-Mantra,
Skript-Metadaten) aus einer Supabase-Datenbank ab. Übertragen wird:

- die ausgewählte Sprache (`de` oder `en`)
- der Tag des Jahres (z. B. `127`)

**Es wird keine Geräte-ID, IP-bezogene Identifikation oder Benutzerkennung
gespeichert.** Supabase loggt Standard-HTTP-Zugriffsdaten (IP-Adresse,
Zeitstempel) für Stabilitätsüberwachung; diese werden nach 7 Tagen
gelöscht.

Anbieter: Supabase Inc., 970 Toa Payoh North #07-04, Singapur 318992.
Datenschutzerklärung: https://supabase.com/privacy

### 3.2 · Cloudflare R2 (Audio-CDN)

Die Audio-Dateien (Guide-Stimme + Hintergrundklang) werden bei jeder
Session direkt von einem öffentlichen Cloudflare-R2-Bucket gestreamt.
Übertragen wird der Datei-Pfad (z. B. `de/awareness/A-morning_10_clara.mp3`).

Cloudflare loggt Standard-HTTP-Zugriffsdaten zur Abuse-Prevention.
Anbieter: Cloudflare Inc., 101 Townsend St, San Francisco, CA 94107, USA.
Datenschutzerklärung: https://www.cloudflare.com/privacypolicy/

### 3.3 · Apple StoreKit (Abonnement)

Wenn du ein Abo abschließt, läuft die Zahlung über Apple's StoreKit.
Die App selbst sieht weder deine Apple-ID, deine Zahlungsdaten noch
deine Rechnungsadresse — sie erfährt nur, ob du aktuell ein gültiges
Abo besitzt.

Anbieter: Apple Inc., One Apple Park Way, Cupertino, CA 95014, USA.
Datenschutzerklärung: https://www.apple.com/legal/privacy/

## 4 · Was die App NICHT tut

- ❌ Kein Analytics (Firebase, Mixpanel, Sentry o. ä.)
- ❌ Keine Werbe-Tracker
- ❌ Kein Cross-App-Tracking (kein App Tracking Transparency Prompt nötig)
- ❌ Keine Cookies, kein Web-Tracking
- ❌ Kein Account, kein Login
- ❌ Keine E-Mail-Liste, kein Newsletter
- ❌ Keine Standortabfrage
- ❌ Kein Zugriff auf Kontakte, Fotos, Mikrofon

## 5 · Lokale Benachrichtigungen

Wenn du in den Einstellungen Tageserinnerungen aktivierst, plant die App
über das iOS-Framework `UserNotifications` lokale Notifications zu den
gewählten Zeiten. Diese laufen vollständig auf deinem Gerät — es ist
kein Push-Server, kein Provider involviert.

## 6 · Deine Rechte (DSGVO)

Da wir keine personenbezogenen Daten erheben, sind folgende Rechte
weitgehend gegenstandslos — der Vollständigkeit halber:

- **Auskunftsrecht (Art. 15 DSGVO):** alle deine App-Daten siehst du
  direkt im Profil-Tab und in den Reflexion-Ansichten.
- **Berichtigung (Art. 16 DSGVO):** Tagebuch-Einträge sind direkt in der
  App editierbar.
- **Löschung (Art. 17 DSGVO):** App deinstallieren ODER Profil → „Alles
  zurücksetzen".
- **Datenübertragbarkeit (Art. 20 DSGVO):** Wir können deine Daten nicht
  exportieren, weil wir sie nicht haben — sie liegen ausschließlich auf
  deinem Gerät.

## 7 · Änderungen

Bei wesentlichen Änderungen dieser Datenschutzerklärung wird die App
über ein Update veröffentlicht; ein Hinweis erscheint im Profil-Modal.

## 8 · Kontakt

Bei Fragen oder Bedenken: **blau.ton@icloud.com**
