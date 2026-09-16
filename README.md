# Conversor de áudios para o Dolphin
 Plugin para o menu de contexto do Dolphin para extrair e converter o áudio de algum vídeo para MP3 ou WAV. Criei originalmente para usar no DaVinci Resolve que não aceita AAC no Linux, mas serve para qualquer propósito que você queira.

## Como instalar
 - Baixe o arquivo em [releases](https://github.com/NIICKTCHUNS/converter-audio-davinci/releases)
 - Depois disso copie ou mova o arquivo `converter-audio.desktop` para esse local: `.local/share/kio/servicemenus/` da sua home
 - Após isso, copie ou mova o outro arquivo `converter-audio` (sem extensão de arquivo) para esse local: `.local/bin/` da sua home

 Só de fazer isso, ele já vai estar instalado, se quiser desinstalar, é só apagar esses arquivos. Se você quiser ocultar posteriormente, só ir nas configurações do Dolphin > Menu de Contexto. Ali você encontra todas as opções dos menus de contexto do Dolphin, inclusive desse plugin.

## Funções
Esse plugin tem as seguintes funções:
- Converter o áudio do vídeo diretamente, sem perda de qualidade, apenas o áudio do vídeo é trocado pela opção que você selecionar (MP3 ou PCM (PCM até onde eu sei, exige versões mais recentes do FFmpeg))
- Extrair e converter o áudio do vídeo, ele converte para MP3 e WAV
  <img width="556" height="112" alt="image" src="https://github.com/user-attachments/assets/8e087ef3-6c96-47a8-97f4-45af01415a35" />

 
### Aviso
Usei o Gemini para fazer esse projeto, se você não curte a ideia de projetos gerados por IA fique a vontade para ignorar esse projeto.
