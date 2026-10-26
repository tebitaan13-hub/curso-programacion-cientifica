# Retroalimentación — Taller evaluativo 01

**Estudiante:** Esteban Mesa Gómez · **Taller:** Taller evaluativo 01 — Python y estructuras de datos
**Fecha límite:** 2026-10-26 23:59 · **Versión revisada:** commit `2179be6`

Excelente trabajo: todo el código está bien resuelto. Los puntos que se perdieron son de organización de la entrega.

## Nota

| Criterio | Puntos |
|---|---|
| Variables, tipos y operadores (Ej. 1 a 4) | 20 / 20 |
| Condicionales y clasificación (Ej. 5) | 14 / 15 |
| Bucles, acumuladores y control de flujo (Ej. 6 a 8) | 30 / 30 |
| Estructuras de datos nativas (Ej. 9) | 15 / 15 |
| Ejecución sin errores | 10 / 10 |
| Documentación en celdas de texto | 3 / 5 |
| Entrega correcta | 1 / 5 |
| **Total** | **93 / 100** |
| **Nota (0–5)** | **4.65** |

Este taller aporta **14.0 %** de los 15 % del momento evaluativo.

## 1. Variables, tipos y operadores (20 / 20)
**Lo que hizo bien:**
- Las siete variables tienen el tipo pedido y los verificó con `type()`.
- La conversión y los tres errores del Ejercicio 2 salen de operaciones, no de números escritos a mano.
- El Ejercicio 3 usa solo `//` y `%` (25 horas, 5 lecturas sobrantes, 1 día y 1 hora).
- El Ejercicio 4 usa `and` y `not`, sin `if`, y da los booleanos correctos.

## 2. Condicionales y clasificación (14 / 15)
**Lo que hizo bien:**
- La cadena `if` / `elif` / `else` clasifica bien las cuatro categorías y da "Dañina para grupos sensibles" para 41.8.

**Lo que puede mejorar:**
- Agregó una quinta categoría, "Lectura no válida", que no está en la escala oficial. La guía pedía solo las cuatro categorías de la tabla.

## 3. Bucles, acumuladores y control de flujo (30 / 30)
**Lo que hizo bien:**
- El Ejercicio 6 descarta los dos `-999.0` con `continue` antes de acumular: 10 válidas y promedio 22.55.
- El Ejercicio 7 da máximo 58.3, mínimo 7.5 y desviación con dos recorridos, sin `max()`, `min()` ni `sum()`.
- El Ejercicio 8 usa `while`, actualiza la concentración dentro del bloque y termina (10 horas).

## 4. Estructuras de datos nativas (15 / 15)
**Lo que hizo bien:**
- Accede a los datos por clave, desempaqueta las coordenadas en `latitud` y `longitud`, y usa `get` con "no disponible" sin errores.

## 5. Ejecución sin errores (10 / 10)
**Lo que hizo bien:**
- El notebook corre completo sin errores y la celda final imprime "Verificación completada sin errores."

## 6. Documentación en celdas de texto (3 / 5)
**Lo que hizo bien:**
- Los nombres de variables son claros y en `snake_case`.
- Hay una celda de texto antes de cada ejercicio.

**Lo que puede mejorar:**
- Las celdas de texto son solo títulos; la guía pedía que expliquen qué hace cada ejercicio.
- La primera celda no trae su nombre completo ni la fecha.

## 7. Entrega correcta (1 / 5)
**Lo que puede mejorar:**
- No siguió la estructura acordada: el notebook debe estar en la carpeta `ejercicios/` con el nombre exacto `taller-evaluativo-01-calidad-del-aire.ipynb`.
- Su archivo está en la raíz del repositorio y se llama "Taller evaluativo 01 — Python y estructuras de datosipynb": le falta el punto antes de `ipynb`, por lo que no se reconoce como notebook y GitHub no lo muestra como tal.
- Sí lo subió antes del plazo, y el contenido se pudo revisar.

## ¿El notebook funciona?
Sí. Corre de principio a fin sin errores, la celda de verificación da el mensaje final y todos los resultados coinciden con los valores esperados.

## Para el próximo taller
- Cree la carpeta `ejercicios/` y guarde allí el notebook con el nombre exacto indicado, terminado en `.ipynb`.
- Revise en GitHub que el notebook se abra como notebook antes del plazo.
- En cada celda de texto, explique en una o dos frases qué hace el ejercicio.
- Ponga en la primera celda el título, su nombre completo y la fecha.
- Use solo las categorías que pide la guía cuando clasifique.
