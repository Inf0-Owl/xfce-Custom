# LEVEL EXTRA

## LSD

Es similar al comando ls, pero con esteroides.

En si la mayor diferencia es que nos despliega las cosas con "más dieseño".

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/b3141b4b-1ee2-4803-aa54-2a061930f6c3)

Para instalarlo solo usamos: `sudo apt install lsd -y`.

## BATCAT

Ahora una alternativa al comando `cat` muy cool, pero externa, es bat, que hace lo mismo pero más bonito, ya que no solo muestra el contenido de un archivo, sino que reconoce de que tipo es, y lo muestra de forma comprensible.

En kali basta con llamar al comando:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/c0e0ea05-37df-4783-9824-83f7abb2ef72)

Para usarlo usamos el comando y el nombre de archivo:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/948f30f0-545b-48c6-99b7-50ee2209c336)

## Alias

Para poder usar lsd como ls, y batcat como cat, vamos a tener que editar el archivo `.zshrc`, esto si dejaste como predeterminado el shell de zsh, en caso de haber puesto bash, tienes que modificar el archivo `.bashrc`.

Lo abrimos con nano:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/c69886b7-ac43-449d-9829-9476e1452ebc)

Buscamos, la parte de los alias:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/e4674e8d-72a0-48ee-a884-ba3aa623f69a)

El comando de la izquierda es lo que vamos a escribir en terminal, el de la derecha, lo que ese comando va a ejecutar.

## HTOP

Es un sistema de visualización y manejo de procesos:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/fa47e0fe-00ca-495e-9af9-8cab21a68627)

Podemos instalarlo con: `sudo apt install htop -y`

## Ranger

Un sistema de manejo de archivos basado en vim:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/a940dd67-54c1-415a-9355-1e455d0b77c0)

Puedes instalarlo con `sudo apt install ranger -y`

## nvim

Un editor de texo minimalista para la terminal, su predecesor es vim.

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/704f66c5-33c0-4886-b8f9-7ef560bf5260)


Puedes instalarlo con `sudo apt install nvim -y`

Con este recomiendo visitar [nvchad](https://nvchad.com/)

## Symbols

Para que todo lo relacionado con iconos funcione bien, te recomiendo descargar también está [font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/NerdFontsSymbolsOnly.zip)

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/e1149d88-74f2-42fe-b7ef-b50c7f6143cf)

Que es completamente de puros simbolos, para que los reconozca tu sistema.

# Documentación y referencias:

[batcat](https://github.com/sharkdp/bat)

[lsd](https://github.com/lsd-rs/lsd)

[nvim](https://neovim.io/)

[htop](https://htop.dev/)

[ranger](https://github.com/ranger/ranger)

