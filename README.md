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
