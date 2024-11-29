# CoreLinuxETermux
Desobedeço minha imaginação até deixar de ser Soberbo. Assim, obedeço à Deus, vivo mais, e não criarei problemas pessoais para resolver.
Busybox scripts e outros arquivos para Core Linux e Termux.
No Core Linux recém instalado, os comandos digitados são:

$ wget -c https://github.com/ExAntiCristo/CoreLinuxETermux/archive/refs/heads/main.zip -O main.zip

$ unzip main.zip

$ mv n.tar.gz /etc/sysconfig/tcedir/mydata.tgz

$ filetool.sh -r

No Termux recém instalado, os comandos digitados são:

$ curl -ksL https://github.com/ExAntiCristo/CoreLinuxETermux/archive/refs/heads/main.zip -o main.zip

$ pkg install busybox

$ busybox mv /sdcard/Download/main.zip $HOME/

$ busybox cd $HOME

$ busybox unzip master.zip

$ busybox mv n.tar.gz mydata.tgz

$ busybox tar -xf mydata.tgz

$ busybox sh RodarEsteProgramaPelaPrimeiraVezNoTermux.sh

Pretendo usar Linux somente, mas reconheço que o Microsoft Windows suporta o busybox e o curl, essenciais para dar o suporte ao arquivo n.tar.gz, com comandos idênticos ao da instalação do Termux.

Basta digitar no "Prompt de Comando":

- Para Google Chrome:

start chrome https://frippery.org/files/busybox/busybox.exe

start chrome https://curl.se/windows/dl-8.11.0_4/curl-8.11.0_4-win32-mingw.zip

- Para Firefox:

start firefox https://frippery.org/files/busybox/busybox.exe

start firefox https://curl.se/windows/dl-8.11.0_4/curl-8.11.0_4-win32-mingw.zip

- Para MsEdge:

start msedge https://frippery.org/files/busybox/busybox.exe

start msedge https://curl.se/windows/dl-8.11.0_4/curl-8.11.0_4-win32-mingw.zip

- Mover o busybox.exe para a Área de Trabalho:

mv %USERPROFILE%\Downloads\busybox.exe %USERPROFILE%\Desktop\

- Comando para abrir o terminal busybox:

%USERPROFILE%\Desktop\busybox.exe sh 

Comandos finais:

$ mv ~/Downloads/curl-8.11.0_4-win32-mingw.zip ~/Desktop/

$ cd ~/Desktop/

$ unzip curl-8.11.0_4-win32-mingw.zip

$ export PATH=~/Desktop/curl-8.11.0_4-win32-mingw/bin:$PATH

Agradeço à Deus pelo Github, e aos sites:

http://www.tinycorelinux.net

https://f-droid.org/en/packages/com.termux/

https://www.microsoft.com

