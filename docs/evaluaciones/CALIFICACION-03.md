# Retroalimentación — Taller evaluativo 03 (NumPy)

**Estudiante:** Esteban Mesa Gomez · **Taller:** Taller evaluativo 03 — NumPy
**Fecha límite:** 2026-10-30 23:59 · **Versión revisada:** commit `54abbd5`

Muy buen trabajo: todos los ejercicios dan los resultados esperados.

## Nota

| Criterio | Puntos |
|---|---|
| Creación y atributos de arreglos (Ej. 1) | 10 / 10 |
| Indexación y slicing (Ej. 2) | 10 / 10 |
| Máscaras booleanas (Ej. 3) | 15 / 15 |
| Vectorización y broadcasting (Ej. 4) | 15 / 15 |
| Estadística por eje y funciones universales (Ej. 5 y 6) | 20 / 20 |
| Integración (Ej. 7) | 10 / 10 |
| Ejecución sin errores | 10 / 10 |
| Documentación | 4 / 5 |
| Entrega correcta | 1 / 5 |
| **Total** | **95 / 100** |
| **Nota (0–5)** | **4.75** |

Este taller aporta **14.3 %** de los 15 % del momento evaluativo.

## 1. Creación y atributos de arreglos (10 / 10)
**Lo que hizo bien:**
- `lecturas_crudas` se crea con `np.array` y los atributos se leen del propio arreglo.
- `dias`, `pendientes` e `interceptos` son correctos.

## 2. Indexación y slicing (10 / 10)
**Lo que hizo bien:**
- Cada resultado sale de una sola expresión, con el índice negativo donde se pedía.
- `bloque` tiene la forma (3, 4) y los valores correctos.

## 3. Máscaras booleanas (15 / 15)
**Lo que hizo bien:**
- `es_util` une dos comparaciones con `&` y entre paréntesis.
- Quedan 5 lecturas útiles, 2 faltantes y el promedio es 27.0, sin bucles.

## 4. Vectorización y broadcasting (15 / 15)
**Lo que hizo bien:**
- Convirtió las pendientes e interceptos en columnas (5, 1) y `calibradas` quedó correcta.
- La celda de texto explica con claridad por qué la multiplicación directa falla.
- `promedio_calibrado_sbc_a` da 31.9.

## 5. Estadística por eje y funciones universales (20 / 20)
**Lo que hizo bien:**
- Los promedios por sensor y por día, el máximo y la media sobre el límite son correctos.
- Usó `np.maximum`, `np.abs` y `np.round`, y `en_alerta` se hizo sobre una copia dejando 8 celdas en alerta y `calibradas` intacta.

## 6. Integración (10 / 10)
**Lo que hizo bien:**
- Los conteos (9, 18, 7 y 1) suman 35 y ninguna lectura queda en dos categorías.
- `dia_pico` es 5 y las dos líneas impresas coinciden con lo pedido.

## 7. Ejecución sin errores (10 / 10)
**Lo que hizo bien:**
- El notebook corre completo sin errores y la verificación imprime el mensaje final.

## 8. Documentación (4 / 5)
**Lo que hizo bien:**
- Cada ejercicio tiene su celda de texto y los nombres siguen `snake_case`.

**Lo que puede mejorar:**
- La celda inicial solo tiene el título: faltan su nombre completo y la fecha.

**Cómo corregirlo:**
- Agregue a la primera celda de texto su nombre completo y la fecha de entrega.

## 9. Entrega correcta (1 / 5)
**Lo que hizo bien:**
- El notebook se subió a GitHub antes del plazo y se puede ver en el repositorio.

**Lo que puede mejorar:**
- No siguió la estructura acordada: el notebook está en la raíz del repositorio y no en la carpeta `ejercicios/`.
- El nombre del archivo es `taller_evaluativo_03_numpy.ipynb`, con guiones bajos, y debe ser `taller-evaluativo-03-numpy.ipynb`.

**Cómo corregirlo:**
- Cree la carpeta `ejercicios/` si no existe y mueva allí el notebook.
- Cambie el nombre del archivo a `taller-evaluativo-03-numpy.ipynb`, con guiones medios. Lo más simple es volver a guardarlo desde Colab con «Archivo → Guardar una copia en GitHub», escogiendo la carpeta `ejercicios/` y ese nombre.

## ¿El notebook funciona?
Sí. Corre completo sin errores, la celda de verificación imprime «Verificación completada sin errores.» y todos los resultados coinciden con los esperados.

## Para el próximo taller
- Guarde el notebook en `ejercicios/` con el nombre exacto que pide la guía.
- Ponga en la primera celda el título, su nombre completo y la fecha.
- Antes de entregar, revise en GitHub que el archivo esté en la carpeta correcta.
- Siga ejecutando «Reiniciar y ejecutar todas» antes de subir, como lo hizo aquí.
