# Sistema_Sala_de_Emergencias_con_Montículos
## Descripción del Proyecto
Este repositorio contiene un sistema diseñado para administrar y mejorar la eficiencia en la atención de pacientes en una sala de emergencias hospitalaria. Utilizando la estructura de datos de montículos (heaps), el sistema clasifica a los pacientes según la urgencia de su condición y el tiempo de espera, para garantizar una respuesta médica rápida y adecuada.

## Características Principales:
Clases y Estructuras de Datos: Implementación de las clases Paciente y SalaEmergencias. Cada Paciente tiene atributos como nombre, nivel_urgencia y horas_espera. La SalaEmergencias maneja dos montículos, uno máximo y uno mínimo, para organizar la atención basada en la prioridad.
Montículo Máximo: Se usa para priorizar a los pacientes con el nivel de urgencia más alto, permitiendo una rápida identificación y atención del caso más crítico.
Montículo Mínimo: Se utiliza para identificar a los pacientes que han esperado demasiado tiempo, dando la posibilidad de atender a aquellos cuya espera ha excedido las horas establecidas.
Simulación y Atención: Simulación del flujo de pacientes con variados niveles de urgencia y tiempos de espera. Incorporación de una lógica de atención que sigue reglas específicas basadas en la urgencia y el tiempo de espera.
Generación de Reportes: Capacidad de generar un reporte post-simulación que muestra el orden de atención de los pacientes y el tiempo que han esperado.
## Tareas Desarrolladas:
Implementación de Clases: Código fuente para la definición de las clases y sus métodos correspondientes.
Simulación de Pacientes: Un script para generar y añadir pacientes aleatorios a la SalaEmergencias.
Lógica de Atención: Un algoritmo que decide qué paciente atender a continuación, basándose en las reglas establecidas.
Reporte de Atención: Una función para crear y mostrar un reporte de los pacientes atendidos, incluyendo detalles de su urgencia y tiempo de espera.
## Cómo Contribuir:
Los colaboradores pueden ayudar a mejorar el sistema de las siguientes maneras:

Optimización de Algoritmos: Mejorar la eficiencia de los algoritmos de gestión de montículos.
Interfaz de Usuario: Desarrollar una interfaz gráfica para facilitar la interacción con el sistema.
Expansión de Funcionalidades: Agregar características adicionales, como la integración de datos en tiempo real o la adaptación para múltiples salas de emergencia.
Pruebas y Validación: Crear casos de prueba adicionales para garantizar la robustez del sistema.
## Instrucciones de Uso:
Para ejecutar la simulación y utilizar el sistema, siga las instrucciones detalladas en el archivo README.md.

Este proyecto es una herramienta crucial para profesionales de la salud que buscan mejorar la respuesta en situaciones de emergencia, asegurando que cada paciente reciba la atención necesaria de manera oportuna y eficiente.
