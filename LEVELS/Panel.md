# LEVEL 6

## Panel -_-

Va a estar tardado esto, preparate, ve toma un coffe, y alistate para esto...

Cuando instalamos kali linux con xfce, tiene esta barrita de arrbia:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/b076a8ff-400b-4f70-9139-ecb3e01eac1d)

Esa barra se llama "Panel".

Tiene un diseño un cuanto simple a mi parecer, así que vamos a configurarlo.

Si damos clic derecho sobre la barra, veremos: 
- Las opciones del item seleccionado.
- Properties: Propiedades del item.
- Move: Nos permite mover el item a otra posición.
- Remove: Para quitar el item.
- Panel: Las opciones para la modificación del panel en general.
	- Add new items: para añadir otros items al panel.
	- Panel preferences: Dónde podemos modificar el panel en sí.
	- logout
	- help
	- about

### Apariencia / diseño

Vamos a modificar el panel:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/e0962cef-1024-4b3c-846f-ad48e91be7f9)

Cosas que me gustan así como están son:
- Row size: 34
- Number of rows: 1
- Autmatically increase the length: Para que el panel se adapte a la cantidad de items que le pongamos.
  - Este sí lo llego a cambiar en algunos casos, para que no se mueva de más.  
- Automatically hide the panel: Never
- Reserve space on screen edges for the panel: Evita que se encime con las cosas en el escritorio.
- Lock panel: Para que no se mueva del lugar dónde lo queremos.

***NOTA: Puedes modificar cada item en la barra, en sus preferencias, para cambiar su comportamiendo o presentación.***

Ahora vamos a revisar el apartado "Appearance":

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/3bf23b9f-d6f8-48e9-959a-78ee929f4af0)

En estilo podemos usar un color solido, lo cual incluye colores transparentes:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/4344f9d9-75f0-4a41-a7ce-ad70d3458cd6)

Podemos crear un color personalizado "+":

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/805b9a0e-bead-4dc6-bc27-72c7276147f2)

La barra de abajo es para la transparencia.

### Items

Podemos modificar también los items:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/43a325b1-f13a-4e05-bc29-591e7d13e9ed)

Se enlistan en el orden que estan, de izquierda a derecha.

## More Panels

Ahora, otra cosa mucho más interesante, podemos tener más de 1 panel:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/52c38fd1-9a8f-4ca3-bda0-c8e162749f85)

Vamos a configurar un segundo panel ahora, (le damos en +):

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/d5d2f42e-6321-4cf2-a960-f06176d286da)

El panel que estemos modificando, se resaltará en rojo:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/218117ce-46dd-4c1c-9d1d-93f966a5a6a9)

En mi panel 2, tendré unicamente estás aplicaciones :

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/08008156-9ef3-4fc2-876b-f5d7d54e1526)

ESTE ES MI CASO, TU CONFIGURA COMO QUIERES, PERO PRIMERO LEE BIEN ESTE NIVEL.

Para configurar el launcher:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/2703d0cd-f327-4576-84ee-5980f91050b1)

Le damos en "+" para añadir aplicaciones ligadas a ese launcher.

Podemos escoger entre todas las aplicaciones que tenemos instaladas:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/16867622-c043-4816-b9f4-3259c98d8f35)

Ahora las aplicaciones que tengo en este segundo panel, las voy a quitar del primero, y lo voy a encoger.

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/6aa45d28-d6d3-4540-96ab-027b432eb669)

Una vez seleccionado el item, lo eliminamos con "-remove".

Ahora hagmos espacio para el segundo panel.

Desbloqueamos el panel (Lock Panel) y reducimos su tamaño (Length):

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/0732525b-a166-4b62-9447-f0f95b0fa5e2)

Ahora solo acomodamos uno a lado del otro con el mouse:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/26040dc9-b0f3-45be-949c-78efbc819eed)

Y podemos bloquearlos en ese lugar (Lock panel), si ya los queremos dejar ahí.

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/5ff305b6-12ed-48ba-85f5-fe495e567c72)

Resultado con 4 paneles, uno para las aplicaciones de menu, 
otro para mostrar las aplicaciones del workspace actual, 
otro para espacios de trabajo, y otro para items del sistema:

![image](https://github.com/Inf0sth/Kali-linux-Custom/assets/106565371/ca973f01-cf6e-482b-8dbd-a1562e37a7a4)

[Back to Intro](../Intro.md)

Esto también te puede interesar:
- [Special Items](../SUB-LEVELS/Special_Items.md)
- [Whisker-Menu](../SUB-LEVELS/Whisker-Menu.md)
- [Workspaces](../SUB-LEVELS/Workspaces.md)
