# Caso de evaluación (5pts)

Su empresa se dedica a recibir dispositivos para repararlos. En algunos casos, no
se puede reparar y deben solicitar un dispositivo nuevo. Cuentan con una base de
datos muy grande donde se registra el estado de cada componente del dispositivo,
y un dato final indicando si pudo repararse o si fue necesario solicitar un dispostivo
nuevo.

Le solicitan que haga y entrene un modelo con esos datos, para que al final se
ingresen los datos de los componentes, y muestre una predicción indicando si el
dispostivo puede repararse, o si debe solicitarse uno nuevo.

## Responda a las siguientes preguntas:

### ¿Qué tipo de modelo aplicaría?

Aplicaria el modelo de arbol de decision por clasificacion.

### ¿Por qué consideras que ese modelo es adecuado?

Este modelo es el idoneo, dado que al final, la predicción se limita a dar dos respuestas, lo cual indica que la variable objetivo es un problema categorico/discreto al solo haber dos posibles respuestas y no un rango, donde si seria util un modelo de regresion.

## Ahora ha aplicado algunos algoritmos de machine learning en datos:

### ¿De qué manera considera que es diferente a la programación regular, para este tipo de proyectos?

En la programación regular debemos (aparte de analizar los datos) programar un algoritmo con las variables independientes,
en este caso nos centramos mas en el analisis y manipulacion de datos para poder entrenar un modelo, no somos conscientes de la logica de prediccion.

### ¿Por qué cree que los modelos como los vistos en las clases no logran llegar a un 100% de respuestas correctas?

Aparte de que los modelos vistos en clase son los basicos, los datos del mundo real son muy complejos, la idea de estos modelos es acertada pero no capturan muchas caracteristicas importantes y no soportan tal nivel de caos.
