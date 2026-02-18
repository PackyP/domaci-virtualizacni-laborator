# domaci-virtualizacni-laborator
Tento projekt představuje vlastní domácí virtualizační a infrastrukturní laboratoř postavenou na Proxmox VE.
--

##Přehled projektu

Cíle:

- Instalace hypervisoru na čistý disk  
- Nastavení statické IP adresy  
- Implementace bridge sítě (`vmbr0`)  
- Konfigurace storage  
- Aktivace zálohování  
- Dokumentace infrastruktury

Projekt simuluje reálné nasazení malého IT prostředí.

# Specifikace hardwaru

| Komponenta | Specifikace |
|------------|------------|
| CPU | AMD A10-7800 Radeon R17, 12 Computer Cores 4C + 8G |
| RAM | 16GB |
| Disk | TOSHIBA DT01ACA200 1,8TB |
| Síťová karta | Realtek 8821CE |

---

# Instalace Hypervisoru

Proxmox VE byl nainstalován z oficiálního ISO.

### Postup instalace

1. Boot z instalačního média  
2. Výběr čistého disku pro instalaci  
3. Nastavení hostname a root hesla  
4. Statická IP konfigurace  
5. Dokončení instalace a restart systému  

---


## 📸 Screenshoty instalace

Snímky uloženy v `docs/images/`:

```markdown
![Instalace - krok 1](docs/images/01-installer.png)
![Instalace - krok 2](docs/images/02-network-config.png)
![Instalace dokončena](docs/images/03-install-complete.png)
```

