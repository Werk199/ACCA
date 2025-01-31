
#Assetto Corsa Car App (ACCA)

Introduzione
Assetto Corsa Car App (ACCA) è un'applicazione progettata per gestire e modificare i file di configurazione delle auto in Assetto Corsa. L'applicazione è suddivisa in tre sezioni principali:

- Modifica LUT: Permette di modificare i file .lut (Look-Up Table) utilizzati per le curve di coppia e potenza.
- Engine.ini: Consente di aggiungere una curva di torque personalizzata al file engine.ini.
- Drivetrain.ini: Permette di visualizzare e modificare i valori delle sezioni [GEARS], [DIFFERENTIAL], e [GEARBOX] nel file drivetrain.ini.

EXE
Potete scaricare lo zip eseguibile tramite questo link:. 
https://www.swisstransfer.com/d/72e54975-d5fb-41e6-8593-c6c84dbf3f79
- Password: PowerLut
...(Il link scadrà il 1/03/2025.)...

L’eseguibile si trova nella cartella dist all’interno dell’archivio.

Requisiti di Sistema

1. Python 3.x
   L'applicazione è scritta in Python, quindi è necessario avere Python 3.x installato.

2. Librerie Richieste
   - numpy
   - matplotlib
   - configparser
   - tkinter (incluso di default in Python)

3. Sistema Operativo
   Compatibile con Windows, macOS e Linux.

Installazione

1. Clona o Scarica il Repository
   Scarica il codice sorgente dal repository GitHub o copia il codice in un file .py.

2. Installa le Dipendenze
   Apri un terminale e installa le librerie necessarie eseguendo:
   pip install numpy matplotlib

3. Esegui l'Applicazione
   Avvia l'applicazione eseguendo il file Python:
   python ACCA.py

Funzionalità

1. Modifica LUT
   - Carica LUT
     Clicca su "Carica LUT" per selezionare un file .lut. Il file verrà caricato e visualizzato in un grafico.
   - Modifica LUT
     Clicca su "Modifica LUT" per aprire un grafico interattivo. Puoi fare clic sui punti esistenti per modificarne la posizione.
     Nota: Non è possibile aggiungere nuovi punti, solo modificare quelli esistenti.
   - Salvataggio
     Dopo aver modificato i punti, chiudi il grafico per salvare automaticamente le modifiche nel file .lut.

2. Engine.ini
   - Carica Engine.ini
     Clicca su "Carica Engine.ini" per selezionare un file engine.ini.
   - Aggiungi Curva di Torque
     Clicca su "Aggiungi Curva di Torque" per selezionare un file .lut. Il nome del file .lut verrà aggiunto alla sezione [ENGINE_DATA] del file engine.ini.
     Nota: Verrà salvato solo il nome del file (ad esempio power.lut), non il percorso completo.

3. Drivetrain.ini
   - Carica Drivetrain.ini
     Clicca su "Carica Drivetrain.ini" per selezionare un file drivetrain.ini.
   - Modifica Valori
     I valori delle sezioni [GEARS], [DIFFERENTIAL], e [GEARBOX] verranno visualizzati in una tabella.
     Fai doppio clic su un valore per modificarlo.
   - Salvataggio
     Clicca su "Salva Modifiche" per salvare le modifiche apportate al file drivetrain.ini.

Come Usare ACCA

1. Avvia l'Applicazione
   Esegui il file ACCA.py per avviare l'applicazione.

2. Seleziona la Funzionalità
   Utilizza le schede per navigare tra le diverse funzionalità:
   - Modifica LUT: Per gestire i file .lut.
   - Engine.ini: Per aggiungere una curva di torque personalizzata.
   - Drivetrain.ini: Per modificare i valori del cambio e del differenziale.

3. Carica i File
   Clicca sui pulsanti "Carica" per selezionare i file di configurazione.

4. Modifica e Salva
   Modifica i valori o i punti nel grafico e salva le modifiche.

Compilazione in un File .exe

Per rendere l'applicazione più comoda da usare, puoi compilarla in un file .exe utilizzando PyInstaller.

Passaggi per Compilare

1. Installa PyInstaller
   Apri un terminale e installa PyInstaller:
   pip install pyinstaller

2. Compila il File Python
   Naviga nella cartella contenente il file ACCA.py ed esegui:
   pyinstaller --onefile --windowed ACCA.py
   --onefile crea un singolo file .exe, mentre --windowed nasconde la console durante l'esecuzione.

3. Trova il File .exe
   Il file .exe verrà creato nella cartella dist all’interno della directory del progetto.

4. Esegui il File .exe
   Apri il file .exe per avviare l’applicazione senza bisogno di Python o delle librerie.

Note Importanti

- Backup dei File
  Prima di modificare i file di configurazione, è consigliabile fare un backup per evitare perdite di dati.

- Compatibilità
  L'applicazione è stata testata su Windows, ma dovrebbe funzionare anche su macOS e Linux con piccole modifiche.

- Segnalazione Problemi
  Se riscontri problemi o hai suggerimenti, apri una issue sul repository GitHub.

Crediti
- Sviluppatore: Alessandro Strina
- Versione: 1.0
- Licenza: MIT License

Contatti
- Email: ascode74@gmail.com

Grazie per aver scelto Assetto Corsa Car App (ACCA)! 🚗💨
```
