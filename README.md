# Yakuza 3 Remastered Patch ITA
<p align="center">
  <img src="img/LogoYakuza4.png" /><br>
    Progetto per la traduzione del gioco Yakuza 3 REMASTERED in italiano.
</p>


![GitHub contributors](https://img.shields.io/github/contributors/zSavT/Yakuza3-Patch-ITA)
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/zSavT/Yakuza3-Patch-ITA/total)
[![Donate](https://img.shields.io/badge/Donate-PayPal-blue.svg)](https://www.paypal.com/paypalme/verio12)


### Un progetto collaborativo

Questo progetto nasce come un'iniziativa open source, pensata per essere sviluppata e migliorata con il contributo della community. Le fondamenta sono state gettate adattando parte del lavoro svolto per la patch di **Yakuza 4**, creando una solida base di partenza.

L'obiettivo è creare una traduzione di alta qualità grazie a uno sforzo collettivo. Chiunque può partecipare: dalla correzione di un semplice refuso al miglioramento di intere sezioni di dialogo. Ogni contributo, piccolo o grande, è essenziale per il successo del progetto. Il mio ruolo sarà quello di coordinare i lavori e revisionare le modifiche proposte.

### Ringraziamenti e risorse utili

Un ringraziamento speciale a **[Lowrentio](https://steamcommunity.com/id/Lowrentio/)** per aver condiviso i suoi tool e le sue traduzioni, risorse preziose che hanno arricchito e facilitato l'avvio del progetto.


### Come contribuire

Il tuo aiuto è fondamentale per migliorare la qualità di questa traduzione. Puoi partecipare in diversi modi, a seconda della tua familiarità con GitHub.

#### Metodo 1: Per utenti con un account GitHub (Consigliato)

Se vuoi contribuire direttamente al codice, il metodo migliore è tramite una **Pull Request**. Puoi usare un client grafico come VS Code o la riga di comando.

##### Flusso di lavoro con Visual Studio Code

1.  **Fork del Repository**:
    - Vai sulla pagina GitHub di questo repository e clicca sul pulsante **"Fork"** in alto a destra. Questo creerà una copia del progetto sul tuo account personale.

2.  **Clonare il Fork sul tuo PC**:
    - Apri Visual Studio Code.
    - Vai alla vista "Controllo del codice sorgente" (l'icona con tre pallini collegati sulla sinistra) e clicca su **"Clona repository"**.
    - Incolla l'URL del **tuo fork** (che trovi sulla pagina del tuo fork su GitHub, sotto il pulsante verde "Code").
    - Scegli una cartella sul tuo computer dove salvare il progetto.

3.  **Creare un Nuovo Branch**:
    - Una volta aperto il progetto in VS Code, clicca sul nome del branch attuale in basso a sinistra (probabilmente `main`).
    - Dal menu che appare in alto, seleziona **"Crea nuovo ramo da..."**.
    - Dai un nome descrittivo al tuo branch (es. `fix/correzione-dialogo-cap5`) e premi Invio. In questo modo, le tue modifiche saranno isolate e facili da gestire.

4.  **Applicare le Modifiche**:
    - Naviga nella cartella `File Estratti Tradotti` e apri i file `.po` che vuoi modificare.
    - Applica le tue correzioni o traduzioni.
    - **Obbligatorio:** Consulta e segui le linee guida del file **glossario.md** per mantenere la coerenza.
    - **Attenzione:** Non alterare tag e variabili come `<Color:1>`, `%s`, `%d`, `\n`, ecc.

5.  **Fare Commit e Push delle Modifiche**:
    - Torna alla vista "Controllo del codice sorgente". I file modificati appariranno nella lista.
    - Scrivi un messaggio di commit che descriva le tue modifiche (es. "Corretti refusi capitolo 5").
    - Clicca sul pulsante **"Esegui commit"**.
    - Infine, clicca su **"Sincronizza modifiche"** per caricare le modifiche sul tuo fork su GitHub.

6.  **Aprire una Pull Request (PR)**:
    - Vai sulla pagina del tuo fork su GitHub.
    - Vedrai un messaggio che ti invita a creare una **Pull Request**. Cliccaci sopra.
    - Assicurati che il branch di base sia `main` del repository originale e il branch di confronto sia quello che hai appena creato.
    - Aggiungi un titolo e una descrizione alla tua PR e clicca su **"Create pull request"**.

##### Flusso di lavoro con Git da riga di comando

1.  **Fork e Clone**: Esegui il fork del repository su GitHub, poi clonalo in locale:
    ```bash
    git clone https://github.com/TUO_USERNAME/Yakuza3-Patch-ITA.git
    cd Yakuza3-Patch-ITA
    ```

2.  **Crea un Branch**: Crea un nuovo branch per le tue modifiche:
    ```bash
    git checkout -b fix/correzione-dialogo-cap5
    ```

3.  **Modifica i File**: Applica le tue correzioni ai file `.po` nella cartella `File Estratti Tradotti`, rispettando sempre il **glossario.md**.

4.  **Aggiungi e Fai Commit**: Suddividi il lavoro in piccoli commit. Per ogni modifica logica:
    ```bash
    git add "percorso/del/file_modificato.po"
    git commit -m "Fix: Corretto refuso nel dialogo di Rikiya"
    ```

5.  **Fai Push**: Carica il tuo branch sul tuo fork:
    ```bash
    git push origin fix/correzione-dialogo-cap5
    ```

6.  **Apri una Pull Request**: Vai sulla pagina del tuo fork su GitHub e apri una Pull Request dal tuo nuovo branch verso il branch `main` del repository originale.

> **Controllo Qualità Automatico**
> Ogni Pull Request avvia un controllo automatico (GitHub Actions) che verifica la coerenza dei file `.po`. Assicurati che i controlli abbiano successo prima di richiedere una revisione.

#### Metodo 2: Invio tramite Email (per modifiche dirette)

Se non hai un account GitHub ma vuoi comunque modificare direttamente i file di traduzione, puoi seguire questa procedura:

1.  Scarica i file `.po` che desideri modificare dalla cartella `File Estratti Tradotti` di questo repository.
2.  Aprili con un editor di testo o un programma specifico come Poedit.
3.  Applica le tue correzioni, seguendo sempre le regole del **[glossario.md](glossario.md)**.
4.  Invia i file `.po` modificati all'indirizzo email: [Contatti](https://savtchannel.altervista.org/contatti-social/).

Mi occuperò io di integrare le tue modifiche nel progetto.

#### Metodo 3: Per segnalazioni rapide (tramite Issues)

Se hai notato un errore ma non vuoi modificare i file, puoi contribuire aprendo una **"Issue"**. È un modo semplice ed efficace per segnalare problemi.

1.  Vai alla sezione **Issues** del repository.
2.  Clicca su `New issue` e scegli il template **"Segnalazione Errore di Traduzione"**.
3.  Compila il modulo nel modo più dettagliato possibile, includendo:
    - **Testo errato** e la tua **proposta di correzione**.
    - **Contesto** (personaggio, capitolo, luogo).
    - Uno **screenshot** del dialogo o del menu, che è fondamentale per verificare lo spazio disponibile e il contesto.

Ogni contributo, dalla correzione di un refuso alla traduzione di intere sezioni, è prezioso per il progetto. Grazie per il tuo supporto!

# Immagini Patch



# Come installare la patch

Per installare bisogna selezionare la sezione [Releases](https://github.com/zSavT/Yakuza3-Patch-ITA/releases) su GitHub e selezionare l'ultima versione della patch disponibile. Selezionate l'installer da scaricare in base al sistema operativo scelto ed avviate l'installer.

![](img/Installer1.png)

L'installazione è guidata e semplice, ma in ogni caso basterà sempre cliccare su "_Avanti_". Attendere la verifica dell'integrità dei file della Patch e cliccare successivamente su "_Avanti_".

![](img/Installer2.png)
![](img/Installer3.png)

Successivamente bisogna accettare i termini d'uso e poi nella schermata successiva, selezionare la cartella dove è installato Yakuza 3 (Di default è impostato il percorso classico) e cliccare su "_Installa Patch_".

![](img/Installer4.png)
![](img/Installer5.png)

# Struttura dei file

- __Yakuza 3\data\2d\cse_en.pa__
    - All'interno sono presenti la maggior parte delle grafiche del gioco, in particolare quelle per l'immagine di introduzione dei capitoli e degli obbiettivi.
    - [x] Tradotto
- __Yakuza 3\data\2d\first_load_picture_en.par__
    - All'interno sono presenti le immagini degli splash screen del primo avvio del gioco.
    - [x] Tradotto
- __Yakuza 3\data\2d\tex_common_en.par__
    - All'interno sono presenti le immagini del menu del gioco.
    - [x] Tradotto
- __Yakuza 3\data\auth\subtitle.par__
    - All'interno sono presenti tutti i testi per le cutscene presenti nel gioco.
    - [x] Tradotto
- __Yakuza 3\data\bootpar\*__
    - All'interno sono presenti vari file relativi a nomi di oggetti, descrizioni e altro.
    - [x] Tradotto
- __Yakuza 3\data\db.ogre3\*__
    - Come sopra.
    - [x] Tradotto
- __Yakuza 3\data\fontpar__
    - All'interno sono presenti i dati relativi al font del gioco.
    - [x] Tradotto
- __Yakuza 3\data\hact\subtitle.par__
    - All'interno sono presenti tutti i testi non presenti nelle cutscene o nelle classi box di dialogo o menu.
    - [x] Tradotto
- __Yakuza 3\data\minigame\*__
    - All'interno sono presenti vari file relativi ai minigiochi.
    - [x] Tradotto
- __Yakuza 3\data\pause_en.par__
    - All'interno sono presenti i testi del gioco relativi ai memo ed altro.
    - [x] Tradotto
- __Yakuza 3\data\scenario_en\mail__
    - All'interno è presente il testo delle email/sms.
    - [x] Tradotto
- __Yakuza 3\data\staffrollpar__
    - All'interno sono presenti le immagini dei crediti finali del gioco.
    - [x] Tradotto
- __Yakuza 3\data\ikusei_param_en.par__
    - All'interno sono presenti i testi del gioco relativi al Colosseo.
    - [x] Tradotto ma con limitazioni
- __Yakuza 3\data\wdr_par_en\*__
    - All'interno sono presenti i file relativi ai box di dialogo della storia e alle interazioni con i negozi.
    - [x] Tradotto

# Funzionamento estrazione PAR

Per estrarre i dati dai file PAR, è necessario utilizzare il programma "_ParTool_", sviluppato da Kaplas80 e disponibile nella [repository](https://github.com/Kaplas80/ParManager.git). Nella cartella PAR è presente il tool per comodità, insieme a un file batch per ricompattare i file. Per scompattare un file PAR, è sufficiente trascinare il file sull'eseguibile; verrà creata una cartella contenente tutti i file presenti nel file PAR. Lo stesso processo, con maggiori opzioni, può essere eseguito tramite riga di comando (per maggiori informazioni, si può consultare la repository originale).

Per ricreare il file PAR dopo le modifiche, è possibile utilizzare il file batch (modificando, se necessario, solo i parametri di input e output) oppure tramite riga di comando, come nell'esempio seguente:

```
.\ParTool.exe create [nome cartella di input] [nome file par output] -c 1
```
Ovviamente, le parentesi quadre non devono essere incluse nel comando.

# Funzionamento estrazione MSG

Per i file MSG, si utilizza il programma realizzato da [BZ](https://brazilalliance.com.br/).

# Funzionamento installer

Per poter creare correttamente l'installer bisogna prima di tutto utilizzare ```packager.py``` per poter generare il file criptato della cartella "_data_". Lo script è guidato e bisogna solo indicare il percorso della cartella con le modifiche della Patch ed il nome del file pkg criptato. Nel file "chiave.txt" bisogna inserire la chiave di criptazione scelta.

## Creazione dell'eseguibile

Per poter generare l'eseguibile dello script bisogna utilizzare la libreria "__pyinstaller__" e generare l'eseguibile con i comandi in base al sistema operativo di arrivo.

### Windows

Per generare l'eseguibile dell'installer per Windows, bisogna utilizzare il seguente comando:
```ps
pyinstaller --onefile --windowed --hidden-import=webbrowser --hidden-import=pyzipper --hidden-import=sys --hidden-import=os --hidden-import=platform --hidden-import=traceback --hidden-import=PyQt6 --icon=assets/logo.png --add-data "assets:assets" --add-data "patch.pkg:." --add-data "chiave.txt:." installer.py
```
Nella cartella "_dist_", è presente l'eseguibile.
### Linux (Steam Deck)

Per generare l'eseguibile per Linux, bisogna fare qualche passaggio in più. L'installer è creato tramite la WSL per Windows.
Per prima cosa bisogna creare l'ambiente virtuale per Python tramite il comando:
```ps
python3 -m venv venv
```
Se non fosse presente la funzione nell'ambiente, si può installare tramite il seguente comando:
```ps
sudo apt-get install -y python3-venv
```
Con il comando seguente, attiviamo l'ambiente:
```ps
source venv/bin/activate
```
Dopo aver attivato l'ambiente bisogna installare pyinstaller con il comando:
```ps
pip3 install pyinstaller
```
Se pip non è presente nell'ambiente, bisogna installarlo con il comando:
```ps
sudo apt install -y python3-pip
```
Successivamente bisogna installare tutte le librerie utilizzate, presenti nel file requirements.txt, che in ogni caso sono:

- PyQt6
- pyzipper

Successivamente bisogna avviare il comando per la creazione del file eseguibile:
```ps
pyinstaller --onefile --windowed --hidden-import=webbrowser --hidden-import=pyzipper --hidden-import=sys --hidden-import=os --hidden-import=platform --hidden-import=traceback --hidden-import=PyQt6 --icon=assets/logo.png --add-data "assets:assets" --add-data "patch.pkg:." --add-data "chiave.txt:." installer.py
```

Una volta terminato, si può disattivare l'ambiente con il comando:
```ps
deactivate
```

Nella cartella "_dist_", è presente l'eseguibile (la versione per Linux non ha tipo/estensione).


# Altre patch della serie

Lista dei progetti di patch in italiano per i giochi della serie:
- [Yakuza 0](https://letraduzionidirulesless.wordpress.com/yakuza0-2/)
    - Come indicato nell'introduzione, la patch di Yakuza 0 è l'unica completa al 100% (o quasi).
    - La versione Director's Cut presenta la lingua italiana.
- Yakuza Kiwami 1, 2 e 3
   - Ufficialmente tradotti in italiano nelle nuove versioni.
- Yakuza 3 Remastered
    - Questo progetto.
- [Yakuza 4 Remastered](https://github.com/zSavT/Yakuza4-Patch-ITA)
    - Un'altra patch realizzata da me per la serie Yakuza è quella di Yakuza 4, il funzionamento ed il materiale tradotto sono gli stessi.
- [Yakuza 5 Remastered](https://github.com/zSavT/Yakuza5-Patch-ITA)
    - Un'altra patch realizzata da me per la serie Yakuza è quella di Yakuza 5, il funzionamento ed il materiale tradotto sono gli stessi.
- [Yakuza 6](https://github.com/zSavT/Yakuza6-Patch-ITA)
    - Un'altra patch realizzata da me per la serie Yakuza è quella di Yakuza 6.


## Dipendenza e ringraziamenti
Si ringrazia

- Per la codifica e la decodifica dei file _PAR_ del gioco, si utilizza il programma sviluppato nella [repo](https://github.com/Kaplas80/ParManager.git) da Kaplas80.<br>
- Per la codifica dei file _MSG_, _BIN_ del gioco, si utilizza il programma sviluppato da [BZ](https://brazilalliance.com.br/).

## Copyright
This patch does not contain copyrighted material, has no functional autonomy, and you must have your own original copy to apply it.
All game rights, intellectual property, logo/names, and movies/images are property of Sega Corporation.

# Altri progetti di traduzione realizzati da me
[Valkyria Chronicles Patch ITA](https://github.com/zSavT/Valkyria-Chronicles-Patch-ITA)


[Digimon Story Cyber Sleuth: Complete Edition](https://github.com/zSavT/Digimon-Story-Cyber-Sleuth-Patch-ITA.git)
