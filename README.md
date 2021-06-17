
# Groovyarcade Plus

Ideia original do Paulo Takeda a.k.a Nipoman, guru dos grupos de arcade do Brasil para que o emulador principal do Groovyarcade seja o Retroarch invés do Groovymame além de baixar as roms, vídeos de pre-visualizaçao e alterar o front-end.

Antes de executar o script abaixo, você irá precisa de uma instalação limpa do Groovyarcade (https://github.com/substring/os/releases) instalado no HD

 - Faça uma instalação padrão do Groovyarcade e reinicie a máquina
 - Saia do Attract Mode e selecione a opção "Exit to shell"
 - No terminal execute o comando `bash <(curl -s https://ga-plus.glitch.me/script.sh)`

 O script atualmente instala os seguintes pacotes via pacman:
 - aria2 (baixador de torrent)
 - alsa (driver de som)
 - retroarch (emulador)
 - flycast (emulador)

Após a instalação dos pacotes é feito o download dos arquivos que o Takeda fez (via torrent) para alterar o funcionamento padrão do Groovyarcade (configurações, snaps e roms). O arquivo baixa aproximadamente 180gb e após baixar é feito a substituição dos arquivos na pasta **~/.config** e **~/shared**
