# Retroalimentación — Taller evaluativo 01

**Estudiante:** Uber Herley Chaverra Silva · **Taller:** Taller evaluativo 01 — Python y estructuras de datos
**Fecha límite:** 2026-10-06 23:59 · **Versión revisada:** commit `f34ddd2`

¡Muy buen trabajo! Su taller es casi perfecto.

## Nota

| Criterio | Puntos |
|---|---|
| Variables, tipos y operadores (Ej. 1 a 4) | 20 / 20 |
| Condicionales y clasificación (Ej. 5) | 15 / 15 |
| Bucles, acumuladores y control de flujo (Ej. 6 a 8) | 30 / 30 |
| Estructuras de datos nativas (Ej. 9) | 15 / 15 |
| Ejecución sin errores | 10 / 10 |
| Documentación en celdas de texto | 5 / 5 |
| Entrega correcta | 2 / 5 |
| **Total** | **97 / 100** |
| **Nota (0–5)** | **4.85** |

Este taller aporta **14.6 %** de los 15 % del momento evaluativo.

## 1. Variables, tipos y operadores (20 / 20)
**Lo que hizo bien:**
- Las siete variables del Ejercicio 1 tienen el tipo exacto y los verificó con `type()`.
- La conversión y los tres errores del Ejercicio 2 salen de operadores, no de valores escritos a mano.
- El Ejercicio 3 usa solo `//` y `%`; el Ejercicio 4 usa `and` y `not` sin ningún `if`.

## 2. Condicionales y clasificación (15 / 15)
**Lo que hizo bien:**
- La cadena `if` / `elif` / `else` está ordenada de menor a mayor y clasifica la lectura de 41.8 como "Dañina para grupos sensibles".
- Ninguna concentración queda sin categoría ni en dos a la vez.

## 3. Bucles, acumuladores y control de flujo (30 / 30)
**Lo que hizo bien:**
- Ejercicio 6: descarta los dos -999.0 con `continue` antes de acumular; obtiene 10 lecturas válidas y promedio 22.55.
- Ejercicio 7: máximo 58.3, mínimo 7.5 y desviación con dos recorridos, sin `max()`, `min()` ni `sum()`.
- Ejercicio 8: el `while` actualiza la concentración dentro del bloque y termina (10 horas).

## 4. Estructuras de datos nativas (15 / 15)
**Lo que hizo bien:**
- Accede a cada dato por su clave, desempaqueta las coordenadas en `latitud` y `longitud`, y usa `get` con "no disponible" sin errores.

## 5. Ejecución sin errores (10 / 10)
**Lo que hizo bien:**
- El notebook corre completo sin errores y la celda de verificación imprime el mensaje final.

## 6. Documentación en celdas de texto (5 / 5)
**Lo que hizo bien:**
- Cada ejercicio tiene su celda de texto previa y los nombres de variables son claros y en `snake_case`.

## 7. Entrega correcta (2 / 5)
**Lo que puede mejorar:**
- No siguió la convención de entrega: el archivo se llama `Copia_de_taller_evaluativo_01_calidad_del_aire.ipynb` (quedó así al guardar desde Colab) y debía llamarse exactamente `taller-evaluativo-01-calidad-del-aire.ipynb`.
- Sí está en la carpeta `ejercicios/` y en `main`, y llegó antes del plazo.

## ¿El notebook funciona?
Sí. Corre completo de principio a fin sin errores, la celda de verificación imprime "Verificación completada sin errores." y los resultados coinciden con los esperados.

## Para el próximo taller
- Renombre el archivo con el nombre exacto que indica la guía antes de subirlo (quite el "Copia_de_").
- Si guarda desde Colab, revise el nombre del archivo en GitHub después de subirlo.
- Use nombres distintos para variables de ejercicios diferentes (por ejemplo, `lectura` y `latitud` se reutilizan en ejercicios posteriores).
- Siga ejecutando "Reiniciar y ejecutar todas" antes de entregar, como lo hizo aquí.
