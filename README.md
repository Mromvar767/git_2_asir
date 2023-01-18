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

	git add README.
	git commit -m "Añado tabla de cuentas de GitHub"md
	git push
