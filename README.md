# tmdb-helper-yawsp
Tento repozitář obsahuje jednoduchý `.json` přehrávač pro doplněk TMDb Helper v Kodi. Umožňuje automatizované vyhledávání filmů a seriálů prostřednictvím doplňku YAWsP. 
*Vytvořeno ve spolupráci s umělou inteligencí.*

## 🛠 Jak přehrávač nainstalovat do Kodi

Máte dvě možnosti instalace. Vyberte si tu, která vám vyhovuje více (pro Android boxy a televize jednoznačně doporučuji první možnost).

### Možnost 1: Instalace přes URL adresu v Kodi (Doporučeno pro Android TV / Boxy)
Toto je nejjednodušší způsob, jak přehrávač nainstalovat bez nutnosti ručně kopírovat soubory do skrytých složek systému.

1. Otevřete TMDb Helper doplněk.
2. V levém menu vyberte **Přehrávače (Players)**.
3. Klikněte na **Update players from URL**.
4. Do vyskakovacího okna vložte odkaz na ZIP soubor tohoto repozitáře:
   `https://github.com/TVUJ_NICK/TVUJ_REPOZITAR/archive/refs/heads/main.zip`
5. Potvrďte stisknutím OK.
6. Aplikace se zeptá, zda chcete stávající přehrávače přepsat, nebo přidat nové. Zvolte podle vlastního uvážení.

### Možnost 2: Manuální vložení souboru
Pokud máte k souborům a složkám v Kodi snadný přístup (např. na počítači), můžete `.json` soubor nakopírovat přímo na jeho místo.

1. Stáhněte si soubor `yawsp.json` z tohoto repozitáře do svého počítače.
2. Otevřete složku s uživatelskými daty doplňku TMDb Helper. Cesta se liší podle vašeho operačního systému:
   * **macOS:** `~/Library/Application Support/Kodi/userdata/addon_data/plugin.video.themoviedb.helper/players/`
   * **Windows:** `%APPDATA%\Kodi\userdata\addon_data\plugin.video.themoviedb.helper\players\`
   * **Android:** `Android/data/org.xbmc.kodi/files/.kodi/userdata/addon_data/plugin.video.themoviedb.helper/players/`
3. Vložte stažený soubor `yawsp.json` do složky `players`.
4. Restartujte Kodi.
5. V nastavení TMDb Helperu nyní uvidíte YAWsP v nabídce přehrávačů.
