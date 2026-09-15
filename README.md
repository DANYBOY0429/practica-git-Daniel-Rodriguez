# Creación y sincronización de repositorios con Git y GitHub



##### Datos del estudiante



**Nombre**: Daniel Rodriguez Moreno
**Matricula**: 2630303



##### Objetivo



Crear un repositorio local utilizando Git, sincronizarlo con un repositorio remoto en GitHub y comprobar el flujo de trabajo en ambos sentidos:



Repositorio local → GitHub
GitHub → Repositorio local



#### Proceso de sincronización



|Comandos utilizados|función|Ejemplo|
|-|-|-|
|mkdir|Crear una carpeta para el repositorio local|mkdir practica-git-Daniel-Rodriguez|
|cd|Te dirige hacia algún repositorio|cd practica-git-Daniel-Rodriguez|
|git init|Se inicializa un repositorio en git|git init|
|git status|Te muestra el estado actual de tu repositorio|git status|
|git add -A|Pasa el contenido del repositorio de la zona de untracked files a staging|git add -A  README.md  datos.txt|
|git commit -m "mensaje"|Se utiliza para crear un commit|git commit -m "primer commit"|
|git log|Se utiliza para mostrar el historial de commits en un repositorio de Git|git log|
|git remote add origin "URL\_DEL\_REPOSITORIO"|Permite asociar un repositorio remoto con tu repositorio local|git remote add origin https://github.com/DANYBOY0429/practica-git-Daniel-Rodriguez.git|
|git remote -v|Se utiliza para listar los repositorios remotos asociados a tu repositorio local y mostrar sus URLs|git remote -v|
|git push -u origin main|Para enviar los cambios locales de un repositorio a un repositorio remoto y, además, establecer un seguimiento automático entre ramas.|git push -u origin main|
|git pull origin main|Descarga los cambios de la rama main del repositorio remoto llamado origin y los fusiona automáticamente con tu rama local actual.|git pull origin main|
|git push|Se utiliza para subir los commits de tu repositorio local a un repositorio remoto, sincronizando ramas y cambios con otros colaboradores.|git push|



###### Como crear un repositorio local:



Desde la powershell, con el comando mkdir "nombre de la carpeta"("practica-git-Daniel-Rodriguez") y se inicializo el repositorio en git con el comando git init.



###### Vinculación del repositorio local con GitHub



Para vincular mi repositorio con GitHub utilice el comando git remote add origin y coloque el URL que me proporciono el repositorio creado en GitHub.



###### Sincronización Local → GitHub



Para sincronizarlo utilice el comando "git push" para realizar un cambio desde el repositorio local y enviarlo ala nube.



###### Sincronización GitHub → Local



Realice un cambio desde GitHub creando un commit y para recibirlo en el repositorio local utilice el comando "git pull".



###### Archivos contenidos en el repositorio



**README.md**:
Contiene el el proceso de la sincronización de git con su nube, se explican los comandos utilizados y la manera en que se sincronizo.



**datos.txt**:
Contiene los cambios desde un repositorio local y la nube de git(GitHub).



###### Conclusión:

Con esta practica aprendí el desarrollo de la sincronización de un repositorio local a uno remoto y como aplicarlo cuando lo sea necesario y la importancia de almacenarlo en GitHub para que no se pierdan o se eliminen datos, ya que en proyectos de mecatrónica me será muy útil y será una forma eficaz de guardar archivos e información.

