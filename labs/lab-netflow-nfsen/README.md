# lab-netflow-nfsen
Tutorial de Monitoreo
---------------------

1. Instalar VirtualBox en su computadora.
2. Instalar Vagrant para el SO que utilice (Linux, MacOS, etc) desde https://www.vagrantup.com/downloads.html.
3. Instalar el Box correspondiente a Debian 7.
    
    ```
    $ vagrant box add puphpet/debian75-x64 --provider virtualbox
    ```
4. Puede listar los Boxes instalados mediante

    ```
    $ vagrant box list
    puphpet/debian75-x64 (virtualbox, 2.0)
    ```
5. Crear un directorio desde donde ejecutar y configurar Vagrant 
    
    ```
  $ mkdir vagrant_monitoreo
  $ cd vagrant_monitoreo/
    ```

6. Inicializar Vagrant
    
    ```
    $ vagrant init puphpet/debian75-x64
    ```
7. Copiar el contenido de https://github.com/LACNIC/tutorial-netmon/tree/master/labs/lab-netflow-nfsen al directorio actual donde se corre Vagrant. Si utilizamos git para ejecutamos 
    
    ```
    git 
    ```
8. Correr la máquina virtual
    
    ```
    $ vagrant up --provider virtualbox
    ```
9. Iniciar sesión ssh sobre la máquina virtual
    
    ```
    $ vagrant ssh
    ```

