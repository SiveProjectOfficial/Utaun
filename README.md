#  Utaun日本語ページ

**Select Language**  
[🇯🇵 日本語](./README.md)  
[🇬🇧 English](./README_uk.md)  
[🇺🇸 English](./README_en.md)  
[🇰🇷 한국어](./README_ko.md)  
[🇨🇳 简体中文](./README_zh_cn.md)   
[🇹🇼 繁體中文](./README_zh_tw.md)   
[🇭🇰 廣東話](./README_zh_hk.md)  
[🇷🇺 Русский](./README_ru.md)   
[🇵🇹 Português](./README_pt.md)   
[🇪🇸 Español](./README_es.md)   
[🇫🇷 Français](./README_fr.md)   
[🇮🇹 Italiano](./README_it.md)   
[🇩🇪 Deutsch](./README_de.md)   
[🇵🇱 Polski](./README_pl.md)  
[🇹🇷 Türkçe](./README_tr.md)   
[🇻🇳 Tiếng Việt](./README_vi.md)   
[🇵🇭 Filipino](./README_ph.md)  
[🇹🇭 ไทย](./README_th.md)   

---

# 【Utaunとは？】

完全無生物の加算合成だけで UTAU 用の CV 音源を生成する Windows ソフトです。
ドキュメントへの ZIP 自動生成や、各 UTAU 関連ソフトへの直接エクスポートに対応しています。

# 【特徴】

* 実行するとドキュメントに音源 ZIP を自動生成、または各ソフトへ直接エクスポート
* 完全無生物の加算合成による母音生成（あ・い・う・え・お・ん）
* 同梱されている子音部・濁音部フォルダをドキュメントにセットして CV 音源を生成
* m / n / y / w 行をプログラム内で自動生成
* ひらがなエイリアス + 英語ローマ字エイリアスに対応（発音はすべて日本語）
* oto.ini / character.txt / readme.txt を自動生成します
* PNG 画像を JPG と BMP に同時変換します（※ character.txt に使用されるのは JPG です）
* readme.txt と character.txt のエンコードは **Shift-JIS（ANSI）** と **UTF-8** を選択可能（※ UTF-8 は OpenUTAU 等で互換性があります）
* 基本周波数（声の高さ）を変更できます
* 音源名（キャラクター名）を自由に設定できます
* **ライトモードとダークモードに対応**
* **エクスポート先の選択が可能**

# 【想定用途】

* 無生物の声で UTAU 音源を作りたい時
* 地声で録音するのが苦手な人向けの音源制作
* 加算合成音声の素材研究
* 自作音源のプロトタイピング
* ZIP を解凍して、そのまま人力ボカロ素材として使う用途
* 音MAD・YTPMV などの素材としての用途

# 【Utaunの使用方法】

① [**GitHub Releases**](#Releases)から最新の Utaun をダウンロードします。  
② ZIPフォルダをダウンロードされる場合は、**「子音部・濁音部フォルダ」と「oto.ini」を「ドキュメント」フォルダ（OneDrive内のドキュメントでもOK）の中に直接置いてください。**（※インストーラー版をご利用の場合は自動で配置されます）  
③ Utaun.exe を任意のフォルダに置きます。  
④ Utaun.exe を起動し、画面の指示に従って音源を作成します。  
⑤ データの保存先として、ZIP出力（ドキュメント等）のほか、UTAUとOpenUTAUへのフォルダ状態での直接エクスポートが選択できます。  
※ 今後のバージョンからは自動アップデート機能がご利用いただけます。  

### UIイメージ  
 ![Test Image 3](IMG_4239.jpeg)

# 【生成した音源の対応・使用方法】

* **UTAU**
  アプリ内から `voice` フォルダへ音源フォルダの状態で直接エクスポートしてそのまま使用できます。
* **OpenUTAU**
  アプリ内から `Singers` フォルダへ音源フォルダの状態で直接エクスポートしてそのまま使用できます。
* **UtauTTS**
  ZIPとして出力されたファイルを解凍し、`utauTTS` の `voice` フォルダに入れて使用します。
* **UtauV**
  ZIP形式のファイルを、UtauV アプリを開いた状態のところにドラッグ＆ドロップ（D&D）して使用します。
* **UTAlet（Web版）**
  ZIP形式のファイルを、公式サイトの画面にドラッグ＆ドロップ（D&D）して使用します。
※ 各ソフト・WEB環境での具体的な利用方法は、それぞれのヘルプ・マニュアル・公式ドキュメントをご参照ください。

# 【動作環境】

* Windows 10 〜 11 （64bit / 32bit対応）  
  **(※PC容量の都合等により32bit版を基準としていますが、64bit版Windowsでも問題なく動作します)**

# 【未対応】

* 濁音母音（あ゙・い゙・ゔ・え゙・お゙）
* 囁き・ブレス・息成分などの表情差分
* 拗音（きゃ・きゅ・きょ / しゃ・しゅ・しょ など）
* 連続音（VCV）
* CVVC
* その他の特殊発音

# 【利用規約】

Utaun 本体（Utaun.exe）では以下の行為は禁止されます。
* 加工
* 編集
* 改造
* 商用利用
* 再配布
* デコンパイル（分解）

# 【生成物について】

（音源・wav・icon.jpg / icon.bmp・oto.ini など）
利用規約は、あなた（配布者）が自由に設定できます。
readme.txt にお好きな規約を書いてください。

アップデート情報や詳細については、GitHubの **Releases** をご覧ください。

# Releases
[日本語版Utaunダウンロード先**→**](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇯🇵)

