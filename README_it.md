[🇮🇹 Torna alla selezione della lingua](./README.md)
​# Cos'è Utaun?  
  
Utaun è un software per Windows che genera voicebank CV (Consonante-Vocale) per UTAU utilizzando esclusivamente la modellazione sinusoidale composita (sintesi vocale CSM) puramente inanimata.  
Supporta la generazione automatica di archivi ZIP di voicebank nella cartella Documenti, nonché l'esportazione diretta verso vari software compatibili con UTAU.  

# Funzionalità  

* Genera automaticamente un file ZIP del voicebank nella cartella Documenti o lo esporta direttamente in un software compatibile all'avvio.  
* Genera vocali (A, I, U, E, O, N) tramite la modellazione sinusoidale composita (sintesi vocale CSM) puramente inanimata.  
* Configura le cartelle di consonanti e suoni sonori incluse nella directory Documenti per generare voicebank CV.  
* Genera automaticamente le righe m, n, y e w all'interno del programma.  
* Supporta alias in Hiragana + alias in Romaji inglese (tutti pronunciati in giapponese).  
* Genera automaticamente `oto.ini`, `character.txt` e `readme.txt`.  
* Converte simultaneamente le immagini PNG nei formati JPG e BMP (Nota: il JPG viene utilizzato per `character.txt`).  
* La codifica di `readme.txt` e `character.txt` può essere scelta tra **Shift-JIS (ANSI)** e **UTF-8** (Nota: l'UTF-8 garantisce la compatibilità con OpenUTAU e altri).  
* Consente di modificare la frequenza fondamentale (altezza della voce).  
* Nome del voicebank (nome del personaggio) liberamente personalizzabile.  
* **Supporta le modalità Chiara e Scura.**  
* **Consente di scegliere la destinazione di esportazione.**  

# Uso previsto  

* Quando desideri creare voicebank UTAU utilizzando voci inanimate o artificiali.  
* Per la produzione di voicebank se trovi difficile o scomodo registrare con la tua voce.  
* Ricerca di materiali audio basati sulla modellazione sinusoidale composita (sintesi vocale CSM).  
* Prototipazione di voicebank personalizzati.  
* Decomprimere lo ZIP generato per usarlo direttamente come risorse di vocaloid simulate da umani.  
* Utilizzo come materiali audio per remix video (ad es. OtoMAD, YTPMV).  

# Come usare Utaun  

① Scarica l'ultima versione di Utaun da **[GitHub Releases](#Releases)**.  
② Se stai scaricando la versione in cartella ZIP, **posiziona le cartelle "Consonant/Voiced Sound" e `oto.ini` direttamente all'interno della cartella "Documenti" (sono supportati anche i Documenti di OneDrive).** (Nota: vengono posizionate automaticamente se usi la versione con installatore).  
③ Posiziona `Utaun.exe` in una cartella a tua scelta.  
④ Avvia `Utaun.exe` e segui le istruzioni sullo schermo per creare il tuo voicebank.  
⑤ Come posizione di salvataggio dei dati, puoi scegliere tra l'output ZIP (Documenti, ecc.) o l'esportazione diretta della cartella su UTAU e OpenUTAU.  
*Nota: La funzione di aggiornamento automatico sarà disponibile nelle versioni future.*  

### Immagine dell'interfaccia (UI)  
![Test Image 3](IMG_4239.jpeg)  

# Compatibilità e utilizzo dei voicebank generati  

* **UTAU**  
  Esporta direttamente come cartella di voicebank non compressa nella cartella `voice` dall'interno dell'app e usala immediatamente.  
* **OpenUTAU**  
  Esporta direttamente come cartella di voicebank non compressa nella cartella `Singers` dall'interno dell'app e usala immediatamente.  
* **UtauTTS**  
  Estrai il file ZIP esportato e posizionalo nella cartella `voice` di `utauTTS`.  
* **UtauV**  
  Trascina e rilascia il file ZIP nella finestra dell'applicazione UtaunV in esecuzione.  
* **UTAlet (Versione Web)**  
  Trascina e rilascia il file ZIP sullo schermo del sito web ufficiale.  
*Nota: Per istruzioni d'uso specifiche in ciascun software o ambiente web, fare riferimento ai rispettivi file di guida, manuali o documentazione ufficiale.*  

# Requisiti di sistema  

* Windows 10 - 11 (supporto 64 bit / 32 bit)  
**(Nota: La versione a 32 bit viene utilizzata come base per motivi di dimensioni dei file, ma funziona senza problemi anche su Windows a 64 bit.)**  

# Funzionalità non supportate  

* Vocali sonore (あ゙, い゙, ゔ, え゙, お゙)  
* Variazioni espressive come sussurri, respiri o componenti di soffio  
* Suoni palatalizzati (es.: kya, kyu, kyo / sha, shu, sho)  
* VCV (Vocali continue)  
* CVVC  
* Altre pronunce speciali  

# Termini di utilizzo  

Le seguenti azioni sono severamente vietate per quanto riguarda l'applicazione Utaun in sé (`Utaun.exe`):  
* Modifica  
* Editing  
* Alterazione  
* Uso commerciale  
* Ristribuzione  
* Decompilazione (disassemblaggio)  

# Contenuto generato  

(Voicebank, file `.wav`, `icon.jpg` / `icon.bmp`, `oto.ini`, ecc.)  
Tu (il distributore) sei libero di stabilire i tuoi termini di utilizzo per i contenuti generati.  
Si prega di scrivere i termini di licenza preferiti all'interno di `readme.txt`.  

Per informazioni sugli aggiornamenti e dettagli, controlla la pagina **Releases** su GitHub.  

# Releases  
[Download Italian Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇮🇹)
