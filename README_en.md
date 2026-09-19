[🇺🇸 Back to Language Selection](./README.md)​
# What is Utaun?

Utaun is a Windows software that generates CV (Consonant-Vowel) voicebanks for UTAU using purely inanimate additive synthesis.
It supports automated ZIP file generation in your Documents folder as well as direct exports to various UTAU-compatible software.

# Features

* Automatically generates a voicebank ZIP in your Documents folder or exports directly to compatible software upon execution.
* Generates vowels (A, I, U, E, O, N) through purely inanimate additive synthesis.
* Set the included consonant and voiced sound folders in your Documents directory to generate CV voicebanks.
* Automatically generates m, n, y, and w rows within the program.
* Supports Hiragana aliases + English Romaji aliases (all pronounced in Japanese).
* Automatically generates `oto.ini`, `character.txt`, and `readme.txt`.
* Simultaneously converts PNG images into JPG and BMP formats (Note: JPG is used for `character.txt`).
* `readme.txt` and `character.txt` encoding can be selected between **Shift-JIS (ANSI)** and **UTF-8** (Note: UTF-8 provides compatibility with OpenUTAU and others).
* Allows you to change the fundamental frequency (pitch).
* Freely customizable voicebank name (character name).
* **Supports both Light and Dark modes.**
* **Allows you to choose your export destination.**

# Intended Use

* When you want to create UTAU voicebanks using inanimate or artificial voices.
* For voicebank production if you find it difficult or uncomfortable to record with your own voice.
* Researching additive synthesis audio materials.
* Prototyping custom voicebanks.
* Unzipping the generated ZIP to use directly as human-made vocaloid (human-vocal simulation) assets.
* Using as audio materials for video remixes (e.g., OtoMAD, YTPMV).

# How to Use Utaun

① Download the latest version of Utaun from **[GitHub Releases](#Releases)**.  
② If you are downloading the ZIP folder version, **place the "Consonant/Voiced Sound folders" and `oto.ini` directly inside your "Documents" folder (OneDrive Documents are also supported).** (Note: These are automatically placed if you use the installer version).  
③ Place `Utaun.exe` in any folder of your choice.  
④ Launch `Utaun.exe` and follow the on-screen instructions to create your voicebank.  
⑤ For the data save destination, you can choose between ZIP output (Documents, etc.) or direct folder export to UTAU and OpenUTAU.  
*Note: The automatic update feature will be available from future versions.*  

### UI Image
![Test Image 3](IMG_4239.jpeg)

# Compatibility & Usage of Generated Voicebanks

* **UTAU**
  Export directly as an uncompressed voicebank folder into your `voice` folder from within the app and use it immediately.
* **OpenUTAU**
  Export directly as an uncompressed voicebank folder into your `Singers` folder from within the app and use it immediately.
* **UtauTTS**
  Extract the exported ZIP file and place it into the `voice` folder of `utauTTS`.
* **UtauV**
  Drag and drop the ZIP file into the running UtauV application window.
* **UTAlet (Web Version)**
  Drag and drop the ZIP file onto the official website screen.
*Note: For specific usage instructions in each software or web environment, please refer to their respective help files, manuals, or official documentation.*

# System Requirements

* Windows 10 to 11 (64-bit / 32-bit supported)
**(Note: 32-bit is used as the baseline due to file size considerations, but it works without issues on 64-bit Windows as well.)**

# Unsupported Features

* Voiced vowels (あ゙, い゙, ゔ, え゙, お゙)
* Expressive variations such as whispers, breaths, or breathy components
* Palatalized sounds (e.g., kya, kyu, kyo / sha, shu, sho)
* VCV (Continuous Vowels)
* CVVC
* Other special pronunciations

# Terms of Use

The following actions are strictly prohibited regarding the Utaun application itself (`Utaun.exe`):
* Modification
* Editing
* Alteration
* Commercial use
* Redistribution
* Decompiling (disassembly)

# Generated Content

(Voicebanks, `.wav` files, `icon.jpg` / `icon.bmp`, `oto.ini`, etc.)
You (the distributor) are free to set your own terms of use for the generated contents.
Please write your preferred license terms inside `readme.txt`.

For update information and details, please check the GitHub **Releases** page.

# Releases
[Download English Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇺🇸)
