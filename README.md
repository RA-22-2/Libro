# Libro
Repositorio de practica 

## Ejercicios de Gestión de Ramas
Para hacer estos ejercicios es necesario haber hecho antes los ejercicios sobre historial de cambios.
#### [Ejercicios resueltos](https://github.com/jmav94/react "Ejercicios resueltos")

#### Ejercicio 1
Crear una nueva rama `bibliografia` y mostrar las ramas del repositorio.
> `git branch bibliografia`</br>
> `git branch / git branch -l / git branch -a`

#### Ejercicio 2 
1. Crear el fichero `capitulos/capitulo4.txt` y añadir el siguiente texto
> *En este capítulo veremos cómo usar GitHub para alojar repositorios en remoto*
2. Añadir los cambios a la zona de intercambio temporal *staging area*
`git add . `
3. Hacer un commit con el mensaje _"Añadido Capitulo 4"_
`git commit m "Añadido capitulo 4"`
4. Mostrar el historial del repositorio incluyendo todas las ramas.
`git log --graph --all --oneline`