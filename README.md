# IPTables-Manager

```
 _____    _____     _     _                 ___  ___                                  
|_   _|  |_   _|   | |   | |                |  \/  |                                  
  | | _ __ | | __ _| |__ | | ___  ___ ______| .  . | __ _ _ __   __ _  __ _  ___ _ __ 
  | || '_ \| |/ _` | '_ \| |/ _ \/ __|______| |\/| |/ _` | '_ \ / _` |/ _` |/ _ \ '__|
 _| || |_) | | (_| | |_) | |  __/\__ \      | |  | | (_| | | | | (_| | (_| |  __/ |   
 \___/ .__/\_/\__,_|_.__/|_|\___||___/      \_|  |_/\__,_|_| |_|\__,_|\__, |\___|_|   
     | |                                                                __/ |          
     |_|                                                               |___/           
```

Ein einfaches, übersichtliches Tool zur Verwaltung von iptables-Regeln mit interaktivem Menü.

## 🚀 Features

- 🔒 **Port-Management** - Ports schnell freigeben oder blockieren (TCP/UDP/Both)
- 🚫 **IP-Blocking** - Einzelne IP-Adressen blockieren oder freigeben
- 📋 **Regel-Übersicht** - Alle aktiven Regeln mit Zeilennummern anzeigen
- 💾 **Backup & Restore** - Regeln speichern und laden
- 🛡️ **Sichere Defaults** - Vorkonfigurierte sichere Standardeinstellung

## 📋 Voraussetzungen

- Linux-System (Debian, Ubuntu, CentOS, etc.)
- Root-Rechte (sudo)
- `iptables` installiert (meist vorinstalliert)

## 📥 Installation

### Option 1: Direkt von GitHub
```bash
# Repository klonen
git clone https://github.com/DEIN-USERNAME/iptables-manager.git
cd iptables-manager

# Ausführbar machen
chmod +x iptables-manager.sh

# Starten
sudo ./iptables-manager.sh
```
