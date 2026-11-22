# Sistema de Gestión - Software FJ (Fase 4)

Este repositorio contiene el desarrollo del componente práctico de la Fase 4 del curso de Programación

## Descripción del proyecto
Es un sistema orientado a objetos en Python para gestionar clientes, servicios (reservas de salas, alquiler de equipos y asesorías especializadas) y reservas de la empresa Software FJ. El programa funciona sin bases de datos, administrando los datos en memoria mediante listas y registrando los eventos y errores en un archivo de log (`software_fj.log`) para que la ejecución continúe de forma estable ante fallos.

## Contenido principal
- **Excepciones personalizadas:** Clases de error propias para datos inválidos, servicios no disponibles y fallos en reservas.
- **Clases y herencia:** Clase abstracta `Entidad`, clase `Cliente` con encapsulación y validaciones, clase base `Servicio` y servicios derivados (`ReservaSala`, `AlquilerEquipo`, `AsesoriaEspecializada`).
- **Reservas y gestor:** Clase `Reserva` con confirmación, cancelación, procesamiento de costos y encadenamiento de excepciones, junto con `SistemaFJ` para manejar listas en memoria.
- **Demostración:** Simulación de más de 10 operaciones válidas e inválidas para verificar el manejo de errores y la continuidad del programa.

## Ejecución
Ejecuta el archivo principal con Python para ver los resultados en consola y revisar el historial generado en `software_fj.log`.
