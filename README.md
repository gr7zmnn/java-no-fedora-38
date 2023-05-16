## Preparando um ambiente Linux para desenvolvimento utilizando Fedora 38 para Java e Angular

### Instalando o Java

Para instalar o Java no Fedora 38, siga os seguintes passos:

1. Abra o terminal e execute o seguinte comando para atualizar os pacotes do sistema:

sudo dnf update

2. Em seguida, instale o OpenJDK, que é uma implementação livre do Java:

sudo dnf install java-11-openjdk-devel

### Instalando o Node.js e o Angular

Para instalar o Node.js e o Angular, siga os seguintes passos:

1. Abra o terminal e execute o seguinte comando para instalar o Node.js:

sudo dnf install nodejs

2. Verifique se o Node.js foi instalado corretamente:

node -v


3. Em seguida, instale o Angular:

npm install -g @angular/cli


### Instalando o IntelliJ IDEA

Para instalar o IntelliJ IDEA no Fedora 38, siga os seguintes passos:

1. Baixe o arquivo de instalação do IntelliJ IDEA no site oficial: https://www.jetbrains.com/idea/download/#section=linux

2. Abra o terminal e navegue até o diretório onde o arquivo foi baixado.

3. Extraia o arquivo usando o seguinte comando:

tar -xvf nome_do_arquivo.tar.gz



4. Navegue até o diretório onde o IntelliJ IDEA foi extraído:

cd nome_do_diretorio


5. Execute o arquivo binário do IntelliJ IDEA:

./bin/idea.sh


E pronto! O IntelliJ IDEA está instalado.
