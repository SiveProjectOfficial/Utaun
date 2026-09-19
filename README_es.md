[🇪🇸Volver a selección de idioma](./README.md)

# ¿Qué es Utaun?  
  
Utaun es un software para Windows que genera bancos de voz CV (Consonante-Vocal) para UTAU utilizando exclusivamente modelado sinusoidal compuesto (síntesis de voz CSM) puramente inanimado.  
Admite la generación automática de archivos ZIP de bancos de voz en su carpeta Documentos, así como exportaciones directas a varios softwares compatibles con UTAU.  

# Características  

* Genera automáticamente un ZIP del banco de voz en su carpeta Documentos o lo exporta directamente a softwares compatibles al ejecutarse.  
* Genera vocales (A, I, U, E, O, N) mediante modelado sinusoidal compuesto (síntesis de voz CSM) puramente inanimado.  
* Configure las carpetas de consonantes y sonidos sonoros incluidas en su directorio Documentos para generar bancos de voz CV.  
* Genera automáticamente las filas m, n, y y w dentro del programa.  
* Compatible con alias en Hiragana + alias en Romaji inglés (todos pronunciados en japonés).  
* Genera automáticamente `oto.ini`, `character.txt` y `readme.txt`.  
* Convierte simultáneamente imágenes PNG a formatos JPG y BMP (Nota: el JPG se utiliza para `character.txt`).  
* La codificación de `readme.txt` y `character.txt` se puede seleccionar entre **Shift-JIS (ANSI)** y **UTF-8** (Nota: UTF-8 proporciona compatibilidad con OpenUTAU y otros).  
* Permite cambiar la frecuencia fundamental (tono).  
* Nombre del banco de voz (nombre del personaje) libremente personalizable.  
* **Compatible con los modos Claro y Oscuro.**  
* **Permite elegir el destino de exportación.**  

# Uso previsto  

* Cuando desee crear bancos de voz de UTAU utilizando voces inanimadas o artificiales.  
* Para la producción de bancos de voz si le resulta difícil o incómodo grabar con su propia voz.  
* Investigación de materiales de audio basados en modelado sinusoidal compuesto (síntesis de voz CSM).  
* Prototipado de bancos de voz personalizados.  
* Descomprimir el ZIP generado para usarlo directamente como recursos de vocaloid simulados por humanos.  
* Uso como materiales de audio para remixes de video (por ejemplo, OtoMAD, YTPMV).  

# Cómo usar Utaun  

① Descargue la última versión de Utaun desde **[GitHub Releases](#Releases)**.  
② Si está descargando la versión en carpeta ZIP, **coloque las carpetas "Consonant/Voiced Sound" y `oto.ini` directamente dentro de su carpeta "Documentos" (también son compatibles los Documentos de OneDrive).** (Nota: Se colocan automáticamente si utiliza la versión del instalador).  
③ Coloque `Utaun.exe` en cualquier carpeta de su elección.  
④ Inicie `Utaun.exe` y siga las instrucciones en pantalla para crear su banco de voz.  
⑤ Para el destino de guardado de datos, puede elegir entre la salida ZIP (Documentos, etc.) o la exportación directa de carpetas a UTAU y OpenUTAU.  
*Nota: La función de actualización automática estará disponible en futuras versiones.*  

### Imagen de la interfaz (UI)  
![Test Image 3](IMG_4239.jpeg)  

# Compatibilidad y uso de los bancos de voz generados  

* **UTAU**  
  Exporte directamente como una carpeta de banco de voz descomprimida en su carpeta `voice` desde la aplicación y úselo de inmediato.  
* **OpenUTAU**  
  Exporte directamente como una carpeta de banco de voz descomprimida en su carpeta `Singers` desde la aplicación y úselo de inmediato.  
* **UtauTTS**  
  Extraiga el archivo ZIP exportado y colóquelo en la carpeta `voice` de `utauTTS`.  
* **UtauV**  
  Arrastre y suelte el archivo ZIP en la ventana de la aplicación UtaunV en ejecución.  
* **UTAlet (Versión web)**  
  Arrastre y suelte el archivo ZIP en la pantalla del sitio web oficial.  
*Nota: Para instrucciones de uso específicas en cada software o entorno web, consulte sus respectivos archivos de ayuda, manuales o documentación oficial.*  

# Requisitos del sistema  

* Windows 10 a 11 (compatible con 64 bits / 32 bits)  
**(Nota: Se utiliza la versión de 32 bits como base debido a consideraciones de tamaño de archivo, pero funciona sin problemas en Windows de 64 bits también.)**  

# Funciones no compatibles  

* Vocales sonoras (あ゙, い゙, ゔ, え゙, お゙)  
* Variaciones expresivas como susurros, respiraciones o componentes de soplido  
* Sonidos palatalizados (ej.: kya, kyu, kyo / sha, shu, sho)  
* VCV (Vocales continuas)  
* CVVC  
* Otras pronunciaciones especiales  

# Términos de uso  

Las siguientes acciones están estrictamente prohibidas con respecto a la aplicación Utaun en sí (`Utaun.exe`):  
* Modificación  
* Edición  
* Alteración  
* Uso comercial  
* Redistribución  
* Descompilación (desensamblaje)  

# Contenido generado  

(Bancos de voz, archivos `.wav`, `icon.jpg` / `icon.bmp`, `oto.ini`, etc.)  
Usted (el distribuidor) es libre de establecer sus propios términos de uso para los contenidos generados.  
Por favor, escriba sus términos de licencia preferidos dentro de `readme.txt`.  

Para obtener información sobre actualizaciones y detalles, consulte la página de **Releases** en GitHub.  

# Releases  
[Download Spanish Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇪🇸)

