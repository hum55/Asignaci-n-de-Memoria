🧠 Simulador de Asignación de Memoria — Best Fit vs Worst Fit
📖 Introducción (Descripción general del simulador)

Este simulador permite visualizar de manera interactiva cómo funcionan los algoritmos de asignación de memoria Best Fit y Worst Fit, dos estrategias clásicas utilizadas en la gestión de memoria de los sistemas operativos.

A través de una interfaz gráfica, el usuario puede definir bloques de memoria y procesos, ejecutar la simulación y observar cómo cada algoritmo asigna los procesos, además de analizar la fragmentación interna generada y comparar cuál ofrece un mejor aprovechamiento de la memoria.

El objetivo es facilitar la comprensión práctica de estos algoritmos mediante una representación visual clara y dinámica.



🧭 Instrucciones
✅ ¿Qué debe hacer el usuario?

Abrir el archivo index.html en el navegador.

Agregar bloques de memoria indicando su tamaño en KB.

Agregar procesos indicando su tamaño y nombre.

Presionar el botón "Ejecutar Simulación".

👀 ¿Qué va a observar?

Dos paneles de simulación:

Best Fit

Worst Fit

Representación gráfica de cada bloque de memoria.

El proceso asignado a cada bloque.

El porcentaje utilizado del bloque.

Indicadores visuales de fragmentación.

📊 ¿Qué significan los resultados?

El sistema mostrará automáticamente:

Fragmentación interna total generada por cada algoritmo.

Cantidad de procesos asignados.

Un resultado comparativo indicando qué algoritmo tuvo mejor desempeño.

⚙️ Explicación de los algoritmos


🔹 Best Fit

El algoritmo Best Fit busca el bloque de memoria más pequeño posible en el que quepa el proceso.
Su objetivo es dejar el menor espacio libre sobrante, reduciendo la fragmentación interna.

Ventaja: Uso más preciso de la memoria.
Desventaja: Puede generar muchos espacios pequeños difíciles de reutilizar.

🔸 Worst Fit

El algoritmo Worst Fit selecciona el bloque de memoria más grande disponible para asignar el proceso.

Ventaja: Deja espacios grandes que pueden ser reutilizados por otros procesos.
Desventaja: Puede generar mayor fragmentación interna.


🧠 Reflexión

Este simulador permite comprender que la eficiencia en la asignación de memoria no depende únicamente de asignar procesos, sino de cómo se distribuye el espacio restante. Visualmente se aprecia que Best Fit tiende a aprovechar mejor la memoria disponible, mientras que Worst Fit prioriza dejar bloques grandes libres. La comparación directa facilita entender por qué la fragmentación interna es un factor crítico en la gestión de memoria de los sistemas operativos.

📚 Referencias

Operating System Concepts — Abraham Silberschatz, Peter B. Galvin, Greg Gagne.

Modern Operating Systems — Andrew S. Tanenbaum.

Operating Systems: Internals and Design Principles — William Stallings.

🤖 Clausula de ia


Yo, HUMBERTO RAMIREZ GRUINTAL, declaro que NO he utilizado herramientas de Inteligencia Artificial para la elaboración de este trabajo académico. Afirmo que cuento con evidencias físicas y/o digitales que demuestran mi autoría, incluyendo pero no limitándose a: documentos manuscritos, materiales impresos con anotaciones o subrayado, historial de versiones de documentos electrónicos, o commits en repositorios de código.

Reconozco y acepto que el profesor se reserva el derecho de solicitar dichas evidencias en cualquier momento, especialmente cuando existan sospechas o se detecten conductas que atenten contra la integridad académica, tales como plagio o uso no reportado de herramientas de IA.
