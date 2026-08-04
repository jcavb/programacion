# Guía para Contribuir

## Quién puede contribuir

Cualquier estudiante o profesor puede proponer mejoras siguiendo el flujo de trabajo establecido.

## Qué tipo de cambios se pueden proponer

- Corrección de errores.
- Mejoras en la redacción.
- Incorporación de nuevas reglas o ejemplos.
- Actualización de información desactualizada.

## Cómo proponer una nueva regla

1. Lee primero el archivo que quieres modificar.
2. Crea una nueva rama con un nombre claro.
3. Realiza el cambio en formato Markdown.
4. Escribe un commit breve explicando qué modificaste.
5. Crea un Pull request.
6. Espera la revisión del profesor o de estudiantes revisores.

## Cómo mejorar una regla existente

Propón cambios que hagan la regla más clara, precisa y fácil de comprender, sin alterar su propósito original.

## Cómo crear un fork


## Cómo crear una rama

Ejecuta el siguiente comando en Git Bash:

```bash
git checkout -b <nombre-de-la-rama>
```

**Ejemplo:**

```bash
git checkout -b agregar-guia-git
```

Usa un nombre descriptivo relacionado con el cambio que realizaras. Las ramas permiten trabajar en cambios sin modificar directamente la rama principal.

## Cómo hacer un commit

Agrega el archivo modificado y crea un commit con un mensaje descriptivo.

```bash
git add <nombre-del-archivo.md>
git commit -m "<descripción breve del cambio>"
```

> **Importante:** Las comillas (`" "`) deben escribirse en el comando `git commit -m` para encerrar el mensaje del commit. En `git add` solo son necesarias si el nombre del archivo o carpeta contiene espacios.

**Ejemplos:**

```bash
git add README.md
git commit -m "Corrección errores ortográficos en README"
```

## Cómo enviar un Pull request

1. Sube la rama al repositorio remoto.
2. Abre tu repositorio en GitHub.
3. Haz clic en **Compare & Pull request**.
4. Describe los cambios y crea el Pull Request.

## Cómo se revisan los cambios

El profesor o los estudiantes revisores verificarán que el cambio sea correcto y coherente. Luego podrán aprobarlo, solicitar modificaciones o rechazarlo.