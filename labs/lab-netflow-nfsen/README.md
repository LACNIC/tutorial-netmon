# lab-netflow-nfsen
Tutorial de Monitoreo
---------------------

0. Instalar VirtualBox en su computadora 

0. Instalar Vagrant para el SO que utilice (Linux, MacOS, etc) desde:

https://www.vagrantup.com/downloads.html

0. Instalar el Box correspondiente a Debian 7:

$ vagrant box add puphpet/debian75-x64 --provider virtualbox

Puede listar los Boxes instalados mediante:

$ vagrant box list

4- Crear un directorio desde donde ejecutar y configurar Vagrant 

  $ mkdir vagrant_monitoreo

  $ cd vagrant_monitoreo/

5- 

git

6- Inicializar Vagrant 

vagrant init puphpet/debian75-x64

7- Correr la máquina virtual

  $ vagrant up --provider virtualbox
  
8- Iniciar sesión ssh sobre la máquina virtual

  $ vagrant ssh


