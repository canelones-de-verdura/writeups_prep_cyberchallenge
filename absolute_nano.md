# ABSOLUTE NANO (picoCTF 2026)

> General Skils, Medium

*You have complete power with nano.*

*Think you can get the flag?*

## Explorando el entorno

El reto consiste en una instancia a la que hay que conectarse por ssh. Ya de entrada podemos ver la flag en el home de nuestro usuario:

![](./imágenes/3.1.png)

Pero no podemos ver que contiene, ya que no tenemos permisos:

![](./imágenes/3.2.png)

Bueno, con `sudo`:

![](./imágenes/3.3.png)

Bueno, con alguna otra cosa que no sea `cat`

![](./imágenes/3.4.png)

Bueno.

## *Qué* podemos usar con sudo?

![](./imágenes/3.5.png)

Con razón *complete power with nano*. Vamos a editar *sudoers* para darle permisos a nuestro usuario:

![](./imágenes/3.6.png)

![](./imágenes/3.7.png)

*yendo al final del todo copiamos el permiso que ya tenía el usuario*

Y pronto:

![](./imágenes/3.8.png)
