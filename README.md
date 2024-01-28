# 🧱 Minecraft Server 🗺

 <img src="a.jpg" />
 
 `Está precisando hospedar um servidor de Minecraft para jogar com os rapazes?`

 # Que tal criar seu próprio Host?

Requisitos mínimos:
  * Cabo Ethernet / Roteador.
  * 1 Pen drive
  * 1 Computador velho (monitor, teclado, etc.)
    * Intel® Core™ i3 ou i5 / AMD Ryzen
    * min 4 GB de RAM
    * 10 GB de espaço disponivel

## Passo 1 - Debian

Vamos precisar de um sistema operacional com acesso a internet para rodar o servidor, nesse caso usaremos o Debian.
Você pode escolher entre instalar diretamente em um PC ou usar uma Máquina Virtual.

* Servidor no Pc
  * Você vai precisar de um pen drive pra fazer a instalação do debian diretamente na máquina e configurar a BIOS para acessar o pen drive na ordem de BOOT.
 
  * https://etcher.balena.io
  * https://www.debian.org/download

* Servidor na VM
  * Caso você prefira usar uma maquina virtual, você terá que configura-la manualmente a quantidade de Mem. RAM e processamento.
    
  * https://www.vmware.com/br/products/workstation-player/workstation-player-evaluation.html
  * https://www.debian.org/download
 
## Passo 2 - Instalando o Debian

Quando você conseguir acesso ao sistema operacional, vai se deparar com essa tela:
<img src="deb.png" />

Mas não se preocupe! Você que é um lerdão vai ter o passo a passo da instalação mastigadinho a seguir:

* Instalação do Debian

  * 1  - Selecione Graphical Install
  * 2  - Selecione o idioma
  * 3  - Selecione a localização
  * 4  - Selecione a configuração do teclado
  * 5  - Selecione o seu hostname (ex: mc-server)
  * 6  - Selecione o nome do dominio (ex: local)
  * 7  - Tela de Senha root (pode pular essa parte apertando Enter)
  * 8  - Selecione o nome do seu usuário (você vai precisar dele para acessar o servidor)
  * 9  - Selecione a senha do seu usuário (use uma senha que você não vai esquecer)
  * 10 - Selecione a região do fuso horario
  * 11 - Selecione a opção "Guided - use entire disk"
  * 12 - Selecione o Seu HD, SSD, etc.
  * 13 - Selecione "All files in one partition"
  * 14 - Selecione "Finish partitioning and write changes to disk"
  * 15 - Selecione a opção "Sim"
  * 16 - Selecione a opção "Não"
  * 17 - Selecione a localização
  * 18 - Selecione a primeira opção "deb.debian.org"
  * 19 - Tela de Proxy (pode pular)
  * 20 - Selecione a opção "Não"
  * 21 - Desmarque as opções "Debian desktop enviroment" e "GNOME" e marque a opção "SSH Server"
  * 22 - Selecione a opção "Sim"
  * 23 - Selecione a opção "dev/sda"
  * 24 - Aguarde o final da instalação e seleciona a opção "Reboot"
  * Não esqueça de remover seu pen drive.

## Passo 3 - Terminal

Meus parabéns, você instalou o Debian com sucesso! Agora vamos deixar ele um pouco mais amigável.

<img src="s.png" />

Você vai precisar de acesso a internet a partir de agora.

* Escreva o usuário e senha que você escolheu durante a instalação, se você esqueceu pode fechar o tutorial já

  * <img src="d.png" />
  
  * Quando você escreve a senha ela não aparece na tela, sim isso é normal.
 
* Escreva esse comando:
  `sudo apt update`
  * <img src="d1.png" />
  * Escreva a sua senha


* Caso precise atualizar algo escreva esse comando:
  `sudo apt upgrade -y`
  * <img src="d2.png" />


* Escreva esse comando:
  `sudo apt install curl`
  * <img src="d3.png" />
  * escolha Y para aceitar


* Escreva esse comando:
  `curl -fsSL https://get.casaos.io | sudo bash`
  * <img src="d4.png" />

* Se tudo deu certo, você vai se deparar com essa tela
  * <img src="d5.png" />
  * pode ir pegar um café e esperar a instalação acabar.

 ## Passo 4 - CasaOS
 
* Ao terminar a instalação, a única coisa que você precisa se preocupar é com o IP que vai aparecer na tela:
  * <img src="d6.png" />

  * Esse é o endereço IP local do seu servidor (não é seu o IP, calma)

  * Agora você pode acessar o seu servidor pelo CasaOS através do seu browser, na sua internet local.

* Digite o IP que apareceu pra você no seu browser e você vai cair nessa tela:
  
  * <img src="casa.png" />

 * Crie uma conta e você poderá acessar o CasaOS sem problemas.

  * <img src="casa1.png" />

* Dentro do CasaOS acesse a AppStore e baixe o Craft Controller.

  * <img src="casa2.png" /> <img src="casa3.png" />
  
* Após baixar, o Crafty vai criar pra você um usuario e senha para acessa-lo (Sim, você vai ter q decorar 3 logins e senhas no processo todo.)

  * <img src="casa4.png" />




















  
<p align="center">
     <img src="" />
</p>
