# Git demo y Laboratorio
 
## Prerrequisitos
 
- Instalacion de git en el sistema [Tutorial de Instalacion](https://git-scm.com/book/es/v1/Empezando-Instalando-Git)
- Una cuenta de github configurada [Configuracion de cuenta de Git](https://github.com/join)
 
## Laboratorio-Git
 
1. Antes de Usar git para este laboratorio, necesita configurar su cuenta de git utilizando el siguiente comando `git config --global user.name "<Nombre de Usuario>"`
 
2. Agregue a la configuración de git su dirección de correo `git config --global user.email "<Micorreo@midominio.com>"`
3. Ingrese a su cuenta de git [https://github.com](https://github.com)
4. Ingrese al link de este repositorio [Repo URL](https://github.com/DouglasLopez/devops-foundations)
5. Haga click en "Fork" para crear una copia de este repositorio dentro de su cuenta de Github.
6. Haga clic en "Clone or Download" para obtener la dirección de https para el repositorio recientemente creado.
7. Clone el repositorio usando el comando `git clone <HTTPS URL del paso previo>`
8. Ingrese al directorio donde ha clonado el repositorio y use el comando `ls -la`
9. Observe el directorio `.git` este directorio contiene toda la información del control de versiones, esta es su copia local del mismo.
10. Corra el comando `git log` y podrá observar el historial de todos los cambios
11. Corra el comando `git remote` para ver la lista de repositorios remotos asociados a su copia local
12. Corra el comando `git remote -v` para ver información más detallada acerca de el repositorio remoto
13. Cree un nuevo archivo `mi_archivo.txt`. y el comando `echo "este es un archivo nuevo"> mi_archivo.txt`
14. Con el comando `git status` puede ver el estado actual de su repositorio el archivo `mi_archivo.txt` aparecer como `untracked`
15. Agregue su archivo al cvs con el comando `git add mi_archivo.txt`
16. Corra el comando `git commit` para agregar sus cambios al repositorio estos cambios estaran almacenados solamente en su copia local
17. Para agregar sus cambios al repositorio remoto corra el comando `git push origin master`
18. Verifique en su cuenta de github si el cambio se ve reflejado en el repositorio
 