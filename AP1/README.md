# AP1: Depuración de programas en JavaScript

## Qué tienes que hacer

Esta carpeta contiene tres páginas HTML con código JavaScript que contiene errores:

| Fichero | Tema |
|---------|------|
| `ejercicio1_fibonacci.html` | Serie de Fibonacci |
| `ejercicio2_recorrer_array.html` | Recorrer arrays |
| `ejercicio3_informe_notas.html` | Funciones y cálculo de notas |

En la cabecera de cada fichero tienes el **resultado esperado**. Tu trabajo es:

1. Ejecutar el programa y ver qué falla.
2. Localizar los errores usando el depurador (breakpoints, Step over/into, Watch) y `console.log`.
3. Corregirlos hasta obtener el resultado esperado.
4. Anotar, como comentario dentro del `<script>`, cada error encontrado: **línea, tipo** (sintaxis / ejecución / lógica) **y cómo lo has corregido**.

## Cómo ejecutarlos

1. Abre el fichero `.html` en el navegador (doble clic, o clic derecho → *Abrir con* → Chrome/Firefox).
2. Abre las DevTools con **F12** y ve a la pestaña **Consola**: ahí aparecen los resultados y los errores.
3. Para depurar paso a paso, usa la pestaña **Depurador** (Firefox) o **Sources** (Chrome): pon *breakpoints*, usa *Step over / Step into* y el panel *Watch*.
4. Después de editar el código, guarda el fichero y recarga la página (**F5**).

## Entrega

Un commit por ejercicio, con mensajes que empiecen por `AP1:`

```bash
git add AP1/ejercicio1_fibonacci.html
git commit -m "AP1: corrijo ejercicio 1 (fibonacci)"
```

## Criterios de evaluación

- Los programas muestran el resultado esperado.
- Has identificado y clasificado correctamente cada error.
- Has usado Git correctamente: commits separados y mensajes descriptivos.

## Consejos

- Cambia una cosa cada vez y vuelve a ejecutar.
- Si un error no muestra mensaje, mira los valores de las variables paso a paso.
- Lee el mensaje de error completo: casi siempre indica la línea del problema.
