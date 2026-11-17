# CL-P01 · Sinotimer SVP-688W local, fără cloud

**ConectLab EB104 – Laboratorul de Sisteme Conectate**, Facultatea de Inginerie Electrică, UPB.

Ghid interactiv pas cu pas: protectorul de energie WiFi Sinotimer SVP-688W (contor, protecție la supra/subtensiune și supracurent, șină DIN) este comandat și citit din Home Assistant doar în rețeaua locală, fără cloud-ul producătorului.

▶ **Rezolvarea aplicată (raport):** https://conectlab-upb.github.io/ConectLab-01-Sinotimer-Local/CONECTLAB_CL-P01_Sinotimer_Raport_implementare_v1.2.html

▶ **Aplicația:** https://conectlab-upb.github.io/ConectLab-01-Sinotimer-Local/

| Fișier | Conținut |
|---|---|
| `index.html` | aplicația (aceeași cu fișierul versionat) |
| `CONECTLAB_CL-P01_Sinotimer_Local_v1.0.html` | aplicația, versiunea 1.0 (proiect ConectLab CL-P01) |
| `CONECTLAB_CL-P01_Sinotimer_Raport_implementare_v1.2.html` | **rezolvarea aplicată în EB104 (17–18.11.2026)** – raport pas cu pas |
| `ConectLab_01_Sinotimer_Local_v1.0.html` | redirecționare spre numele nou (adresă veche) |

## Ce conține
1. **Începe aici** – arhitectura înainte/după, cele două căi, ce trebuie pregătit.
2. **Calea A (12 pași)** – firmware original, cheie locală cu tinytuya, integrare Tuya Local / LocalTuya în Home Assistant, blocarea accesului la internet din router.
3. **Configurator** – generează scriptul de test local; tabel pentru DP-uri.
4. **Calea B** – firmware propriu (OpenBeken / ESPHome / Tasmota), după identificarea modulului WiFi.
5. **Probleme frecvente** și lista de verificare la predare.

> Pagina nu transmite date. Cheile locale (local key) **nu se publică** în acest repository.
