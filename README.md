# ¿Qué es una *pull request*?
![portada](https://media.makeameme.org/created/look-pull-requests.jpg)

Una pull request es una petición de validación de cambios que se hace a un repositorio.

Es la manera en la que se muestra una sugerencia de cambio sobre el código del repositorio original.

En vuestro caso, la **pull request** va a ser el método de entrega para todos los labs durante este bootcamp.

## 🧠¿Pero cómo hacemos una *pull request*?🧠

Cada día tendréis disponible un nuevo repositorio en la organización de GitHub de [Ironhack](https://github.com/Ironhack-Data-Madrid-Enero-2022) con el lab correspondiente al material dado durante las clases.

También podéis encontrar el link al lab directamente en el **Student Portal**.

### Los pasos a seguir son los siguientes:

1. **Forkear**  :fork_and_knife: el repo del lab desde el GitHub de [Ironhack](https://github.com/Ironhack-Data-Madrid-Enero-2022) (aparecerá un repo con el mismo nombre en tu cuenta de GitHub)
![img_pull1](https://github.com/Fominayasg/Instrucciones_pull-request/blob/main/images/img_1.jpg)

2. Copiar el link del nuevo repo de **MI GitHub**.
    1. Pulsar el botón verde **CODE**
    2. Copiar el link
![img_pull2](https://github.com/Fominayasg/Instrucciones_pull-request/blob/main/images/img_2.jpg)

3. Ir a la **terminal** y navegar hasta la carpeta donde yo quiera tener mi lab.
Una vez en la carpeta adecuada, escribo el siguiente comando: **`git clone www.el-link-a-mi-repo.com`**. Ya tenemos el lab en nuestro ordenador!!! Bien!!
4. Hacemos un **cambio** en algun archivo. Si o lo hacemos, como nuestro código es exacto al del repositorio original, no podremos hacer la pull request.
5. Volvemos a la terminal y asegurándonos de estar en la carpeta principal del repositorio en el que estamos trabajando, ejecutamos los siguientes comandos uno por uno.
    1. `git status` (veremos los archivos cambiados)
    1. **`git add nombre_archivo_cambiado`**
    2. **`git commit -m "mensaje"`** (sustituye "mensaje" por la descrioción del cambio que vaya a commitear)
    3. **`git push origin main`** (sustituye "main" por "master" si tu rama principal se llama así)
6. Hacer la **PULL REQUEST** en el repo original del lab en GitHub:
Nombre de la pull request [Nombre del lab]Nombre Apellido
7. Comentario de la pull request (si hay algo en lo que tengo dudas o que se me ha atascado especialmente o memes)

