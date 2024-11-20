# Ubuntu příkazy
## Navigace v souborovém systému:
- cd /cesta/k/adresáři  # změna aktuálního adresáře
- ls -la                 # zobrazení obsahu adresáře s detaily
- pwd                    # výpis aktuálního adresáře

## Správa souborů a adresářů:
- cp zdroj cíl           # kopírování souboru nebo adresáře
- mv zdroj cíl           # přesunutí nebo přejmenování souboru/adresáře
- rm soubor              # smazání souboru
- mkdir nový_adresář     # vytvoření nového adresáře

## Správa uživatelů:
- sudo adduser uživatel      # přidání nového uživatele
- sudo deluser uživatel      # odstranění uživatele
- sudo usermod -aG skupina uživatel  # přidání uživatele do skupiny

## Správa balíčků:
- sudo apt update            # aktualizace seznamu balíčků
- sudo apt upgrade           # aktualizace nainstalovaných balíčků
- sudo apt install balíček   # instalace nového balíčku
- sudo apt remove balíček    # odstranění balíčku

## Síťové příkazy:
- ifconfig                   # zobrazení konfigurace síťového rozhraní
- ping adresa                # odeslání ping na adresu
- netstat -tuln              # zobrazení otevřených portů a síťových spojení
