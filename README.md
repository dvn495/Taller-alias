# Taller-alias
**EJERCICIO 1**

`git log --graph --decorate --all -n 5`

**--graph**: Muestra una reprentación grafica del historial de commits.
**-decorate**: Muestra las referencias de las ramas (como los nombres de las ramas o las etiquetas) junto a los commits en el registro.
**--all**:  Muestra los commits de todas las ramas.
**--n 5**: Limita la salida a los ultimos 5 commits.

**EJERCICIO 2**


`git log --graph %C(red)%h%C(reset) %C(yellow)%d%C(reset) %s%C(reset) %Cgreen(%ar)%C(reset) --abbrev-commit --date=relative`

**--graph**: Muestra una representación gráfica del historial de commits.
**%C(red)%h%C(reset)**: Muestra el hash corto del commit en color rojo.
**%C(yellow)%d%C(reset)**: Muestra las referencias (ramas o tags) en las que está involucrado el commit en color amarillo.
**%s%C(reset)**: Muestra el mensaje del commit.
**%Cgreen(%ar)%Creset**: Muestra la fecha relativa del commit en color verde.
**--abbrev-commit**: Muestra el hash del commit como un identificador abreviado.
**--date=relative**: Muestra las fechas de los commits de forma relativa.

**EJERCICIO 3**


`git config --global alias.lG "log -1 HEAD"`

Este comando va a crear un alias llamado lg que representa el comando git log -1 HEAD. Ahora, cuando se ejecute git lg, Git ejecutará el comando git log -1 HEAD.

**EJERCICIO 4**


`git config --global alias.ec "config --global --edit"`

Este comando crea un alias global llamado ec, que permite abrir la configuración global de Git en el editor de texto predeterminado cuando se ejecute git ec.

**EJERCICIO 5**


`git config --global alias.ec "config --global --edit"`

**--graph**: Muestra una reprentación grafica del historial de commits.
**--abbrev-commit**: Muestra el hash del commit de manera abreviada.
**--decorate**: Muestra las referencias de las ramas (como los nombres de las ramas o las etiquetas) junto a los commits en el registro.
**--pretty=format**: Define el formato de salida del registro de commits.
**%C(color)**: Especifica el color del texto.
**%h**: Muestra el hash abreviado del commit.
**%d**: Muestra las referencias (ramas o tags) que apuntan a cada commit.
**%S**: Muestra el resumen del commit.
**%s**: Muestra el mensaje del commit.
**%an**: Muestra el nombre del autor del commit.

