# Honda GX160 · Motore a 4 tempi — simulatore per visore VR

Simulatore didattico in realtà virtuale del motore **Honda GX160** (monocilindrico 4 tempi OHV), da usare con il visore **Meta Quest 2 / 3 / 3S**. È pensato per la lezione di classe terza sul funzionamento del motore a quattro tempi (ciclo Otto teorico).

**Prof. Giuseppe Fumuso** — Meccatronica, IIS "Orso Mario Corbino", Partinico (PA)

▶ **Apri il simulatore:** https://homeassistant500-png.github.io/Gx160-vr/

---

## Cosa si può fare

- Vedere il motore **in scala reale** appoggiato su un tavolo virtuale, prenderlo in mano, girarlo e ingrandirlo fino a ×3.
- Seguire il **ciclo Otto teorico** guidato dall'angolo di manovella (0–720°): aspirazione, compressione, scoppio ed espansione, scarico.
- Osservare le **valvole** che si aprono e si chiudono, la **scintilla** al PMS e i **gas colorati** nel cilindro.
- Aprire il motore con lo **spaccato**: vetro, sezione, solido.
- **Isolare** i gruppi di componenti: manovellismo, distribuzione, accensione, lubrificazione.
- Leggere dal **pannello di comando** i valori in tempo reale: fase, angolo, distanza dal PMS, volume nel cilindro, stato di valvole e candela, diagramma p–V qualitativo.
- Mostrare o nascondere le **etichette** sui componenti e i **termini in inglese**.

## Come si apre

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

Il pulsante **RIMETTI SUL TAVOLO** del pannello riporta il motore nella posizione iniziale.

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
| `index.html` | Il simulatore completo in un unico file (circa 770 KB), senza collegamenti esterni |
| `README.md` | Questa pagina |

Per aggiornare il simulatore basta caricare la nuova versione di `index.html` con **Add file → Upload files**: sostituisce la precedente e il sito si aggiorna in un paio di minuti.

## Materiali collegati

Fa parte della lezione sul motore a 4 tempi insieme a:

- simulatore 2D;
- simulatore 3D per la LIM (con tour automatico e video);
- dispensa per gli alunni e dispensa per il docente;
- presentazione.

## Riconoscimenti

- Grafica 3D realizzata con [three.js](https://threejs.org) (licenza MIT).
- Struttura del simulatore basata sul kit [teardown](https://github.com/elvarofficial/teardown) (licenza MIT).
- Caratteri Inter e JetBrains Mono (SIL Open Font License).

Honda e GX160 sono marchi dei rispettivi proprietari. Questo è un materiale didattico non ufficiale, senza legami con Honda Motor Co.
