## WriteUp
1 - Entendiendo el nombre de los archivos.

Como podemos observar y el enunciado nos dice, el nombre de los archivos esta encrypted a excepcion del iv.txt
Sabiendo como referencia que este es el correcto (por la extension .txt), podemos deducir comparandolo con este que el acabado en == debe ser base64 y que el restante esta encrypted por un cifrado cesar (ROT13)

2 - Una vez descifrados con cualquier herramienta (como por ejemplo cybercheff) podemos ver que los nombres son;
key.txt y entrada.txt

Con un IV (vector de inicializacion), una key y una entrada no es dificil pensar en AES.

3 - Resolviendo 
Bastará con ir de nuevo a cybercheff o similar, seleccionar AES Decrypt e introducir dentro de cada caja su correspondencia (El contenido del fichero key.txt en key, el contenido de iv.txt en iv, y el de entrada.txt como input...)

Una vez hecho esto podremos ver en el output la solucion;

Confirmamos el despliegue del arma quimica, estan autorizados para lanzarla en Manhattan tras el exito de nuestra prueba. Codigo de activacion: C0r0n4_V1ruS
