# Práctica 1

Un repositorio para empezar a usar [git](https://git-scm.com/) y Github

## ¿Como probar en la nube?

[Github-Codespaces](https://github.com/features/codespaces)

## Comandos git básicos

```
git clone https://github.com/gitt-3-pat/p1
git status
git add .
git commit -m "TU MENSAJE"
git push

git checkout -b feature/1
git checkout main
```

## ¿Cómo escribir un README.md con formato?

[Github Markdown](https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

- [x] **¿Cómo probar en la nube?** :+1:
- [x] **¿Cómo escribir un README.md con formato?** :+1:
- [ ] Memoria explicativa
- [ ] Enlaces de interés

## MEMORIA EXPLICATIVA- PROGRAMACIÓN APLICACIONES TELEMÁTICAS[^1]
A lo largo de esta memoria explicaremos brevemente los comandos utilizados en la práctica e incluiremos una captura del código introducido en la terminal.

### 1.Git Clone
<img width="574" alt="Imagen1.png" src="https://github.com/paofcheca/p1/blob/main/Imagenes/Imagen1.png" />

Este comando nos permite <ins>clonar</ins> un repositorio a partir de su URL en el nuestro.

### 2.Git Status
<img width="574" alt="Imagen2.png" src="https://github.com/paofcheca/p1/blob/main/Imagenes/Imagen2.png" />

Git Status muestra el <ins>estado actual</ins> del repositorio local. 
> [!NOTE]
> Incluye cambios que aún no se han guardado (staged o unstaged), la rama en la que estás trabajando o archivos nuevos que no están siendo rastreados.

### 3.Git Add .
<img width="574" alt="Imagen3.png" src="https://github.com/paofcheca/p1/blob/main/Imagenes/Imagen3.png" />

Git Add añade archivos al <ins>área de preparación</ins> (staging area). 
> [!IMPORTANT]
> Esto prepara a los archivos para ser incluidos en el próximo commit.

### 4.Git Commit
<img width="574" alt="Imagen4.png" src="https://github.com/paofcheca/p1/blob/main/Imagenes/Imagen4.png" />

Este comando guarda los cambios en el <ins>historial</ins> del repositorio. Un commit representa un punto de control del desarrollo.

### 5.Git Push
<img width="574" alt="Imagen5.png" src="https://github.com/paofcheca/p1/blob/main/Imagenes/Imagen5.png" />

Git Push <ins>sincroniza los cambios y envía los commits</ins> locales al repositorio remoto.

### 6.Git Checkout
<img width="574" alt="ImagenCheck.png" src="https://github.com/paofcheca/p1/blob/main/Imagenes/Imagen6.png" />

Git Checkout permite:
* Restaurar archivos
* Cambiar de rama
 > [!TIP]
>Para crear una nueva rama utilizamos <ins>**flag -b**<ins>.

## ENLACES A OTROS ARCHIVOS

### Explicación comandos
[Ver git.pdf](git.pdf)

### Evidencia instalación del software y su funcionamiento
[Ver entorno.pdf](entorno.pdf)

[^1]: Paola Fernández-Checa Clemente
