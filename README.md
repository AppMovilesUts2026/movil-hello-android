# Taller 2 - Arquitectura MVVM Fragments y Navigation component

## Información del Estudiante
<<<<<<< HEAD
- Nombre: Sergio Rodríguez _  Michael Alberto Romero Gonzalez _ Anderson Sanguino Suarez _ Marlon Andres Ramirez Chirivi
- Código: 1098820679 _ 100487913 _ 1005538900 _ 1095950857
- Fecha: 06/03/2026
=======
- Nombre: Sergio Rodríguez _  Michael Alberto Romero Gonzalez _ Anderson Sanguino Suarez - Marlon 
- Código: 1098820679 _ 100487913 _1005538900
- Fecha: 06/03/202
>>>>>>> 7fd00a0b72e8ad62951228a225ff40a595e81d43

## Respuestas

## Pruebas de Comprensión
### ¿Por qué los datos no se pierden al rotar? Explicar el rol del ViewModel.
Porque el ViewModel guarda los datos y no se destruye cuando la pantalla rota. Cuando la Activity o Fragment se recrea, el ViewModel mantiene la información y la vuelve a mostrar.
### ¿Qué ventaja tiene usar LiveData en lugar de actualizar la UI manualmente?
LiveData actualiza la interfaz automáticamente cuando cambian los datos, evitando tener que actualizar la UI manualmente y reduciendo errores.
### ¿Qué problema resuelve Safe Args comparado con usar Bundle manualmente?
Safe Args evita errores de tipo de datos al pasar información entre fragments. Con Bundle puedes equivocarte en nombres o tipos; Safe Args lo valida automáticamente.

## Respuestas a Preguntas Conceptuales
#### 1. ¿Qué problema resuelve el ViewModel en Android?

   El ViewModel guarda y maneja los datos de la interfaz, evitando que se pierdan cuando la pantalla cambia o se recrea.

#### 2. ¿Por qué LiveData es "lifecycle-aware" y qué beneficio trae?

   Porque solo actualiza la UI cuando la Activity o Fragment está activo, evitando errores y consumo innecesario de recursos.

#### 3. Explica con tus propias palabras el flujo de datos en MVVM

   El Model contiene los datos, el ViewModel los procesa y el View (Activity o Fragment) los muestra en pantalla.

#### 4. ¿Qué ventaja tiene usar Fragments vs múltiples Activities?

   Los Fragments permiten reutilizar partes de la interfaz dentro de una misma Activity y hacen la navegación más flexible.

#### 5. ¿Cómo ayuda el Repository Pattern a la arquitectura?

   El Repository organiza el acceso a los datos (base de datos, API, etc.) y separa esa lógica del resto de la aplicación.



   



<<<<<<< HEAD
![Captura del emulador](docs/captura_emulador_1.png)
![Captura del emulador](docs/captura_emulador_2.png)
![Captura del emulador](docs/captura_emulador_3.png)
![Captura del emulador](docs/captura_emulador_4.png)
=======
>>>>>>> 7fd00a0b72e8ad62951228a225ff40a595e81d43
