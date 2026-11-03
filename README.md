# Dual Ram Versions of MiSTer Console Cores
These cores require two SDRAM boards to function*. While most will work fine with a 128mb board and a 32mb board, having two 128mb 3.0 boards will guarantee compatability.

\**Some main board vendors solder SD ram directly to the board. In this case, you only need one SDRAM board in the left GPIO slot*
## Info
Cores will be put in the `Console (Dual SDRAM)` folder.

To manually install, add this to your `downloader.ini`.

```ini
[TheJesusFish/Dual-Ram-Console-Cores]
db_url = https://raw.githubusercontent.com/TheJesusFish/Dual-Ram-Console-Cores/db/db.json.zip
```
### Versioning
- **Saturn:** Based on the latest stable core
- **Jaguar:** Based on the latest stable core
- **PSX:** Based on the VRAM dual ram core (which is based on the latest stable).
