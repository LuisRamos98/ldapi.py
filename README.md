# ldapi.py
Fuerza Bruta en Servidor LDAP
Este código en Python utiliza fuerza bruta para obtener el valor de un atributo de los usuarios en un servidor LDAP en un entorno controlado. El código se ejecuta en un entorno local y se enfoca en descubrir el número de teléfono (telephoneNumber) de los usuarios.

Funcionalidad
El código realiza las siguientes acciones:

Realiza peticiones HTTP al servidor LDAP local en http://localhost:8888/ utilizando la librería requests.

Utiliza una lista de caracteres válidos (letras minúsculas y dígitos) para adivinar los valores del atributo "user_id" de los usuarios.

Una vez que encuentra usuarios válidos, continúa adivinando los valores de los números de teléfono (atributo "telephoneNumber") utilizando fuerza bruta.

Muestra los usuarios válidos encontrados y los números de teléfono descubiertos.

Uso
Asegúrate de tener instalada la librería requests.

Ejecuta el script en un entorno controlado y local.

El código intentará adivinar los usuarios válidos y los números de teléfono en el servidor LDAP.

Los resultados se mostrarán en la consola.

Notas
Este código es solo para fines educativos o en entornos donde tengas permiso para realizar pruebas de seguridad. El uso no autorizado de fuerza bruta en sistemas ajenos es ilegal y puede tener consecuencias legales.
