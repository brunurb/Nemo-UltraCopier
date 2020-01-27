# Nemo-UltraCopier

1- Instalar el paquete ultracopier: en Mint Cinnamon desde Synaptic, o desde la terminal con:  sudo apt-get install ultracopier

 2 - Lo descomprimimos y copiamos el contenido de la carpeta Nemo-UltraCopier-master 
     (tres archivos principales: 
     Nemo-ultracopier.nemo_action, 
     Nemo-ultracopier.py 
     Nemo-ultracopier-folder.nemo_action 
     y el archivo Readme que explica que hacer con ellos ) y lo pegamos 
     en la carpeta home/usuario/.local/share/nemo/actions

3 - Abrimos la carpeta anterior y damos permisos de ejecución 
    al archivo /home/usuario/.local/share/nemo/actions/nemo-ultracopier.py
    
4 - Comprueba que en Nemo->Editar->Extensiones->Acciones aparecen las nuevas acciones de Ultracopier 



Nemo-UltraCopier-0.2

Last version release date: 31 Oct 2014

Author: Lester Carballo Pérez

This is an action for the Nemo browser, to paste files using ultracopier instead of the default nemo copier tool.
Installation instruction

1- Install ultracopier(http://ultracopier.first-world.info/) on Ubuntu and Mint sudo apt-get install ultracopier

2- Download the nemo action files: https://github.com/brunurb/Nemo-UltraCopier/archive/master.zip

3- Uncompress the file Nemo-UltraCopier.zip and copy the contents of 3 (Nemo-ultracopier.nemo_action, Nemo-ultracopier.py 
   Nemo-ultracopier-folder.nemo_action) files to the place /home/USER/.local/share/nemo/actions where USER it's your user       account.

4- Give permission for execute the file /home/USER/.local/share/nemo/actions/nemo-ultracopier.py.

5- Test the result and enjoy.
Change log

0.2-Beta

    Add translation for spanish languages (Es)
    Removed some unnecessary conversion and allow the empty spaces in the url.
    Fixed empty space in the source url(thanks to Alberto Perez).

0.1-Beta

    Initial release
