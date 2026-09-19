[🇹🇼 返回語言選擇](./README.md)​
# 什麼是 Utaun？  
  
Utaun 是一款 Windows 軟體，僅透過完全無生物的複合正弦波建模（CSM語音合成）為 UTAU 生成 CV（輔音-元音）音源。  
它支援在「文件」資料夾中自動產生音源 ZIP，以及直接匯出至各種相容 UTAU 的軟體。  

# 特點  

* 執行後可在文件資料夾中自動產生音源 ZIP，或直接匯出至相容軟體。  
* 透過完全無生物的複合正弦波建模（CSM語音合成）生成元音（A、I、U、E、O、N）。  
* 將附帶的輔音和濁音資料夾放置在文件目錄中即可生成 CV 音源。  
* 在程式內自動生成 m、n、y、w 行。  
* 支援平假名別名 + 英語羅馬字別名（發音全部為日語）。  
* 自動生成 `oto.ini`、`character.txt` 和 `readme.txt`。  
* 同時將 PNG 影像轉換為 JPG 和 BMP 格式（註：`character.txt` 使用的是 JPG）。  
* `readme.txt` 和 `character.txt` 的編碼可在 **Shift-JIS (ANSI)** 和 **UTF-8** 之間選擇（註：UTF-8 相容 OpenUTAU 等軟體）。  
* 可以更改基頻（音高）。  
* 可以自由設定音源名稱（角色名）。  
* **支援淺色和深色模式。**  
* **支援選擇匯出目標。**  

# 預期用途  

* 想要使用無生物或人工聲音製作 UTAU 音源時。  
* 不擅長或不方便用自己的聲音進行錄音時的音源製作。  
* 研究複合正弦波建模（CSM語音合成）音頻素材。  
* 自製音源的原型製作。  
* 解壓生成的 ZIP，直接用作人工 Vocaloid 素材。  
* 作為影片混音（如鬼畜音MAD、YTPMV 等）的音頻素材。  

# 如何使用 Utaun  

① 從 **[GitHub Releases](#Releases)** 下載最新版本的 Utaun。  
② 如果您下載的是 ZIP 資料夾版本，**請將「輔音/濁音資料夾」和 `oto.ini` 直接放在「文件」資料夾中（也支援 OneDrive 文件）。**（註：如果使用安裝程式版本，會自動放置）  
③ 將 `Utaun.exe` 放在您喜歡的任意資料夾中。  
④ 啟動 `Utaun.exe` 並按照螢幕上的說明建立您的音源。  
⑤ 作為資料儲存位置，除了 ZIP 輸出（文件等）之外，還可以選擇直接以資料夾形式匯出到 UTAU 和 OpenUTAU。  
*註：自動更新功能將在以後的版本中提供。*  

### UI 介面  
![Test Image 3](IMG_4239.jpeg)  

# 生成音源的對應與使用方法  

* **UTAU**  
  在應用內直接以音源資料夾狀態匯出到 `voice` 資料夾中即可直接使用。  
* **OpenUTAU**  
  在應用內直接以音源資料夾狀態匯出到 `Singers` 資料夾中即可直接使用。  
* **UtauTTS**  
  解壓匯出的 ZIP 檔案，並將其放入 `utauTTS` 的 `voice` 資料夾中。  
* **UtauV**  
  將 ZIP 格式的檔案拖放到正在執行的 UtauV 應用程式視窗中。  
* **UTAlet（網頁版）**  
  將 ZIP 格式的檔案拖放到官方網站介面上。  
*註：有關各個軟體或網頁環境中的具體使用方法，請參考各自的說明檔、手冊或官方文件。*  

# 執行環境  

* Windows 10 至 11（支援 64位元 / 32位元）  
**(註：基於檔案大小等考量，以 32位元版本為基準，但在 64位元 Windows 上也能正常執行。)**  

# 不支援的功能  

* 濁元音（濁音、帶濁音的元音類）  
* 耳語、呼吸聲、氣聲等表情差異  
* 拗音（kya、kyu、kyo / sha、shu、sho 等）  
* 連續音（VCV）  
* CVVC  
* 其他特殊發音  

# 使用條款  

關於 Utaun 本體（`Utaun.exe`），嚴禁以下行為：  
* 加工  
* 編輯  
* 改造  
* 商業用途  
* 再分發  
* 反編譯（拆解）  

# 關於生成的內容  

（音源、`.wav` 檔案、`icon.jpg` / `icon.bmp`、`oto.ini` 等）  
您（發布者）可以自由設定生成內容的使用條款。  
請在 `readme.txt` 中編寫您喜歡的使用許可條款。  

有關更新資訊和詳細資訊，請查看 GitHub **Releases** 頁面。  

# Releases  
[Download Traditional Chinese Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇹🇼)
