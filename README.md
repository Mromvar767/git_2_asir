PRÁCTICA MANEJO DE GIT

Repositorio git_2_asir
	git clone git@github.com:Mromvar767/git_2_asir.git

Push inicial
	git push

Ignorar archivos
	git add privado.txt
	git commit -m "añado fichero privado.txt"
	git push
	git add privada
	git commit -m "añado carpeta privada"
	git push
	git rm --cached privado.txt
	git commit -m "ignoro fichero privado.txt"
	git push

Añadir fichero '1.txt' y tag v0.1
	git tag v0.1
	git add 1.txt
	git commit -m "Añado fichero 1.txt y tag v0.1"
	git push
	git push --tags

Crear una tabla
| NOMBRE | GITHUB |
| ----------- | ----------- |
| Nacho | [Enlace a github](https://github.com/jrodrob861/git_2_asir) |
| Adrián | [Enlace a github](https://github.com/areyjim770/git_2_asir) |
| David | [Enlace a github](https://github.com/Davalomal/Git_2_asir) |

	git add README.md
	git commit -m "Añado tabla de cuentas de GitHub"md
	git push

Crear una rama
	git branch v0.2
	git checkout v0.2

Añadir fichero
	git add 2.txt
	git commit -m "Añado fichero 2.txt"

Crear rama remota
	git push origin v0.2

Merge directo
	git checkout main
	git merge v0.2
	git push

Merge con conflicto
	git add 1.txt
	git commit -m "Añado 'Hola' a 1.txt"
	git checkout v0.2
	git add 1.txt
	git commit -m "Añado 'Adios' a 1.txt
	git checkout main
	git merge v0.2

Arreglar conflicto
	git add 1.txt
	git commit -m "Arreglo conficto de fichero 1.txt"
	git push

Borrar rama
	git tag v0.2
	git branch -d v0.2
	git commit -m "Borrado de la rama v0.2"
	git push --tags
	git push

Listado de cambios
	git log

Colaborando en repositorios de terceros
	git clone git@github.com:Mromvar767/git_2_asir-1.git
	git clone git@github.com:Mromvar767/git_2_asir-2.git
	git branch Mario
	git checkout Mario
	git add equipo.md
	git commit -m "Actualizo archivo 'equipo.md'"
	git push --set-upstream origin Mario
	(desde git branch hasta git push lo mismo otra vez pero en el repositorio de Raúl)
