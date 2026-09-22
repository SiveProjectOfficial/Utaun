[🇵🇹 Voltar à seleção de idioma](./README.md)
​
# O que é o Utaun?  
  
O Utaun é um software para Windows que gera voicebanks CV (Consoante-Vogal) para o UTAU usando exclusivamente modelagem senoidal composta (síntese de voz CSM) puramente inanimada.  
Ele suporta a geração automática de arquivos ZIP de voicebank na sua pasta Documentos, bem como exportações diretas para vários softwares compatíveis com o UTAU.  

# Recursos  

* Gera automaticamente um ZIP de voicebank na sua pasta Documentos ou exporta diretamente para softwares compatíveis ao ser executado.  
* Gera vogais (A, I, U, E, O, N) através de modelagem senoidal composta (síntese de voz CSM) puramente inanimada.  
* Configure as pastas de consoantes e sons sonoros incluídas no seu diretório Documentos para gerar voicebanks CV.  
* Gera automaticamente as linhas m, n, y e w dentro do programa.  
* Suporta apelidos em Hiragana + apelidos em Romaji em inglês (todos pronunciados em japonês).  
* Gera automaticamente `oto.ini`, `character.txt` e `readme.txt`.  
* Converte imagens PNG simultaneamente para os formatos JPG e BMP (Nota: o JPG é usado para o `character.txt`).  
* A codificação do `readme.txt` e do `character.txt` pode ser selecionada entre **Shift-JIS (ANSI)** e **UTF-8** (Nota: o UTF-8 oferece compatibilidade com o OpenUTAU e outros).  
* Permite alterar a frequência fundamental (tom).  
* Nome do voicebank (nome do personagem) livremente personalizável.  
* **Suporta os modos Claro (Light) e Escuro (Dark).**  
* **Permite escolher o destino de exportação.**  

# Uso Pretendido  

* Quando você quiser criar voicebanks do UTAU usando vozes inanimadas ou artificiais.  
* Para a produção de voicebanks se você achar difícil ou desconfortável gravar com sua própria voz.  
* Pesquisa de materiais de áudio baseados em modelagem senoidal composta (síntese de voz CSM).  
* Prototipagem de voicebanks personalizados.  
* Descompactar o ZIP gerado para usar diretamente como ativos de vocaloid gerados por humanos (simulação de voz humana).  
* Uso como materiais de áudio para remixes de vídeo (por exemplo, OtoMAD, YTPMV).  

# Como Usar o Utaun  

① Baixe a versão mais recente do Utaun em **[GitHub Releases](#Releases)**.  
② Se você estiver baixando a versão em pasta ZIP, **coloque as pastas "Consonant/Voiced Sound" e o `oto.ini` diretamente dentro da sua pasta "Documentos" (Documentos do OneDrive também são suportados).** (Nota: Elas são colocadas automaticamente se você usar a versão do instalador).  
③ Coloque o `Utaun.exe` em qualquer pasta de sua escolha.  
④ Inicie o `Utaun.exe` e siga as instruções na tela para criar seu voicebank.  
⑤ Para o destino de salvamento dos dados, você pode escolher entre saída ZIP (Documentos, etc.) ou exportação direta de pasta para o UTAU e OpenUTAU.  
*Nota: O recurso de atualização automática estará disponível em versões futuras.*  

# UI
**UI (Tela de Operação - Claro)**   
 ![Test Image 3](UI/IMG_5542.jpeg)  
**UI (Tela de Configurações - Claro)**  
![Test Image4](UI/IMG_5538.jpeg)
**UI (Tela de Operação - Escuro)**  
![Test Image5](UI/IMG_5540.jpeg)  
**UI (Tela de Configurações - Escuro)**  
![Test Image6](UI/IMG_5541.jpeg)  
**UI (Tela de Exportação)**  
![Test Image7](UI/IMG_5536.jpeg)  
**UI (Tela de Detalhes da Atualização)**  
![Test Image8](UI/IMG_5539.jpeg)  
**UI (Tela de Atualização)**  
![Test Image9](UI/IMG_5537.jpeg)

# Compatibilidade e Uso dos Voicebanks Gerados  

* **UTAU**  
  Exporte diretamente como uma pasta de voicebank descompactada para sua pasta `voice` de dentro do aplicativo e use-a imediatamente.  
* **OpenUTAU**  
  Exporte diretamente como uma pasta de voicebank descompactada para sua pasta `Singers` de dentro do aplicativo e use-a imediatamente.  
* **UtauTTS**  
  Extraia o arquivo ZIP exportado e coloque-o na pasta `voice` do `utauTTS`.  
* **UtauV**  
  Arraste e solte o arquivo ZIP na janela do aplicativo UtaunV em execução.  
* **UTAlet (Versão Web)**  
  Arraste e solte o arquivo ZIP na tela do site oficial.  
*Nota: Para instruções de uso específicas em cada software ou ambiente web, consulte seus respectivos arquivos de ajuda, manuais ou documentação oficial.*  

# Requisitos do Sistema  

* Windows 10 a 11 (suporte a 64 bits / 32 bits)  
**(Nota: O sistema de 32 bits é usado como base devido a considerações de tamanho de arquivo, mas funciona sem problemas em Windows de 64 bits também.)**  

# Recursos Não Suportados  

* Vogais vozeadas (あ゙, い゙, ゔ, え゙, お゙)  
* Variações expressivas, como sussurros, respirações ou componentes de baforada  
* Sons palatizados (ex.: kya, kyu, kyo / sha, shu, sho)  
* VCV (Vogais Contínuas)  
* CVVC  
* Outras pronúncias especiais  

# Termos de Uso  

As seguintes ações são estritamente proibidas em relação ao aplicativo Utaun em si (`Utaun.exe`):  
* Modificação  
* Edição  
* Alteração  
* Uso comercial  
* Redistribuição  
* Descompilação (desmontagem)  

# Conteúdo Gerado  

(Voicebanks, arquivos `.wav`, `icon.jpg` / `icon.bmp`, `oto.ini`, etc.)  
Você (o distribuidor) é livre para definir seus próprios termos de uso para os conteúdos gerados.  
Por favor, escreva seus termos de licença preferidos dentro do `readme.txt`.  

Para informações de atualização e detalhes, verifique a página de **Releases** no GitHub.  

# Releases  
[Download Portuguese Version of Utaun →](https://github.com/SiveProjectOfficial/Utaun/releases/tag/🇵🇹)
