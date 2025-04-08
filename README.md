# Fundamentos de Programación Web - Examen Parcial I

## Universidad Nacional
### Sede Regional Chorotega, Campus Nicoya
**Curso:** Fundamentos de Programación Web  
**Examen:** Examen Parcial I, I Ciclo 2025  
**Valor:** 15%, Total de puntos: 100 puntos.  
**Profesora:** Gloriana Peña Ramírez  
**Fecha del examen:** 8-04-2024  
**Hora:** 05:00 p.m.

## Instrucciones Generales
Realice cada uno de los siguientes ejercicios utilizando las herramientas aprendidas en clase y conocimientos autodidactas. La programación debe realizarse en JavaScript.

## Ejercicio 2: Diseño de una Ventana de Selección de Asientos de Teatro

### Objetivo
El objetivo de este ejercicio es diseñar la vista de reserva de asientos para la sala principal del teatro "TEATRO-UNA". La página debe representar el escenario del teatro, la disposición de asientos, un formulario para elegir el número de asientos y un pie de página con información del teatro.

### Requisitos
- **HTML**: Estructura de la página.
- **CSS**: Estilización de los elementos.
- **Bootstrap**: Uso permitido mediante CDN únicamente.

### Instrucciones
Diseñe una página web que incluya lo siguiente:
- Una representación visual del escenario del teatro.
- Selección de asientos con filas y números, indicando cuáles están ocupados o disponibles.
- Un formulario que permita al usuario seleccionar el número de asientos que desea reservar.
- Un botón para confirmar la reserva.
- Un pie de página con la información del teatro "TEATRO-UNA", que incluya nombre, dirección, teléfono y correo electrónico.
- Utilice HTML y CSS para el diseño. Puede usar Bootstrap o escribir sus propios estilos personalizados.

### Ejemplo
Puede guiarse por diseños de salas de teatro en línea, pero el objetivo es crear un diseño único y atractivo que represente al teatro "TEATRO-UNA".

### Evaluación
- **Maquetado HTML:** 10 puntos
- **Diseño CSS:** 10 puntos
- **Framework Bootstrap y otro de su elección:** 10 puntos
- **Originalidad y creatividad:** 10 puntos

## Ejercicio 2: Agregar Funcionalidad al Teatro Utilizando JavaScript

### Objetivo
El objetivo de este ejercicio es trabajar con JavaScript para crear un algoritmo que permita seleccionar los asientos del teatro.

### Instrucciones
En el ejercicio anterior diseñamos una sala de teatro que incluye varios asientos. En código JavaScript, utilizaremos una matriz para representar los asientos. Serán objetos y tendrán dos atributos: 
- **id**: Entero.
- **estado**: Booleano (true si está ocupado y false si está libre).

Se pide desarrollar en JavaScript la función `suggest` que recibe como argumento el número de asientos que se desea reservar.
- Si la cantidad de asientos solicitados excede el tamaño máximo de la fila, la función debe devolver un conjunto vacío.
- Si en ninguna fila hay suficientes asientos disponibles juntos, la función debe devolver un conjunto vacío.
- Se comenzará a buscar asientos juntos en la fila más cercana al centro del teatro. Si varias filas pudiesen albergar el número de asientos solicitado, se elegirá siempre la más cercana al centro.

El resultado debe ser un Set con los ids de los asientos pre-seleccionados.

### Evaluación
- **Cambio de color de los asientos seleccionados:** 10 puntos
- **Funcionalidad de acuerdo con los requerimientos:** 30 puntos
