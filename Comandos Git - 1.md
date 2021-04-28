`Comandos`
# <h1 class=center> **Listado de comandos de Git Hub**</h1>

### Los comandos se usan en consola 


>   1. git init = solo se ejecuta una ves al comensar el proyecto para tener el resplado del directorio de los trabajos, comiense hacer el seguimiento de los proyectos   

>    2. git add = para darle el seguimiento de adecuado de un archivo en especifico o a todo el repositorio. 
    
>   3. git commit = se encarga de llevar el archivo trabajado por el comando git add (que se encuentra en el statis area) para llevar los cambios al repositorio local(Fotografia final). es donde se se crea la foto instantania del archivo. de donde se trabajo en los cambios. 
    3.1. Nota: se le puede agregar una instruccion de la siguiente manera git commit -M (escribe la descricion deseada)



### Manejo para los file en git ###


>    1. git status -s = es para saber que esta estan '\'
        1. ?? i= indica que no se ha hecho una copia del los proyectos en git,todo los que indica '\' b. A = cuando el file a sido anadido y se le esta dando un seguimiento esta en la fase 2 de status area 
        2. M = indica que el archivo a sido modificado pero no ha sido resplandado esa copia. 
        3. git log --oneline = para saber la linea de todas las modificaciones que les ha hecho a los archivos en git.
        
> 2. git reset --hard =  se restaura donde dejaste el archivo 

>3. gir commit -am "" =  para agregar y escribir la descripcion

>4. git push --set-upstream origin master = configura al repositorio que para a anadir(previamente con su dirreccion)
    1. git push -u origin master = para actualizar los cambios que se hicieron en el area de stages 
    2.
>5. git remote add origin https://github.com/{user}/{name_repositorie}.git = indica donde va el repositorio