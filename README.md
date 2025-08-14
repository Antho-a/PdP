## Ejercicio 1: Lenguaje utilizado: "C"

### Reglas del lenguaje
- Cada instrucción del código debe finalizar con un `;`.
- El código principal debe estar dentro de la función llamada `main` que retorna vacío.
- La estructura de funciones o declaraciones debe estar encerrada entre `{ }`.
- Existen palabras reservadas que no pueden ser utilizadas como nombres de variables (por ejemplo: `if`, `while`, `int`, etc).

### Características particulares del lenguaje
- Manejo de espacios de memoria a través de punteros y posibilidad de seleccionar con qué registros trabajar.
- Lenguaje base para aprender otros lenguajes.
- Alto rendimiento y eficiencia: si está programado correctamente, puede ser tan rápido como el lenguaje ensamblador.

### Estilo de programación
- Programación estructurada.

### Problemas que resuelve el lenguaje
- Administración de espacios de memoria.
- Control directo del hardware.
- Creación de sistemas operativos.
"""

# Guardar en un archivo .txt
ruta_salida = "/mnt/data/trabajo_practico_0.txt"
with open(ruta_salida, "w", encoding="utf-8") as f:
    f.write(texto_prolijo)

ruta_salida
