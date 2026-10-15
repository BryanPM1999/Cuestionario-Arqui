# ⚡ Cuestionario de Arquitectura de Computadoras

Aplicación web interactiva y moderna para el estudio y evaluación práctica de **Arquitectura de Computadoras**, compuesta por un banco de **40 preguntas evaluativas** con explicaciones teóricas y retroalimentación inmediata.

🌐 **Demo / Repositorio:** [https://github.com/BryanPM1999/Cuestionario-Arqui](https://github.com/BryanPM1999/Cuestionario-Arqui)

---

## 📚 Temas Evaluados

1. **Jerarquía de Memoria** (Preguntas 1 a 10)
   - Principios rectores (velocidad vs capacidad vs costo por bit).
   - Registros de la CPU, operaciones de la ALU y cúspide jerárquica.
   - Memoria RAM principal y almacenamiento secundario (SSD / HDD).
   - Principios de localidad: **Temporal** (bucles, contadores) y **Espacial** (recorrido de arreglos contiguos).

2. **Rendimiento de Memoria y Relación con la CPU** (Preguntas 11 a 17)
   - Concepto de latencia y penalización por fallo (*miss penalty*).
   - Aciertos (*hits*) y fallos (*misses*) de caché.
   - Cálculo de tasas: $Hit\ Rate$ y $Miss\ Rate$.
   - Fórmula del tiempo promedio de acceso:
     $$\text{Tiempo Promedio} = \text{Tiempo Caché} + (\text{Tasa de Fallos} \times \text{Penalización})$$
   - Relación de niveles L1, L2 y L3 (latencia, cercanía y capacidad).

3. **Medición y Evaluación del Rendimiento de Máquinas** (Preguntas 18 a 28)
   - Métrica **MIPS** (*Millions of Instructions Per Second*) y sus limitaciones frente a arquitecturas CISC vs RISC.
   - Métrica **MFLOPS** (*Million Floating-point Operations Per Second*) en computación científica y cálculo numérico.
   - Concepto de tiempo de referencia (*benchmarks*) y tiempo no estimado (medición empírica en tiempo real).
   - Principios de rigurosidad: reproducibilidad de pruebas, carga de trabajo (*workload*) y evaluación multifactorial.

4. **Memoria Caché: Funcionamiento y Políticas de Reemplazo** (Preguntas 29 a 34)
   - Caché como puente de velocidad entre CPU y DRAM.
   - Tipos de fallos: Fallos forzosos (*Compulsory / Cold Miss*) y fallos por capacidad (*Capacity Miss*).
   - Algoritmo de reemplazo **FIFO** (*First In, First Out*) y resolución paso a paso de secuencias de acceso.

5. **Memoria Virtual y Comparativas** (Preguntas 35 a 40)
   - Objetivo de la memoria virtual: extensión de capacidad sobre almacenamiento secundario (*swap/paging*).
   - Comparación Caché vs Memoria Virtual (velocidad en nanosegundos vs microsegundos/milisegundos, soporte a CPU vs ampliación de RAM).
   - Flujo de resolución ante fallos de jerarquía.

---

## ✨ Características y Funcionalidades

- **🔀 Barajado Dinámico de Opciones:** Las alternativas de respuesta se barajan de forma aleatoria manteniendo siempre la validación precisa de la respuesta correcta.
- **🎯 Filtro por Tema:** Permite estudiar el banco completo de 40 preguntas o filtrar por módulos específicos.
- **🗺️ Mapa / Índice de Preguntas:** Visualiza rápidamente el estado de todas las preguntas (pendientes, aciertos en verde, fallos en rojo) y salta directamente a cualquiera de ellas con la tecla `M`.
- **🌙 Modo Oscuro y Claro:** Interfaz cuidada con paleta cromática moderna y soporte de guardado automático en `localStorage`.
- **🔊 Efectos de Audio Sintetizados:** Sonidos generados mediante *Web Audio API* sin librerías externas pesadas (activable/desactivable en cualquier momento).
- **🔁 Repaso de Falladas:** Al finalizar el cuestionario, puedes seleccionar *“Reintentar solo las falladas”* para reforzar los puntos débiles.
- **⌨️ Atajos de Teclado:**
  - Teclas `1`, `2`, `3`, `4` o `A`, `B`, `C`, `D`: Seleccionar opción.
  - Flecha `→`: Siguiente pregunta.
  - Flecha `←`: Pregunta anterior.
  - Tecla `M`: Abrir / Cerrar índice y mapa de preguntas.
  - Tecla `ESC`: Cerrar modales.
- **🎉 Animación de Celebración:** Efecto de confeti y desglose porcentual por áreas temáticas al completar la prueba.

---

## 🚀 Cómo Ejecutar

No requiere compilación ni dependencias complejas. Basta con abrir el archivo `index.html` en cualquier navegador web moderno:

1. **Directamente en local:**
   - Haz doble clic en el archivo `index.html`.
2. **Con un servidor local ligero:**
   ```bash
   npx serve .
   ```
3. **En GitHub Pages:**
   - Ve a **Settings** > **Pages** en tu repositorio de GitHub.
   - Selecciona la rama `main` y la carpeta `/ (root)`.
   - ¡Tu cuestionario estará disponible en línea en segundos!

---

## 👤 Autor
- **BryanPM1999** - [GitHub](https://github.com/BryanPM1999)
