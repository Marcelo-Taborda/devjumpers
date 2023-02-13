# Ejercitacion Final | Git - Github
---
## Instrucciones

- Creamos un repositorio con el nombre "devjumpers".

[![Captura-de-pantalla-75-1.png](https://i.postimg.cc/VvLKhwyx/Captura-de-pantalla-75-1.png)](https://postimg.cc/G8VPBZmK)

- Realizamos una copia del repositorio localmente y creamos el archivo "README.md" donde agregaremos el paso a paso de la ejercitación.

```
git clone https://github.com/Marcelo-Taborda/devjumpers.git
```
```
touch README.md
```

- Hacemos un commit de README.md con el mensaje "commit inicial" y lo enviamos al repositorio en github.

```
git add .
```
```
git commit -m "commit inicial"
```
```
git push
```
### Captura de los comandos utilizados hasta ahora.

[![Captura-de-pantalla-20230209-171216.png](https://i.postimg.cc/FRBmZ3Kc/Captura-de-pantalla-20230209-171216.png)](https://postimg.cc/HcXfWJXs)

- Creamos el archivo "privado.txt" y la carpeta "privada".
```
touch privado.txt
```
```
mkdir privada
```

- Creamos el archivo ".gitignore" y agregamos el archivo y carpeta creados previamente dentro de el.

```
nano .gitignore
```
[![Captura-de-pantalla-20230212-085646.png](https://i.postimg.cc/1zTVgnZC/Captura-de-pantalla-20230212-085646.png)](https://postimg.cc/KKP8wYjB)

- Agregamos el archivo 1.txt, creamos una nueva rama llamada v0.2 y nos posicionamos en ella.
```
touch 1.txt
```
```
git checkout -b v0.2
```
- Dentro de la nueva rama creamos el archivo 2.txt y subimos todos los cambios.
```
touch 2.txt
```
```
git add .
```
```
git commit -m "Agregado del .gitignore, 1.txt y creacion de la rama v0.2 y dek archivo 2.txt dentro de la nueva rama."
```
```
git push --set-upstream origin v0.2
```
### Captura de los comandos utilizados hasta ahora.

[![Captura-de-pantalla-20230212-092435.png](https://i.postimg.cc/Z0t91Snb/Captura-de-pantalla-20230212-092435.png)](https://postimg.cc/V0gLC2Xp)

- Volvemos a la rama main y hacemos un merge de la rama v0.2.

```
git checkout main
```
```
git merge v0.2
```

- Editamos y agregamos un hola en el archivo 1.txt de la rama main y hacemos un commit.
```
echo Hola > 1.txt
```
```
git add .
```
```
git commit -m "Edicion del archivo 1.txt"
```

- Nos movemos a la rama v0.2 y agregamos un adios en el archivo 1.txt.

```
git checkout v0.2
```
```
echi Adios > 1.txt
```

- Realizamos un commit de los cambios realizados y nos posicionamos en la rama principal.
```
git add .
```
```
git commit -m "Edicion del archivo 1.txt"
```
```
git checkout main
```

- Hacemos un merge de la rama v0.2.
```
git merge v0.2
```
### Captura de los comandos utilizados hasta ahora.

[![Captura-de-pantalla-20230212-095708.png](https://i.postimg.cc/PfwF8nZ2/Captura-de-pantalla-20230212-095708.png)](https://postimg.cc/BtJCdymK)

- Comprobamos que ramas tienen merge y cuales no.
```
git branch --merged
```
```
git branch --no-merge
```
[![Captura-de-pantalla-20230212-100055.png](https://i.postimg.cc/FK07LRrh/Captura-de-pantalla-20230212-100055.png)](https://postimg.cc/1g5mxyVd)

- Resolvemos el conflicto ocasionado por el merge y hacemos un commit.

[![Captura-de-pantalla-82.png](https://i.postimg.cc/t4kXQx4Z/Captura-de-pantalla-82.png)](https://postimg.cc/0z6g7rmP)

```
git add .
```
```
git commit -m "Conflictos en 1.txt resueltos."
```

- Eliminamos la rama v0.2.
```
git branch -d v0.2
```

- Listamos todos los cambios realizados.
```
git log --oneline --decorate --all --graph
```
[![Captura-de-pantalla-20230213-044956.png](https://i.postimg.cc/N033V6Hw/Captura-de-pantalla-20230213-044956.png)](https://postimg.cc/2qx9LBGH)

### Captura de los comandos utilizados hasta ahora.

[![Captura-de-pantalla-20230213-044956.png](https://i.postimg.cc/PrKkxvBm/Captura-de-pantalla-20230213-044956.png)](https://postimg.cc/xckZp8jC)

### Foto de perfil agregada
[![Captura-de-pantalla-20230213-054043.png](https://i.postimg.cc/mgn2wZQ1/Captura-de-pantalla-20230213-054043.png)](https://postimg.cc/HrQgWgvT)

### Doble factor de autenticacion activado
[![Captura-de-pantalla-84.png](https://i.postimg.cc/k5tMhrc1/Captura-de-pantalla-84.png)](https://postimg.cc/94CjrnsZ)

### Tabla de compañeros
|NOMBRE|GITHUB|
|:------------:|:------------:|
|Leandro Cuevas|https://github.com/leandro-cuevas|
|Armando Torres Quintana|https://github.com/ArmaTQ|
|Iván|https://github.com/ivandelaparte|


### Colaborador agregado
[ivandelaparte](https://github.com/ivandelaparte "https://github.com/ivandelaparte")