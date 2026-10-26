# Retroalimentación — Taller evaluativo 03 (NumPy)

**Estudiante:** Uber Herley Chaverra Silva · **Taller:** Taller evaluativo 03 — NumPy
**Fecha límite:** 2026-10-26 23:59 · **Versión revisada:** commit `9fb380c`

¡Muy buen trabajo! Casi todo el taller está correcto y bien explicado.

## Nota

| Criterio | Puntos |
|---|---|
| Creación y atributos de arreglos (Ej. 1) | 10 / 10 |
| Indexación y slicing (Ej. 2) | 10 / 10 |
| Máscaras booleanas (Ej. 3) | 15 / 15 |
| Vectorización y broadcasting (Ej. 4) | 15 / 15 |
| Estadística por eje y funciones universales (Ej. 5 y 6) | 20 / 20 |
| Integración (Ej. 7) | 7 / 10 |
| Ejecución sin errores | 10 / 10 |
| Documentación | 5 / 5 |
| Entrega correcta | 2 / 5 |
| **Total** | **94 / 100** |
| **Nota (0–5)** | **4.70** |

Este taller aporta **14.1 %** de los 15 % del momento evaluativo.

## 1. Creación y atributos de arreglos (10 / 10)
**Lo que hizo bien:**
- Creó `lecturas_crudas` con `np.array` y una lista de listas, y leyó forma, dimensiones, tamaño y tipo desde sus atributos.
- `dias`, `pendientes` e `interceptos` son correctos.

## 2. Indexación y slicing (10 / 10)
**Lo que hizo bien:**
- Cada resultado sale de una sola expresión, con el índice negativo donde se pedía.
- `bloque` tiene la forma `(3, 4)` correcta.

## 3. Máscaras booleanas (15 / 15)
**Lo que hizo bien:**
- `es_util` une las dos comparaciones con `&` y paréntesis.
- Quedan 5 lecturas útiles, 2 faltantes y promedio 27.0.

## 4. Vectorización y broadcasting (15 / 15)
**Lo que hizo bien:**
- Convirtió pendientes e interceptos en columnas `(5, 1)` y calibró todo sin bucles.
- La explicación del error entre `(5, 7)` y `(5,)` es clara, y el promedio de SBC-A es 31.9.

## 5. Estadística por eje y funciones universales (20 / 20)
**Lo que hizo bien:**
- Los promedios por sensor y por día, los máximos y la media sobre el límite son correctos.
- Usó `np.maximum`, `np.abs` y `np.round`, y `en_alerta` es una copia con máscara que deja 8 celdas y no altera `calibradas`.

## 6. Integración (7 / 10)
**Lo que hizo bien:**
- Los cuatro conteos (9, 18, 7 y 1) suman 35 y el día pico es 5.

**Lo que puede mejorar:**
- El taller pedía imprimir exactamente dos líneas: `Lecturas por categoría: Buena=9, Moderada=18, Dañina para grupos sensibles=7, Dañina para la salud=1` y `Día más contaminado: 5 con 43.0 ug/m3`. Usted imprimió un informe con varias líneas y otro formato, así que el texto no coincide.

**Cómo corregirlo:**
- En la celda final borre el informe de varias líneas e imprima solo dos líneas, copiadas tal cual del enunciado: primero `Lecturas por categoría: ...` con los cuatro conteos (9, 18, 7 y 1) y luego `Día más contaminado: 5 con 43.0 ug/m3`. Use sus variables para los números, pero deje igual las palabras, los signos y los espacios.

## 7. Ejecución sin errores (10 / 10)
**Lo que hizo bien:** el notebook corre completo sin errores.

## 8. Documentación (5 / 5)
**Lo que hizo bien:** cada ejercicio tiene su celda de texto y los nombres siguen `snake_case`.

## 9. Entrega correcta (2 / 5)
**Lo que hizo bien:** el notebook está en la carpeta `ejercicios/` y se ve en GitHub antes del plazo.

**Lo que puede mejorar:**
- No siguió la estructura acordada: el archivo debe llamarse exactamente `taller-evaluativo-03-numpy.ipynb` (con guiones) y el suyo se llama `taller_evaluativo_03_numpy.ipynb` (con guiones bajos).

**Cómo corregirlo:**
- Cambie el nombre del archivo a `ejercicios/taller-evaluativo-03-numpy.ipynb` (guiones en lugar de guiones bajos), manténgalo en la carpeta `ejercicios/` de la rama `main` y súbalo de nuevo a GitHub, de modo que no quede la versión con el nombre anterior.

## ¿El notebook funciona?
Sí. Corre completo sin errores, la celda de verificación imprime "Verificación completada sin errores." y los resultados coinciden con los esperados.

## Para el próximo taller
- Copie el nombre exacto del archivo que pide la guía y revise en GitHub que quedó con ese nombre.
- Cuando se pida un texto de salida exacto, cópielo carácter por carácter.
- Siga con el hábito de explicar cada ejercicio antes del código.
