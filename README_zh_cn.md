[🇨🇳 返回语言选择](./README.md)
# 什么是 Utaun？  
  
Utaun 是一款 Windows 软件，仅通过完全无生物的复合正弦波建模（CSM语音合成）为 UTAU 生成 CV（辅音-元音）音源。  
它支持在“文档”文件夹中自动生成音源 ZIP，以及直接导出到各种兼容 UTAU 的软件。  

# 特点  

* 运行后可在文档文件夹中自动生成音源 ZIP，或直接导出至兼容软件。  
* 通过完全无生物的复合正弦波建模（CSM语音合成）生成元音（A、I、U、E、O、N）。  
* 将附带的辅音和浊音文件夹放置在文档目录中即可生成 CV 音源。  
* 在程序内自动生成 m、n、y、w 行。  
* 支持平假名别名 + 英语罗马字别名（发音全部为日语）。  
* 自动生成 `oto.ini`、`character.txt` 和 `readme.txt`。  
* 同时将 PNG 图像转换为 JPG 和 BMP 格式（注：`character.txt` 使用的是 JPG）。  
* `readme.txt` 和 `character.txt` 的编码可在 **Shift-JIS (ANSI)** 和 **UTF-8** 之间选择（注：UTF-8 兼容 OpenUTAU 等软件）。  
* 可以更改基频（音高）。  
* 可以自由设置音源名称（角色名）。  
* **支持浅色和深色模式。**  
* **支持选择导出目标。**  

# 预期用途  

* 想要使用无生物或人工声音制作 UTAU 音源时。  
* 不擅长或不方便用自己的声音进行录音时的音源制作。  
* 研究复合正弦波建模（CSM语音合成）音频素材。  
* 自制音源的原型制作。  
* 解压生成的 ZIP，直接用作人工 Vocaloid 素材。  
* 作为视频混音（如鬼畜音MAD、YTPMV 等）的音频素材。  

# 如何使用 Utaun  

① 从 **[GitHub Releases](#Releases)** 下载最新版本的 Utaun。  
② 如果您下载的是 ZIP 文件夹版本，**请将“辅音/浊音文件夹”和 `oto.ini` 直接放在“文档”文件夹中（也支持 OneDrive 文档）。**（注：如果使用安装程序版本，会自动放置）  
③ 将 `Utaun.exe` 放在您喜欢的任意文件夹中。  
④ 启动 `Utaun.exe` 并按照屏幕上的说明创建您的音源。  
⑤ 作为数据保存位置，除了 ZIP 输出（文档等）之外，还可以选择直接以文件夹形式导出到 UTAU 和 OpenUTAU。  
*注：自动更新功能将在以后的版本中提供。*  

### UI 界面  
![Test Image 3](IMG_4239.jpeg)  

# 生成音源的对应与使用方法  

* **UTAU**  
  在应用内直接以音源文件夹状态导出到 `voice` 文件夹中即可直接使用。  
* **OpenUTAU**  
  在应用内直接以音源文件夹状态导出到 `Singers` 文件夹中即可直接使用。  
* **UtauTTS**  
  解压导出的 ZIP 文件，并将其放入 `utauTTS` 的 `voice` 文件夹中。  
* **UtauV**  
  将 ZIP 格式的文件拖放到正在运行的 UtauV 应用程序窗口中。  
* **UTAlet（网页版）**  
  将 ZIP 格式的文件拖放到官方网站界面上。  
*注：有关各个软件或网页环境中的具体使用方法，请参考各自的帮助文件、手册或官方文档。*  

# 运行环境  

* Windows 10 至 11（支持 64位 / 32位）  
**(Note: 出于文件大小等考量，以 32位版本为基准，但在 64位 Windows 上也能正常运行。)**  

# 不支持的功能  

* 浊元音（浊音、带浊音的元音类）  
* 耳语、呼吸声、气声等表情差异  
* 拗音（kya、kyu、kyo / sha、shu、sho 等）  
* 连续音（VCV）  
* CVVC  
* 其他特殊发音  

# 使用条款  

关于 Utaun 本体（`Utaun.exe`），严禁以下行为：  
* 加工  
* 编辑  
* 改造  
* 商业用途  
* 再分发  
* 反编译（拆解）  

# 关于生成的内容  

（音源、`.wav` 文件、`icon.jpg` / `icon.bmp`、`oto.ini` 等）  
您（发布者）可以自由设置生成内容的使用条款。  
请在 `readme.txt` 中编写您喜欢的使用许可条款。  

有关更新信息和详细信息，请查看 GitHub **Releases** 页面。  

# Releases  
[Download Simplified Chinese Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇨🇳)

### 关于Utaun 的再分发许可
[关于Utaun 的再分发许可**→**](./关于Utaun的再分发许可.md)

