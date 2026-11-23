# Honda GX160 · Motore a 4 tempi — simulatore per visore VR

Simulatore didattico in realtà virtuale del motore **Honda GX160** (monocilindrico 4 tempi OHV), da usare con il visore **Meta Quest 2 / 3 / 3S**. È pensato per la lezione di classe terza sul funzionamento del motore a quattro tempi (ciclo Otto teorico).

**Prof. Giuseppe Fumuso** — Meccatronica

▶ **Apri il simulatore:** https://homeassistant500-png.github.io/Gx160-vr/

📘 **Dispensa per lo studio:** https://homeassistant500-png.github.io/Gx160-vr/dispensa-motore-4-tempi.html

🖥️ **Simulatore 3D per PC e LIM:** https://homeassistant500-png.github.io/Gx160-vr/GX160-simulatore-3D.html

---

## Cosa si può fare

- Vedere il motore appoggiato sul **banco del laboratorio virtuale** (parte a grandezza doppia; si può portare in **scala reale 1:1** o a ×3), prenderlo in mano e girarlo.
- Seguire il **ciclo Otto teorico** guidato dall'angolo di manovella (0–720°): aspirazione, compressione, scoppio ed espansione, scarico.
- Osservare le **valvole** che si aprono e si chiudono, la **scintilla** al PMS e i **gas colorati** nel cilindro.
- Aprire il motore con lo **spaccato**: vetro, sezione, solido.
- **Isolare** i gruppi di componenti: manovellismo, distribuzione, accensione, lubrificazione.
- Leggere dal **pannello di comando** i valori in tempo reale: fase, angolo, distanza dal PMS, volume nel cilindro, stato di valvole e candela, diagramma p–V qualitativo.
- Mostrare o nascondere le **etichette** sui componenti e i **termini in inglese**.
- Studiare la **dispensa direttamente nel visore**: il pulsante **DISPENSA** apre un pannello con la teoria da sfogliare a pagine e il quiz con correzione immediata.

## Dispensa per lo studio

La dispensa interattiva **«Struttura e funzionamento del motore a quattro tempi»** si apre da PC, tablet o smartphone:

https://homeassistant500-png.github.io/Gx160-vr/dispensa-motore-4-tempi.html

Contiene quattro schede:

1. **Teoria** — classificazione dei motori, struttura, le 4 fasi del ciclo, caratteristiche del motore Otto, combustione e battito in testa.
2. **Simulatore** — sezione animata del GX160 con diagramma della distribuzione e diagramma p–V, teorici e reali.
3. **Combustione** — dosatura della miscela aria-benzina e andamento della pressione con il battito in testa.
4. **Esercitazioni e quiz** — esercizi su tre livelli e quiz finale con correzione immediata.

Nel visore, il pulsante **DISPENSA** del pannello dei comandi apre un secondo pannello alla destra del banco con la **teoria** (sezioni 1.1–1.7, a pagine) e il **quiz**. Il pulsante **APRI LA DISPENSA COMPLETA** esce dalla realtà virtuale e apre questa pagina nel browser del Quest; con «indietro» si torna al simulatore.

## Simulatore 3D per PC e LIM

La versione per lo schermo del simulatore si apre da PC o dalla LIM, senza visore:

https://homeassistant500-png.github.io/Gx160-vr/GX160-simulatore-3D.html

- **Modello 3D** del GX160 da ruotare con il trascinamento e ingrandire con la rotellina; viste preimpostate: insieme, cilindro, distribuzione, manovellismo.
- **Spaccato** (vetro, sezione, solido) e **isolamento** dei gruppi di componenti: manovellismo, distribuzione, accensione, lubrificazione.
- **Ciclo Otto teorico** guidato dall'angolo di manovella 0–720°: valvole, scintilla al PMS, gas colorati; clic sulla striscia del ciclo per saltare a una fase.
- **Pannelli in tempo reale:** fase con la spiegazione, angolo, distanza dal PMS, volume nel cilindro, stato di valvole e candela, fasatura teorica e diagramma p–V qualitativo.
- **Tour automatico:** se nessuno tocca la pagina il simulatore si presenta da solo; un clic prende il controllo e dopo 25 s di inattività il tour riparte.
- Pulsante **INGLESE** per mostrare i termini tecnici anche in inglese.
- **Tasti:** spazio pausa · ← → ±15° · ↑ ↓ velocità · 1–4 viste · H nasconde i pannelli.

Il file funziona anche **senza Internet**: basta scaricare `GX160-simulatore-3D.html` e aprirlo con un doppio clic sul PC della LIM.

## Come si apre il simulatore per visore

1. Sul visore apri **Meta Quest Browser**.
2. Digita l'indirizzo del simulatore (conviene salvarlo nei preferiti).
3. Premi il pulsante rosso **ENTRA NEL VISORE** e consenti l'accesso alla realtà virtuale.

La pagina funziona solo da un indirizzo **https** (come quello di GitHub Pages): aperta come file dal disco o da un indirizzo http, il visore non entra in realtà virtuale.

Su PC o sulla LIM la stessa pagina si apre in **anteprima**: trascina per ruotare il motore, usa la rotellina per avvicinarti, clicca sul pannello per usare i comandi. Per far vedere alla classe ciò che vede lo studente nel visore, usa la funzione **Trasmetti** del Quest verso la LIM o uno smartphone.

## Comandi dei controller

| Comando | Azione |
|---|---|
| **Grilletto** | Preme i pulsanti del pannello; un clic sulla striscia del ciclo porta a quell'angolo |
| **Impugnatura** (tasto laterale) | Afferra il motore per spostarlo e girarlo |
| **Levetta destra** ← → | Ruota il motore |
| **Levetta destra** ↑ ↓ | Ingrandisce o rimpicciolisce il motore |
| **Levetta sinistra** ← → | Avanti o indietro nel ciclo |
| **A** | Pausa / avvia |
| **B** | Fase successiva |
| **X** | Spaccato successivo (vetro → sezione → solido) |
| **Y** | Isolamento successivo |

Il pulsante **RIMETTI SUL TAVOLO** del pannello riporta il motore sul banco, nella posizione iniziale.

## Dati tecnici usati

**Dati verificati** (scheda Honda Engines Europe GX160 2013; Honda Engine Assembly Information GX120/160/200):

| Grandezza | Valore |
|---|---|
| Alesaggio × corsa | 68 × 45 mm |
| Cilindrata | 163 cm³ |
| Rapporto di compressione | 9,0 : 1 (8,5 : 1 in alcune versioni) |
| Potenza netta | 3,6 kW a 3600 giri/min |
| Coppia massima | 10,3 N·m a 2500 giri/min |
| Cilindro | inclinato di 25°, canna in ghisa, raffreddamento ad aria |
| Distribuzione | valvole in testa (OHV) con aste e bilancieri, albero a camme nel basamento, ingranaggi 1:2 |
| Diametro testa valvole | aspirazione 25 mm, scarico 24 mm |
| Lubrificazione | a sbattimento (paletta sul cappello di biella) |
| Accensione | magnete transistorizzato |
| Senso di rotazione | antiorario visto dal lato PTO |

**Valori assunti** (non pubblicati da Honda, indicati con * nel simulatore):

- lunghezza della biella: 76 mm;
- alzata delle valvole: 6 mm.

**Grandezze calcolate:** volume della camera di combustione Vc = 20,4 cm³; volume al PMI = 183,9 cm³.

**Semplificazioni didattiche:**

- fasatura teorica: valvole aperte da punto morto a punto morto, scintilla esattamente al PMS;
- diagramma p–V **qualitativo** (adiabatiche con γ = 1,4, combustione istantanea a volume costante), senza valori di pressione;
- forme esterne di carter, serbatoio, filtro, marmitta, condotti e profilo delle camme schematiche: nessuna loro misura compare nei pannelli.

## File del repository

| File | Contenuto |
|---|---|
| `index.html` | Il simulatore per visore in un unico file (circa 770 KB), senza collegamenti esterni |
| `GX160-simulatore-3D.html` | Il simulatore 3D per PC e LIM in un unico file (circa 810 KB), utilizzabile anche senza Internet |
| `dispensa-motore-4-tempi.html` | La dispensa interattiva per lo studio (versione per gli studenti, senza le soluzioni degli esercizi) |
| `README.md` | Questa pagina |

Per aggiornare un file basta caricarne la nuova versione con lo stesso nome con **Add file → Upload files**: sostituisce la precedente e il sito si aggiorna in un paio di minuti.

## Materiali collegati

Fa parte della lezione sul motore a 4 tempi insieme a:

- simulatore 2D;
- simulatore 3D per la LIM (pubblicato qui) e video del tour;
- dispensa per gli alunni (pubblicata qui) e dispensa per il docente;
- presentazione.

## Riconoscimenti

- Grafica 3D realizzata con [three.js](https://threejs.org) (licenza MIT).
- Struttura del simulatore basata sul kit [teardown](https://github.com/elvarofficial/teardown) (licenza MIT).
- Caratteri Inter e JetBrains Mono (SIL Open Font License).

Honda e GX160 sono marchi dei rispettivi proprietari. Questo è un materiale didattico non ufficiale, senza legami con Honda Motor Co.
