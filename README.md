# Entornos de Desarrollo · 1º DAW

IES La Florida (Catarroja)

Este repositorio contiene las prácticas del módulo. Cada práctica está en su propia carpeta (`AP1`, `AP2`...) con su propio `README.md` donde se explica qué hay que hacer.

| Carpeta | Práctica |
|---------|----------|
| `AP1` | Depuración de programas en JavaScript |

## Cómo trabajar

1. Haz **fork** de este repositorio (botón *Fork*, arriba a la derecha). Solo lo haces una vez.
2. Clona **tu fork** (no el original):
   ```bash
   git clone https://github.com/TU_USUARIO/NOMBRE_REPO.git
   cd NOMBRE_REPO
   ```
3. Trabaja dentro de la carpeta de la práctica. Haz **un commit por ejercicio**, empezando el mensaje por el código de la práctica:
   ```bash
   git add AP1/ejercicio1_fibonacci.html
   git commit -m "AP1: corrijo ejercicio 1 (fibonacci)"
   ```
4. Sube los cambios:
   ```bash
   git push
   ```
5. **Entrega en el Aula Virtual la URL de tu fork** (o de la carpeta de la práctica) antes de la fecha límite.

## Cuando haya una práctica nueva

Cuando el profesor añada una práctica nueva, tu fork no la recibe automáticamente. Para traerla:

1. En GitHub, entra en tu fork y pulsa **Sync fork → Update branch**.
2. En tu ordenador, actualiza el repositorio local:
   ```bash
   git pull
   ```

Haz esto **antes de empezar** cada práctica nueva para evitar conflictos.