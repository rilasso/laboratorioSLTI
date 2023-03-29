# Comandos Basicos de git y definición

- git `init` 
	- Se utiliza para inicializar un repositorio.
- git `add`
	- git `add` <archivo>
		- Se utiliza para agregar un archivo.
	- git `add` .
		- Se utiliza para agregar todos los archivos.
- git `commit` -m "Mensaje"
	- Se utiliza para subir los archivos agregados con git add. Se agrega un mensaje.
- git `diff` <archivo>
	- Se utiliza para mostrar la diferencia de un archivo del repositorio con tu local.
- git `diff` <hash><archivo>
	- Se utiliza para ver la diferencia del archivo con un commit anterior.
- git `status`	
	- Se utiliza para ver los cambios agregados al staging.
- git `branch` <CurNombre><NuevoNombre>
	- Se utiliza para crear un branch.
- git `checkout` <Nombre>
	- Se utiliza para entrar a un nuevo branch.
- git `checkout` -b <Nombre>
	- Se utiliza para cambiar de branch y crear uno nuevo.
- git `merge` <Nombre>
	- Se utiliza para merge el current branch con el <Nombre> del branch.
- git `revert` <ID>
	- Se utiliza para regresar al <id> del commit y se guardan los cambios.
- git `reset`
	- `--soft` 
		- Sirve para hacer un reset pero los cambios guardados siguen en pie.
	- `--hard`
		- Sirve para hacer un reset pero los cambios son eliminados inmediatamente. 

Peticiones de cambio / Pull request
- Es una forma de que un colaborador y resoluciones de conflictos
- Se hace antes de fusionarlo con la rama principal.
- Es una practica común en proyectos colaborativos. Se revisa la calidad del código y evitar errores.


Merge entre ramas y resoluciones de conflictos
- El merge se puede hacer de forma automática o manual
- Si git detecta problemas en el merge con la rama git notifica si hay algún conflicto 
- Si no hay conflictos el merge se hara automáticamente.

