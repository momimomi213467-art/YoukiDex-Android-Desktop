# HyperOS

Desktop mode per Android, basato su **YoukiDEX** (GPL-3.0).

Fork di: https://github.com/mrYouki/YoukiDex-Android-Desktop

## Cosa fa

- Dock / taskbar (stile Windows o centrato)
- Finestre freeform
- Overlay Accessibility (anche senza cambiare launcher)
- System tray, menu app, hot corners
- Opzionale come launcher di default

## Build

1. Clona questo repo
2. Apri in **Android Studio**
3. Sync Gradle → Run su device API 26+

```bash
git clone https://github.com/momimomi213467-art/YoukiDex-Android-Desktop.git HyperOS
cd HyperOS
# Apri in Android Studio
```

## Nome app

In `strings.xml` il nome visualizzato è **HyperOS**.  
Il `applicationId` resta `com.youki.dex` (cambiare package richiede refactor di tutto il codice Kotlin).

## Licenza

**GPL-3.0** (come YoukiDEX / Smart Dock).

## Play Protect

Se l’APK da Releases viene bloccato, builda da sorgente in Android Studio e installa quel APK.
