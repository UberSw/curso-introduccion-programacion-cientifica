# Retroalimentación — Taller evaluativo 02

**Estudiante:** Uber Herley Chaverra Silva · **Taller:** Taller evaluativo 02 — Funciones y POO
**Fecha límite:** 2026-10-21 00:00 · **Versión revisada:** commit `f8998c0`

Muy buen trabajo: todos los ejercicios dan los resultados esperados.

## Nota

| Criterio | Puntos |
|---|---|
| Funciones: parámetros, valores por defecto y retorno (Ej. 1 a 3) | 20 / 20 |
| `map`, `filter` y `lambda` (Ej. 4) | 10 / 10 |
| Clases, atributos y métodos (Ej. 5 y 7) | 15 / 15 |
| Encapsulamiento y validación (Ej. 6) | 15 / 15 |
| `__repr__` y `__str__` (Ej. 6 a 8) | 10 / 10 |
| Integración de funciones y clases (Ej. 8) | 10 / 10 |
| Ejecución sin errores | 5 / 10 |
| Documentación | 5 / 5 |
| Entrega correcta | 1 / 5 |
| **Total** | **91 / 100** |
| **Nota (0–5)** | **4.55** |

Este taller aporta **13.7 %** de los 15 % del momento evaluativo.

## 1. Funciones: parámetros, valores por defecto y retorno (20 / 20)
**Lo que hizo bien:**
- `calibrar_lectura` tiene los valores por defecto en la firma y usa `return`.
- `es_lectura_valida` rechaza -999.0 y 600.0, y acepta 25.0 y 0.0.
- `promedio_valido` reutiliza `es_lectura_valida`, da 27.0 y devuelve `None` si no hay lecturas útiles. No usa variables globales.

## 2. `map`, `filter` y `lambda` (10 / 10)
**Lo que hizo bien:**
- Obtuvo las 5 lecturas calibradas (de 11.5 a 61.9) y las 2 excedencias, sin bucles ni comprensiones.

## 3. Clases, atributos y métodos (15 / 15)
**Lo que hizo bien:**
- `Lectura` guarda sus tres datos con valores por defecto y convierte bien los mg/m3 (25.2).
- `Estacion` guarda objetos `Lectura` y `valores()` usa `a_microgramos()`; los ocho valores coinciden con `lecturas_sbc_a`.

## 4. Encapsulamiento y validación (15 / 15)
**Lo que hizo bien:**
- `Sensor` lanza `ValueError` con código vacío o pendiente menor o igual a cero, antes de guardar nada.
- Usa `_pendiente` e `_intercepto`, y `calibrar` reutiliza `calibrar_lectura`.
- No dejó celdas de prueba que fallen.

## 5. `__repr__` y `__str__` (10 / 10)
**Lo que hizo bien:**
- Los textos de `Sensor`, `Estacion` e `InformeEstacion` coinciden exactamente con lo pedido.

## 6. Integración de funciones y clases (10 / 10)
**Lo que hizo bien:**
- `InformeEstacion` da 31.9 y "Moderada" reutilizando las funciones y el método `calibrar`.
- `categoria_pm25` usa una sola cadena `if / elif / else` con las cuatro categorías.
- Resolvió también el reto opcional (`excedencias`, da 2).

## 7. Ejecución sin errores (5 / 10)
**Lo que hizo bien:**
- El notebook corre completo sin ningún error.

**Lo que puede mejorar:**
- La celda de verificación final quedó incompleta: le faltan la última comprobación (el texto de `str(informe)`) y la línea que imprime "Verificación completada sin errores.". Por eso el mensaje final nunca aparece. Debía copiarse completa y sin modificar.

## 8. Documentación (5 / 5)
**Lo que hizo bien:**
- Cada ejercicio tiene su celda de texto previa y todas las funciones, clases y métodos tienen docstring de una línea. Los nombres siguen las convenciones.

## 9. Entrega correcta (1 / 5)
**Lo que puede mejorar:**
- No siguió la estructura acordada: el nombre del archivo debe ser exactamente `taller-evaluativo-02-funciones-y-poo.ipynb` (con guiones), y usted subió `taller_evaluativo_02_funciones_y_poo.ipynb` (con guiones bajos).
- Además quedó una copia duplicada en la raíz del repositorio, con un nombre extraño que mezcla `ejercicios\` con el nombre del archivo. Esto suele pasar al guardar desde Colab con una ruta mal escrita.

## ¿El notebook funciona?
Sí, corre completo sin errores y todos los resultados coinciden con los esperados. La celda de verificación no llega a imprimir el mensaje final porque está incompleta.

## Para el próximo taller
- Copie la celda de verificación completa, hasta la última línea, y no la modifique.
- Use el nombre exacto del archivo que indica la guía, con guiones.
- Al guardar en GitHub desde Colab, escriba la ruta `ejercicios/` con barra normal para que no se cree un archivo duplicado en la raíz.
- Revise el repositorio en GitHub después de guardar para confirmar que solo hay un archivo, en el lugar correcto.
