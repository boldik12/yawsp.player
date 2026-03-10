# tmdb-helper-yawsp
Tento repozitář obsahuje jednoduchý `.json` přehrávač pro doplněk TMDb Helper v Kodi. Umožňuje vyhledávání filmů a seriálů prostřednictvím doplňku YAWsP. 
*Vytvořeno ve spolupráci s umělou inteligencí.*

## 🛠 Jak přehrávač nainstalovat do Kodi

Máte dvě možnosti instalace.

### Možnost 1: Instalace přes URL adresu v doplňku

1. Otevřete TMDb Helper doplněk.
2. V levém menu vyberte **Přehrávače (Players)**.
3. Klikněte na **Update players from URL**.
4. Vložte odkaz na ZIP soubor tohoto repozitáře:
   `https://github.com/boldik12/tmdb-helper-yawsp/archive/refs/heads/main.zip`
5. Potvrďte stisknutím OK.

### Možnost 2: Manuální vložení souboru

1. Stáhněte si soubor `yawsp.json` z tohoto repozitáře do svého zařízení.
2. Otevřete složku s uživatelskými daty doplňku TMDb Helper. Cesta se liší podle vašeho operačního systému:
   * **macOS:** `~/Library/Application Support/Kodi/userdata/addon_data/plugin.video.themoviedb.helper/players/`
   * **Windows:** `%APPDATA%\Kodi\userdata\addon_data\plugin.video.themoviedb.helper\players\`
   * **Android:** `Android/data/org.xbmc.kodi/files/.kodi/userdata/addon_data/plugin.video.themoviedb.helper/players/`
3. Vložte stažený soubor `yawsp.json` do složky `players`.
4. Restartujte Kodi.
5. V nastavení TMDb Helper - players nyní uvidíte YAWsP v nabídce přehrávačů.
