# Examen práctico de Git

## Objetivo

El objetivo de este examen es evaluar el manejo práctico de **Git**, especialmente el trabajo con repositorios, ramas, commits e integración de cambios realizados por otros compañeros.

Cada estudiante deberá realizar el proceso de manera individual y trabajar utilizando **su propia rama**.

---

## 1. Clonar el repositorio

Cada estudiante deberá comenzar **clonando el repositorio proporcionado por el instructor** en su computador.

Una vez clonado, deberá ingresar al proyecto y verificar que el repositorio se encuentre correctamente configurado.

---

## 2. Crear una rama personal

Cada estudiante deberá crear una nueva rama utilizando su **nombre y apellido**.

### Importante

Los nombres de las ramas **no deben contener espacios**.

Para separar las palabras pueden utilizar el carácter `_`.

### Ejemplo

Si el estudiante se llama:

**Juan Pérez Gómez**

El nombre de su rama podría ser:

`juan_perez_gomez`

Después de crearla, deberá **moverse a su nueva rama** y comprobar que efectivamente está trabajando sobre ella.

> ⚠️ No se debe realizar el examen directamente sobre la rama `main`.

---

## 3. Crear un archivo de información personal

Dentro del proyecto deberá crear un archivo `.txt` utilizando su nombre.

### Ejemplo

`juan_perez.txt`

El archivo deberá contener como mínimo:

- Nombre completo.
- Fecha de nacimiento.
- Una breve descripción personal.
- Actividades que le gusta realizar en su tiempo libre.

### Ejemplo de contenido

Nombre completo: Juan Pérez Gómez  
Fecha de nacimiento: 15 de marzo de 2005

Me gusta aprender sobre tecnología y desarrollo de software.

En mis tiempos libres me gusta escuchar música, jugar videojuegos, ver películas y compartir con mis amigos.

---

## 4. Realizar el primer commit

Después de terminar el archivo de información personal deberá:

1. Verificar los cambios realizados en el repositorio.
2. Agregar el archivo al área de preparación.
3. Realizar un **commit**.

El mensaje del commit deberá describir claramente el cambio realizado.

### Ejemplo de mensaje

`Agrega información personal de Juan Pérez`

---

## 5. Crear un archivo sobre un tema de interés

Cada estudiante deberá seleccionar **un tema que le guste o sobre el cual tenga interés**.

Algunos ejemplos pueden ser:

- Videojuegos.
- Música.
- Deportes.
- Programación.
- Inteligencia artificial.
- Motocicletas.
- Cine.
- Tecnología.
- Viajes.
- Animales.
- Otro tema de su interés.

Deberá crear un segundo archivo `.txt`.

El nombre del archivo deberá estar relacionado con el tema seleccionado.

### Ejemplo

`videojuegos.txt`

Dentro del archivo deberá escribir **con sus propias palabras** sobre el tema seleccionado.

Deberá explicar brevemente:

- De qué trata el tema.
- Por qué le gusta o le interesa.
- Algún aspecto que considere interesante.
- Su opinión personal sobre el tema.

---

## 6. Realizar el segundo commit

Después de terminar el segundo archivo deberá:

1. Verificar los nuevos cambios.
2. Agregar el archivo correspondiente.
3. Realizar un nuevo **commit**.

El mensaje deberá describir correctamente el cambio realizado.

### Ejemplo de mensaje

`Agrega información sobre videojuegos`

Al llegar a este punto, el estudiante deberá tener **como mínimo dos commits propios** realizados en su rama.

---

## 7. Publicar su rama

Una vez realizados los dos commits, el estudiante deberá **publicar su rama en el repositorio remoto**.

La rama publicada deberá conservar el nombre definido inicialmente con su nombre y apellido.

---

## 8. Seleccionar la rama de otro compañero

Cada estudiante deberá seleccionar la rama de **otro compañero del grupo**.

Deberá actualizar la información del repositorio para poder identificar las ramas que han sido publicadas por los demás estudiantes.

Posteriormente deberá seleccionar una de ellas para realizar el proceso de integración.

---

## 9. Traer cambios de otra rama

El estudiante deberá permanecer ubicado en **su propia rama**.

Desde ella deberá traer e integrar los cambios realizados en la rama del compañero seleccionado.

### Ejemplo

Si su rama es:

`juan_perez`

Y seleccionó la rama:

`maria_gomez`

Los cambios de `maria_gomez` deberán quedar incorporados dentro de `juan_perez`.

> ⚠️ Antes de realizar la integración, compruebe que se encuentra ubicado en su propia rama.

---

## 10. Resolver posibles conflictos

Durante la integración pueden presentarse **conflictos**.

Si Git detecta un conflicto, el estudiante deberá:

1. Identificar el archivo o archivos afectados.
2. Revisar las diferencias existentes.
3. Determinar qué información debe conservarse.
4. Corregir manualmente el contenido.
5. Eliminar correctamente las marcas de conflicto.
6. Guardar los archivos.
7. Completar el proceso de integración.

La aparición de un conflicto **no significa que el examen esté incorrecto**. Hace parte de las situaciones que pueden presentarse al trabajar colaborativamente con Git.

---

## 11. Publicar el resultado final

Una vez terminada la integración, el estudiante deberá comprobar que los archivos propios y los archivos provenientes de la otra rama se encuentren correctamente dentro de su rama.

Finalmente deberá **publicar los cambios finales en el repositorio remoto**.

---

# Resultado esperado

Al finalizar el examen, cada estudiante deberá tener:

1. El repositorio correctamente clonado.
2. Una rama personal identificada con su nombre.
3. Un archivo `.txt` con su información personal.
4. Un commit correspondiente a su información personal.
5. Un segundo archivo `.txt` sobre un tema de su interés.
6. Un segundo commit correspondiente al tema seleccionado.
7. Su rama publicada en el repositorio remoto.
8. Cambios provenientes de la rama de otro compañero.
9. La integración entre las ramas realizada correctamente.
10. Los cambios finales publicados en el repositorio remoto.

---

# Reglas del examen

- Cada estudiante debe trabajar inicialmente **únicamente en su propia rama**.
- No se permite desarrollar el examen directamente sobre `main`.
- La rama debe identificar claramente al estudiante.
- Los nombres de las ramas **no deben contener espacios**.
- Se puede utilizar `_` para separar palabras en el nombre de la rama.
- Los archivos deben contener información escrita por el estudiante.
- Cada actividad solicitada deberá tener su respectivo commit.
- Los mensajes de los commits deben describir claramente los cambios realizados.
- No se debe eliminar el trabajo realizado por otros compañeros.
- Antes de integrar otra rama, el estudiante deberá verificar en qué rama se encuentra.
- Si se presenta un conflicto, deberá resolverlo correctamente.
- El resultado final deberá quedar publicado en el repositorio remoto.
- **El estudiante deberá conocer y utilizar por su cuenta los comandos de Git necesarios para completar cada punto.**

---

# Flujo general del examen

**Clonar repositorio → Crear rama personal → Cambiar a su rama → Crear primer archivo → Primer commit → Crear segundo archivo → Segundo commit → Publicar rama → Obtener cambios de otro compañero → Integrar ramas → Resolver conflictos si existen → Publicar resultado final**

## Importante

Durante el examen **no se proporcionarán los comandos necesarios para realizar cada procedimiento**.

El estudiante deberá demostrar que comprende qué operación de Git necesita realizar en cada etapa y utilizar correctamente los comandos aprendidos durante la formación.
