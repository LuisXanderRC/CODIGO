# Primer día con Git/Github

Lista de comandos de Git

- Para poder ver la version de Git

```bash
git --version
```

- Comando para configurar el usuario y el correo

```bash
git config --global user.email "email"
```

- Para poder configurar el username

```bash
git config --global user.name "username"
```

- Sirve para poder empezar a usar el control de version (git) un nuestra carpeta.

- Esto se hace solo una vez por carpeta

```bash
git init
```

- Para ver el estado de nuestros cambios

```bash
git status
```

- Agrega los archivos a la memoria de la PC

```bash
git add .
```

- Crea el registro de los cambios realizados

```bash
git commit -m "comentario"
```

- Para poder ver el historial de commits

[ ] Git log retorna un `id` con este id vamos a poder ver el detalle de los cambios que se hicieron en ese commit.

```bash
git log
```

- Para poder ver el detalle del commit usamos

```bash
git show id-de-commit
```

- Para cambiar el nombre de la rama

```bash
git branch -M main
```

```bash
git push origin main
```
