# Proxmox: Línea de comandos.
## Descripción

La idea de este proyecto es automatizar un entorno de trabajo real.

- Estamos en un centro educativo y necesitamos:

- Crear grupos de trabajo para alumnos y profesores.

- Crear usuarios y asignarles un determinado grupo.

- Crear pools (recursos).

- Crear nuevos roles.

- Asignar a usuarios o a grupos permisos (roles) sobre los pools creados anteriormente.

- Poner a disposición de los usuarios plantillas de contenedores y máquinas virtuales.

- Deshacer la estructura anterior.

La información estará guardada en un fichero llamado ** usuarios.txt ** .

Ese fichero puede ser lo complejo que se necesite. Para simplificarlo hemos supuesto que dicho fichero solo tiene dos campos:

nombre de usuario: contraseña


Veremos los comandos necesarios para automatizar el proceso.

Vamos a crear pequeños scripts, que vayan incrementando cada uno de los apartados.

Para finalizar lo haremos todo en un script final.

Espero que alguién le pueda servir.


## Contenidos
1. Conociendo el Clúster

  - [Conociendo el Clúster](modulo1/cluster.md)

2. Gestión de usuarios y grupos

  - [Gestión de usarios y grupos](modulo2/usuariosygrupos.md)

  - [Script: Creación masiva de usuarios](modulo2/creacionusuarios.md)

3. Creación de pools

 - [Creación de pools](modulo3/creacionpools.md)
 
 -[Script: Creación de pools](modulo3/creacionpools.sh)
 

## Referencias
  * [proxmox](https://pve.proxmox.com/pve-docs/api-viewer)

## Licencia

