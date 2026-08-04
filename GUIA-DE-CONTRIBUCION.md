# Guía para Contribuir

## Quién puede contribuir

Cualquier estudiante o profesor puede proponer mejoras siguiendo el flujo de trabajo establecido.

## Qué tipo de cambios se pueden proponer

- Corrección de errores.
- Mejoras en la redacción.
- Incorporación de nuevas reglas o ejemplos.
- Actualización de información desactualizada.

## Cómo proponer una nueva regla

1. Crea un **Fork** del repositorio si aún no tienes uno.
2. Clona el **Fork** en tu equipo.
3. Lee primero el archivo que quieres modificar.
4. Crea una nueva rama con un nombre claro.
5. Realiza el cambio en formato Markdown.
6. Escribe un commit breve explicando qué modificaste.
7. Envía un Pull Request.
8. Espera la revisión del profesor o de estudiantes revisores.

## Cómo mejorar una regla existente

Propón cambios que hagan la regla más clara, precisa y fácil de comprender, sin alterar su propósito original.

## Cómo crear un **Fork**

1. Ingresa al repositorio original en GitHub.
2. Haz clic en **Fork**.
3. Selecciona tu cuenta de GitHub.
4. Espera a que GitHub cree una copia del repositorio en tu cuenta.

## Cómo clonar un **Fork**

Antes de clonar el repositorio, ubícate en la carpeta donde deseas guardarlo utilizando el comando `cd`.

```bash
cd <ruta-de-la-carpeta>
```

**Ejemplo:**

```bash
cd Documentos/Proyectos
```

Una vez creado el **Fork**, ábrelo en GitHub, haz clic en el botón **<> Code**, selecciona la opción **HTTPS** y copia la URL del repositorio.

Ejecuta el siguiente comando en Git Bash:

```bash
git clone <URL-del-Fork>
```

**Ejemplo:**

```bash
git clone https://github.com/usuario/programacion.git
```

Luego entra a la carpeta del repositorio:

```bash
cd <nombre-del-repositorio>
```

**Ejemplo:**

```bash
cd programacion
```

## Cómo crear una rama

Ejecuta el siguiente comando en Git Bash:

```bash
git checkout -b <nombre-de-la-rama>
```

**Ejemplo:**

```bash
git checkout -b agregar-guia-git
```

Usa un nombre descriptivo relacionado con el cambio que realizarás. Las ramas permiten trabajar en cambios sin modificar directamente la rama principal.

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

## Cómo enviar un Pull Request

Primero, sube la rama a tu **Fork** ejecutando el siguiente comando. 

```bash
git push origin <nombre-de-la-rama>
```

**Ejemplo:**

```bash
git push origin agregar-guia-git
```

Luego:

1. Abre tu **Fork** en GitHub.
2. Si el envío fue exitoso, aparecerá el botón **Compare & Pull Request** en la página principal de tu **Fork**.
3. Haz clic en **Compare & Pull Request**.
4. Escribe un título y una descripción que expliquen los cambios realizados.
5. Haz clic en **Create Pull Request** para enviar tu propuesta de cambios al repositorio original.

## Cómo actualizar un **Fork**

Si el repositorio original recibe cambios, puedes sincronizar tu **Fork** desde GitHub.

1. Abre tu **Fork** en GitHub.
2. Haz clic en **Sync fork**.
3. Selecciona **Update branch** para incorporar los cambios del repositorio original.

## Cómo se revisan los cambios

El profesor o los estudiantes revisores verificarán que el cambio sea correcto y coherente. Luego podrán aprobarlo, solicitar modificaciones o rechazarlo.
