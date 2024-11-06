# Sesión 13: Declaración de Funciones en JavaScript

## Título del Laboratorio
Creación de una Calculadora Básica con Funciones en JavaScript

## Duración
Duración estimada: 2 horas

## Objetivos del Laboratorio
1. Implementar una serie de funciones que realicen operaciones matemáticas básicas.
2. Aplicar el uso de funciones para organizar y simplificar el código.
3. Comprender cómo las funciones pueden retornar valores y recibir múltiples parámetros.

## Materiales Necesarios
- Computadora con acceso a un editor de texto (recomendado: Visual Studio Code o Sublime Text).
- Navegador web para ejecutar el código JavaScript.
- Documentación de referencia de funciones en JavaScript y ejemplos de operaciones matemáticas.

## Documentos de Ayuda
- **Sintaxis Básica de Funciones en JavaScript**: Guía sobre cómo declarar y utilizar funciones.
- **Guía de Operaciones Matemáticas en JavaScript**: Ejemplos de funciones matemáticas.
- **Ejemplos de Código Preescritos**: Fragmentos de código para consulta rápida.

## Estructura del Laboratorio
### Parte 1: Crear Funciones Matemáticas (30 minutos)
1. Implementar funciones en JavaScript para realizar operaciones de:
   - **Suma**
   - **Resta**
   - **Multiplicación**
   - **División**

### Parte 2: Implementar una Calculadora Simple (45 minutos)
1. Crear una función principal llamada `calculadora` que reciba dos números y una operación (como una cadena) como parámetros.
2. La función `calculadora` debe usar las funciones matemáticas creadas en la Parte 1 para realizar la operación solicitada y retornar el resultado.

### Parte 3: Probar y Depurar la Calculadora (30 minutos)
1. Solicitar al usuario que ingrese dos números y una operación mediante `prompt`.
2. Mostrar el resultado en la consola utilizando `console.log`.

### Parte 4: Reflexión y Conclusiones (15 minutos)
1. Discutir cómo las funciones ayudan a organizar el código y facilitan su reutilización.
2. Explorar posibles extensiones de la calculadora para soportar operaciones adicionales.

## Ejercicios Propuestos
1. **Función de Área de un Círculo**: Escribe una función que calcule el área de un círculo dado su radio.
2. **Función de Conversión de Temperatura**: Crea una función para convertir grados Celsius a Fahrenheit.
3. **Función para Verificar Paridad**: Implementa una función que determine si un número es par o impar.

## Buenas Prácticas
- Utilizar nombres de funciones descriptivos para mejorar la claridad del código.
- Mantener las funciones cortas y específicas para facilitar su reutilización y prueba.
- Utilizar comentarios útiles para explicar el propósito de cada función, especialmente en partes complejas del código.

## Resumen
Las funciones en JavaScript son fundamentales para organizar y estructurar el código. La práctica con funciones, como la creación de una calculadora, permite a los desarrolladores aplicar conceptos clave y mejorar sus habilidades de programación.

---

## Ejemplo de Código

Aquí un ejemplo de cómo se puede implementar una función de suma en JavaScript:

```javascript
function sumar(a, b) {
    return a + b;
}

console.log(sumar(5, 3)); // Salida: 8
