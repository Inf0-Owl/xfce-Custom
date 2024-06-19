### Tipografia

Primero conseguimos una tipografia desde internet, por ejemplo de [Nerd-Fonts](https://www.nerdfonts.com/font-downloads).

Y podemos descargarla con wget y el link de descarga:
`wget https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/BigBlueTerminal.zip`

O directamente dandole en el botón "Download":

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/f8f653c5-f596-42ff-9e32-41bc61f9a231)

Nos generará un .zip, lo descomprimimos con `unzip nombre_de_archivo.zip`

Luego los movemos a la carpeta ".fonts".

Podemos mover el contenido desempaquetado de la descarga a ese directorio (Desde el directorio donde descomprimimos):
`mv *ttf ~/.fonts`


La otra forma es crear el directorio:
- `mkdir ~/.fonts`

Movernos al directorio ".fonts":
- `cd ~/.fonts`

Descargar nuestra fuente al directorio ".fonts":
`wget [liga de la tipografía]`

Y descomprimir el archivo:
`unzip nombre_de_archivo.zip`

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/d6c956d9-a63d-4303-ad12-d662fe44aa2e)

[Back to intro](../Intro.md)
