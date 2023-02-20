# Crear repositorio y subir proyecto

Los pasos a continuacion se deberan realizar en el orden presentado para que no halla algun problema o error en el proceso de subir nuestro proyecto
a nuestro repositoto.

<details><summary>Inicializar el repositorio (git init)</summary>
<br>
<p>
  
Este comando Se usa cuando ya se inicializo la consola de comandos en la carpeta que vamos a subir a github.
  
```git
   git init
```
Una vez lo utilizamos este comando en git , lo que hara sera inicializar esa carpeta que escogimos como repositorio agregando la configuracion que necesita git
para funcionar en este y asi poder emplear los otros comandos que nos ofrece git.
  
</p>
<br>  
</details>

<details>
<summary>Añadiendo el origen del repositorio a git (git remote add origin)</summary>
<br>
<p>
  
Una vez inicializado el repositorio en nuestra carpeta, procedemos a configurar nuestro origen de github para enlazar nuestro repositorio local con el de la nube
para ello utilizamos el siguiente comando.

```git
   git remote add origin "URL generado de git hub de nuestro repositorio anteriormente creado"
```

una vez ejecutado este comando quedara linkeado nuestro repositorio local con el de github y con esto podemos emplear otros comandos para interactuar con estos.
<br> 
</p>
<br>
</details>

<details>
<summary>Estado de git en el repositorio(git status)</summary>
<p>
<br> 
Cuando inicializamos nuestro repositorio podremos acceder al comando git status:

```git
   git status
```
El cual este nos mostrara el estado de nuestro repositorio, nos puede mostrar los cambios que hay en archivos, los archivos que no se han registrado para que git
  les realize seguimiento , y algunos otros detalles que se muestran al emplear este comando.
  
</p>
<br>
</details>


<details>
<summary>Comparando el repositorio local con el de la nube (git fetch origin)</summary>
<p>
<br>  
Este comando nos dira si hay alguna deferencia entre nuestro repositorio local y el de la nube

```git
   git fetch origin main
```
<br>
Nota: la parte final del comando "main" hace referencia a la rama que se quiere conocer o comparar los archivos del repositorio.  
<br>
</p>
</details>


<details>
<summary>Descargando los <em><b>archivos/cambios</b></em> que hay en el repositorio de github</summary>
<br>    
<p>

Este comando nos descargara los archivos o actualizaciones que hay en el repositorio de github a nuestro repositorio local.

```git
   git pull origin main
```
<br>
Nota: la parte final del comando "main" hace referencia a la rama que se va descargar la diferencia de archivos de repositorio local y nube.
<br>  
</p>
</details>


<details>
<summary>Agregando nuestros archivos(git add .)</summary>
<br>    
<p>

Este comando nos descargara los archivos o actualizaciones que hay en el repositorio de github a nuestro repositorio local.

```git
   git add .
```
<br>
Nota: la parte final del comando "." hace referencia a que va agregar como repositorio todo lo que este dentro de esa carpeta.
<br>
</p>
</details>


<details>
<summary>Preparando nuestros archivos para la subida(git commit -m "Fist Commit")</summary>
<br>    
<p>

Este comando preparara los nuevos archivos o arvhivos con cambios para ser subidos en una etapa de stage.
```git
   git commit -m "Fist Commit"
```
<br>
Nota: El comentario deberia ser lo mas claro en cuanto que se va realizar cuando se suban los archivos, ej: "Modificando archivo index, reestructura de colores en css".
<br>
</p>
</details>


<details>
<summary>Subiendo (git push -u origin main)</summary>
<br>    
<p>
Este comando sube los archivos al repositorio de github (nube) hay que espicificar la rama a la cual se quiere subir los cambios por lo cual el "main" puede ser otro nombre de rama diferente.

```git
   git push -u origin main
```
<br>
Nota: el -U hace referencia a Update por lo cual sobreescribira alguna modificacion en un archivo.
<br>
</p>
</details>
