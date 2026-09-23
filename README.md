# Habits & Routines · EnglishPRO

App de práctica de *used to*, *usually*, *be used to* y *get used to* (ESO / Bachillerato), con el mismo motor que [present-tenses](https://github.com/nuriacalvo-teacher/present-tenses).

**5 módulos × 3 niveles, con 10 ejercicios por nivel:**

1. Used to (do)
2. Usually (do) vs Used to (do)
3. Be used to (doing)
4. Get used to (doing)
5. Master Quiz: Habits & Routines

- **Level 1:** opción múltiple (hace falta un 90 % para aprobar)
- **Level 2:** rellenar huecos (80 %)
- **Level 3:** traducción del español al inglés (80 %)

Cada nivel empieza con la explicación del módulo. Los alumnos pueden entrar con su cuenta de Google y el código de clase, o como invitados (en ese caso no se guarda nada). El panel del profesor se abre con tu cuenta de Google.

## Corrección de las traducciones

Se aceptan todas las respuestas correctas, no solo la del modelo:
- sinónimos (phone/mobile, mum/mother, timetable/schedule, *be used to* / *be accustomed to*…)
- contracciones (I'm = I am, didn't = did not…)
- el orden de las palabras
- otras formas que también sean correctas en esa frase (*would play* o *played* para un hábito pasado)
- *he* o *she* cuando la frase en español no lleva sujeto

Dentro de una respuesta, `[a|b]` significa "vale a o b" y `[a|]` que la palabra es opcional.

## ⚠️ Firebase: hay que hacer una cosa una sola vez

Esta versión guarda los resultados en su propio nodo, **`habits_v2`**. La versión anterior los guardaba en `results`; esos datos siguen en Firebase, pero el panel nuevo no los muestra.

En la consola de Firebase (proyecto *goya-english*): Realtime Database → **Reglas**. Duplica el bloque de `present_tenses_v2`, cambia el nombre a `habits_v2` y publica.

Hasta que no lo hagas, el modo invitado funciona, pero la entrada con código de clase mostrará "Wrong class code".
