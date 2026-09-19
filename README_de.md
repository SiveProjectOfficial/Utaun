[🇩🇪 Zurück zur Sprachauswahl](./README.md)
# Was ist Utaun?  
  
Utaun ist eine Windows-Software, die CV-Voicebanks (Konsonant-Vokal) für UTAU unter Verwendung ausschließlich unbeseelter kompositer Sinusoidenmodellierung (CSM-Sprachsynthese) generiert.  
Sie unterstützt die automatische Erstellung von Voicebank-ZIP-Archiven im Dokumente-Ordner sowie den direkten Export in verschiedene UTAU-kompatible Programme.  

# Funktionen  

* Erstellt beim Ausführen automatisch eine Voicebank-ZIP im Dokumente-Ordner oder exportiert sie direkt in kompatible Software.  
* Generiert Vokale (A, I, U, E, O, N) durch ausschließlich unbeseelte komposite Sinusoidenmodellierung (CSM-Sprachsynthese).  
* Platzieren Sie die mitgelieferten Konsonanten- und Stimmhaften-Ordner im Dokumente-Verzeichnis, um CV-Voicebanks zu generieren.  
* Automatische Erstellung von m-, n-, y- und w-Reihen direkt im Programm.  
* Unterstützt Hiragana-Aliase + englische Romaji-Aliase (alle Aussprachen auf Japanisch).  
* Automatische Erstellung von `oto.ini`, `character.txt` und `readme.txt`.  
* Konvertiert PNG-Bilder gleichzeitig in die Formate JPG und BMP (Hinweis: Für `character.txt` wird JPG verwendet).  
* Die Kodierung von `readme.txt` und `character.txt` kann zwischen **Shift-JIS (ANSI)** und **UTF-8** gewählt werden (Hinweis: UTF-8 bietet Kompatibilität mit OpenUTAU und anderen).  
* Die Grundfrequenz (Tonhöhe) iständerbar.  
* Frei anpassbarer Voicebank-Name (Charaktername).  
* **Unterstützt den Hell- und Dunkelmodus.**  
* **Erlaubt die Wahl des Exportziels.**  

# Verwendungszweck  

* Wenn Sie UTAU-Voicebanks mit unbeseelten oder künstlichen Stimmen erstellen möchten.  
* Für die Voicebank-Produktion, wenn Ihnen die Aufnahme mit der eigenen Stimme schwerfällt oder unangenehm ist.  
* Erforschung von Audiomaterialien auf Basis kompositer Sinusoidenmodellierung (CSM-Sprachsynthese).  
* Prototyping eigener Voicebanks.  
* Entpacken der generierten ZIP-Datei, um sie direkt als menschlich simulierte Vocaloid-Assets zu verwenden.  
* Verwendung als Audiomaterial für Videoremixes (z. B. OtoMAD, YTPMV).  

# Verwendung von Utaun  

① Laden Sie die neueste Version von Utaun von **[GitHub Releases](#Releases)** herunter.  
② Wenn Sie die ZIP-Ordnerversion herunterladen, **platzieren Sie die Ordner „Consonant/Voiced Sound“ und `oto.ini` direkt in Ihrem „Dokumente“-Ordner (OneDrive-Dokumente werden ebenfalls unterstützt).** (Hinweis: Bei Verwendung des Installers geschieht dies automatisch).  
③ Platzieren Sie `Utaun.exe` in einem Ordner Ihrer Wahl.  
④ Starten Sie `Utaun.exe` und folgen Sie den Anweisungen auf dem Bildschirm, um Ihre Voicebank zu erstellen.  
⑤ Als Datenspeicherort können Sie zwischen ZIP-Ausgabe (Dokumente etc.) oder direktem Ordner-Export für UTAU und OpenUTAU wählen.  
*Hinweis: Die automatische Update-Funktion wird in zukünftigen Versionen verfügbar sein.*  

### Benutzeroberfläche (UI)  
![Test Image 3](IMG_4239.jpeg)  

# Kompatibilität und Verwendung der generierten Voicebanks  

* **UTAU**  
  Exportieren Sie die Voicebank direkt als unkomprimierten Ordner aus der App heraus in Ihren `voice`-Ordner und verwenden Sie sie sofort.  
* **OpenUTAU**  
  Exportieren Sie die Voicebank direkt als unkomprimierten Ordner aus der App heraus in Ihren `Singers`-Ordner und verwenden Sie sie sofort.  
* **UtauTTS**  
  Entpacken Sie die exportierte ZIP-Datei und legen Sie sie in den `voice`-Ordner von `utauTTS`.  
* **UtauV**  
  Ziehen Sie die ZIP-Datei per Drag & Drop in das Fenster der laufenden UtauV-Anwendung.  
* **UTAlet (Web-Version)**  
  Ziehen Sie die ZIP-Datei per Drag & Drop auf die Benutzeroberfläche der offiziellen Website.  
*Hinweis: Spezifische Anweisungen zur Verwendung in der jeweiligen Software oder Web-Umgebung entnehmen Sie bitte den entsprechenden Hilfedateien, Handbüchern oder der offiziellen Dokumentation.*  

# Systemanforderungen  

* Windows 10 bis 11 (64-Bit / 32-Bit unterstützt)  
**(Hinweis: Aus Gründen der Dateigröße dient die 32-Bit-Version als Basis, das Programm läuft jedoch problemlos auch auf 64-Bit-Windows.)**  

# Nicht unterstützte Funktionen  

* Stimmhafte Vokale (あ゙, い゙, ゔ, え゙, お゙)  
* Expressive Variationen wie Flüstern, Atemgeräusche oder Hauchkomponenten  
* Palatalisierte Laute (z. B. kya, kyu, kyo / sha, shu, sho)  
* VCV (Kontinuierliche Vokale)  
* CVVC  
* Sonstige Spezialaussprachen  

# Nutzungsbedingungen  

Für die Utaun-Anwendung selbst (`Utaun.exe`) sind folgende Handlungen strengstens untersagt:  
* Modifikation  
* Bearbeitung  
* Umbau  
* Kommerzielle Nutzung  
* Weiterverteilung  
* Dekompilierung (Disassemblierung)  

# Generierte Inhalte  

(Voicebanks, `.wav`-Dateien, `icon.jpg` / `icon.bmp`, `oto.ini` usw.)  
Es steht Ihnen (dem Distributor) frei, eigene Nutzungsbedingungen für die generierten Inhalte festzulegen.  
Bitte schreiben Sie Ihre bevorzugten Lizenzbedingungen in die `readme.txt`.  

Informationen zu Updates und Details finden Sie auf der **Releases**-Seite auf GitHub.  

# Releases  
[Download German Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇩🇪)
