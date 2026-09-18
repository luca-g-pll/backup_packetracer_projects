# backup_packetracer_projects

Repository di **backup personale** contenente file `.pkt` di **Cisco Packet Tracer**, relativi a esercitazioni pratiche di networking svolte durante il percorso di studio.

## 📋 Descrizione

Cisco Packet Tracer è un software di simulazione di rete sviluppato da Cisco, utilizzato per progettare, configurare e testare topologie di rete (router, switch, PC, server) in un ambiente virtuale, senza bisogno di hardware fisico. Questa repository funge da archivio/backup dei file di progetto (`.pkt`) prodotti durante lo svolgimento di esercitazioni scolastiche/di laboratorio, con particolare focus su:

- **NAT** (Network Address Translation) — traduzione degli indirizzi IP privati in pubblici
- **DHCP** (Dynamic Host Configuration Protocol) — assegnazione automatica degli indirizzi IP ai dispositivi
- **Firewall** — configurazione di regole di sicurezza di rete

## 🗂️ Struttura del repository

| File | Argomento presunto |
|---|---|
| `ES_15_NAT.pkt` | Esercizio 15, configurazione NAT |
| `NATesercitazione.pkt` | Esercitazione dedicata al NAT |
| `PROVA_VE.pkt` | File di prova/verifica |
| `es_3_dhcp.pkt` | Esercizio 3, configurazione DHCP |
| `es_3.2_dhcp.pkt` | Esercizio 3.2, variante/approfondimento DHCP |
| `es_4.pkt` | Esercizio 4 |
| `es_5.pkt` | Esercizio 5 |
| `es_8_1.pkt` | Esercizio 8, parte 1 |
| `es_8_2.pkt` | Esercizio 8, parte 2 |
| `es_8_3.pkt` | Esercizio 8, parte 3 |
| `es_9_4.pkt` | Esercizio 9, parte 4 |
| `es_9_5.pkt` | Esercizio 9, parte 5 |
| `firewall_1.pkt` | Esercizio sulla configurazione di un firewall |

Tutti i file sono topologie di rete indipendenti tra loro, ciascuna rappresentante un esercizio o una prova specifica.

## ⚙️ Requisiti

Per aprire e visualizzare/modificare questi file è necessario:

- **Cisco Packet Tracer** (scaricabile gratuitamente previa registrazione su [Cisco Networking Academy](https://www.netacad.com/courses/packet-tracer))
- Versione consigliata: la più recente disponibile, per garantire la piena compatibilità con i file `.pkt`

## 💻 Utilizzo

1. Scarica e installa Cisco Packet Tracer se non già presente.
2. Clona o scarica i file `.pkt` di interesse da questo repository.
3. Apri Packet Tracer e carica il file (`File → Open`) per visualizzare la topologia di rete, i dispositivi configurati e le relative impostazioni (indirizzamento IP, regole NAT/DHCP/firewall, ecc.).
4. È possibile eseguire la simulazione in tempo reale o in modalità "Simulation" per osservare il flusso dei pacchetti tra i dispositivi.

## ⚠️ Note

- Questa repository è pensata come **archivio/backup personale**, non come progetto software con codice sorgente: non contiene script, applicazioni o documentazione approfondita per ciascun esercizio.
- I nomi dei file non seguono una convenzione di naming del tutto uniforme (es. `es_3_dhcp.pkt` vs `es_3.2_dhcp.pkt` vs `es_4.pkt` senza argomento nel nome), il che rende utile consultare direttamente il contenuto del file per capirne lo scopo esatto.
- Non essendo file di testo, il contenuto dei `.pkt` non è leggibile/versionabile in modo tradizionale con `git diff`: ogni modifica sostituisce l'intero file binario.

## 📄 Licenza

Materiale realizzato a scopo di esercitazione personale/scolastica.
