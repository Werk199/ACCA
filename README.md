# Assetto Corsa Car App (ACCA)

## Introduzione
**Assetto Corsa Car App (ACCA)** è un'applicazione progettata per gestire e modificare i file di configurazione delle auto in Assetto Corsa. L'applicazione è suddivisa in tre sezioni principali:

- **Modifica LUT**: Permette di modificare i file `.lut` (Look-Up Table) utilizzati per le curve di coppia e potenza.
- **Engine.ini**: Consente di aggiungere una curva di torque personalizzata al file `engine.ini`.
- **Drivetrain.ini**: Permette di visualizzare e modificare i valori delle sezioni `[GEARS]`, `[DIFFERENTIAL]`, e `[GEARBOX]` nel file `drivetrain.ini`.

---

## EXE
Potete scaricare lo zip eseguibile tramite questo link:  
[**Download Eseguibile**](https://www.swisstransfer.com/d/72e54975-d5fb-41e6-8593-c6c84dbf3f79)  
**Password:** `PowerLut`  
> Il link scadrà il **1/03/2025**.

L’eseguibile si trova nella cartella **dist** all’interno dell’archivio.

---

## Requisiti di Sistema

1. **Python 3.x**  
   L'applicazione è scritta in Python, quindi è necessario avere Python 3.x installato.

2. **Librerie Richieste**  
   - `numpy`
   - `matplotlib`
   - `configparser`
   - `tkinter` (incluso di default in Python)

3. **Sistema Operativo**  
   Compatibile con Windows, macOS e Linux.

---

## Installazione

1. **Clona o Scarica il Repository**  
   Scarica il codice sorgente dal repository GitHub o copia il codice in un file `.py`.

2. **Installa le Dipendenze**  
   Apri un terminale e installa le librerie necessarie eseguendo:
   ```bash
   pip install numpy matplotlib
