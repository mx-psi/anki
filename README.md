# ¿Qué es Anki?

[Anki](https://apps.ankiweb.net/index.html) es un programa de software libre para utilizar la técnica de [repetición espaciada](https://codual.github.io/2016/07/07/repeticion-espaciada/) mediante *flashcards*.

# ¿Qué contiene este repositorio?

Es una colección de las tarjetas que he ido utilizando en el doble grado de Ingeniería Informática y Matemáticas de la Universidad de Granada, divididas por mazos en función de la asignatura (¡no están todas!).

Por favor, **ten en cuenta las siguientes advertencias**:

- El contenido de las tarjetas puede ser incorrecto y se corresponde sólo con lo que di en ese curso (lo que puede que difiera del que estés dando tú). Son bienvenidas correcciones y añadidos.
- Originalmente no hice las tarjetas con el objetivo de compartirlas así que pueden contener notación no estándar, anotaciones personales o simplemente ser poco claras para tí. Si encuentras alguna anotación o contenido que no vaya a serte útil al utilizar las tarjetas considera hacer un Pull Request. Gracias!

Dicho esto, mi recomendación es que utilices las tarjetas como base y conserves sólo las que se correspondan con el contenido que quieres memorizar. Si te han sido útiles nunca está de más contactar conmigo para decírmelo :D

# ¿Cómo puedo utilizarlo?

## Formato antiguo (`.apkg`)

Los mazos originales están en `.apkg`.

Cada archivo `apkg` puede importarse en Anki para estudiar el contenido de la asignatura. Para poder generar las fórmulas necesitas tener instalado LaTeX junto con el paquete [dvipng](https://en.wikipedia.org/wiki/Dvipng).

Algunos de los mazos pueden tener información de programación que deberás borrar manualmente mediante las opciones de Anki.

Puedes actualizar el formato siguiendo las instrucciones de [#6](https://github.com/mx-psi/anki/pull/6).
¡Recuerda hacer un PR para evitar que los demás tengan que hacerlo también!

## Formato nuevo (.json)

El nuevo formato está en `.json` e incluye las fórmulas con MathJax.
Para este formato necesitas tener instalado:

- Anki 2.1 y
- el plugin [CrowdAnki](https://github.com/mx-psi/anki/pull/6).

Importa con la opción de CrowdAnki **la carpeta** asociada a un mazo.


