# Guía de Markdown para GitHub

Esta guía fue creada para que los estudiantes de la Especialidad de Programación aprendan a escribir documentos `.md` usando **Markdown** en GitHub.

Markdown permite escribir texto con formato de manera simple. Se usa mucho en GitHub para crear archivos como `README.md`, guías, documentación, instrucciones de proyectos, bitácoras y manuales.

---

## 1. ¿Qué es un archivo `.md`?

Un archivo `.md` es un archivo de texto escrito con Markdown.

Por ejemplo:

```text
README.md
REGLAS.md
CULTURA.md
GUIA-DE-CONTRIBUCION.md
```

En GitHub, estos archivos se muestran con formato visual: títulos, listas, tablas, enlaces, imágenes, código y más.

---

## 2. Títulos y subtítulos

Para crear títulos se usa el símbolo `#`.

```markdown
# Título principal
## Subtítulo
### Subtítulo más pequeño
#### Nivel 4
##### Nivel 5
###### Nivel 6
```

Resultado:

# Título principal
## Subtítulo
### Subtítulo más pequeño
#### Nivel 4
##### Nivel 5
###### Nivel 6

Recomendación: usa solo un `#` como título principal del documento.

---

## 3. Texto en negrita, cursiva y tachado

```markdown
**Texto en negrita**
*Texto en cursiva*
***Texto en negrita y cursiva***
~~Texto tachado~~
```

Resultado:

**Texto en negrita**

*Texto en cursiva*

***Texto en negrita y cursiva***

~~Texto tachado~~

Ejemplo aplicado:

```markdown
**Importante:** No instalar juegos en los computadores del laboratorio.
```

---

## 4. Párrafos y saltos de línea

Para crear un nuevo párrafo, deja una línea en blanco entre textos.

```markdown
Este es el primer párrafo.

Este es el segundo párrafo.
```

Resultado:

Este es el primer párrafo.

Este es el segundo párrafo.

---

## 5. Listas con viñetas

Se pueden crear listas usando `-`, `*` o `+`.

```markdown
- Respetar a los compañeros.
- Cuidar los computadores.
- Documentar los trabajos.
- Subir avances a GitHub.
```

Resultado:

- Respetar a los compañeros.
- Cuidar los computadores.
- Documentar los trabajos.
- Subir avances a GitHub.

---

## 6. Listas numeradas

```markdown
1. Crear una rama.
2. Modificar el archivo.
3. Guardar los cambios.
4. Hacer commit.
5. Crear un pull request.
```

Resultado:

1. Crear una rama.
2. Modificar el archivo.
3. Guardar los cambios.
4. Hacer commit.
5. Crear un pull request.

---

## 7. Listas con subniveles

Para crear niveles dentro de una lista, usa espacios al inicio.

```markdown
- Laboratorio de programación
  - Cuidar los computadores.
  - Mantener limpio el espacio.
  - Avisar si un equipo falla.
- Trabajo en clases
  - Participar activamente.
  - Preguntar con respeto.
  - Ayudar a otros compañeros.
```

Resultado:

- Laboratorio de programación
  - Cuidar los computadores.
  - Mantener limpio el espacio.
  - Avisar si un equipo falla.
- Trabajo en clases
  - Participar activamente.
  - Preguntar con respeto.
  - Ayudar a otros compañeros.

---

## 8. Casillas de verificación

Muy útiles para tareas, checklist o seguimiento de avances.

```markdown
- [x] Crear repositorio en GitHub.
- [x] Crear archivo README.md.
- [ ] Agregar reglas de la especialidad.
- [ ] Revisar ortografía.
- [ ] Crear pull request.
```

Resultado:

- [x] Crear repositorio en GitHub.
- [x] Crear archivo README.md.
- [ ] Agregar reglas de la especialidad.
- [ ] Revisar ortografía.
- [ ] Crear pull request.

---

## 9. Enlaces

Para crear un enlace se usa este formato:

```markdown
[Texto visible](https://www.github.com)
```

Ejemplo:

```markdown
Visita [GitHub](https://www.github.com) para crear tu repositorio.
```

Resultado:

Visita [GitHub](https://www.github.com) para crear tu repositorio.

---

## 10. Imágenes

Para insertar una imagen se usa un formato parecido al enlace, pero con un signo `!` al inicio.

```markdown
![Texto alternativo](ruta-o-url-de-la-imagen)
```

Ejemplo:

```markdown
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)
```

También puedes usar imágenes guardadas dentro del repositorio:

```markdown
![Diagrama del proyecto](imagenes/diagrama.png)
```

Recomendación: crea una carpeta llamada `imagenes` para guardar imágenes del proyecto.

---

## 11. Líneas divisorias

Para separar secciones puedes usar tres guiones:

```markdown
---
```

Resultado:

---

Úsalas para separar partes importantes del documento, pero no abuses de ellas.

---

## 12. Citas o frases destacadas

Se usa el símbolo `>`.

```markdown
> En programación, equivocarse es parte del aprendizaje.
```

Resultado:

> En programación, equivocarse es parte del aprendizaje.

Ejemplo aplicado:

```markdown
> Antes de decir “no funciona”, intenta explicar qué probaste y qué error apareció.
```

---

## 13. Código en línea

Para destacar comandos, nombres de archivos o palabras técnicas, usa comillas invertidas.

```markdown
El archivo principal del repositorio se llama `README.md`.
```

Resultado:

El archivo principal del repositorio se llama `README.md`.

Más ejemplos:

```markdown
Usa el comando `git status` para revisar los cambios.
La rama principal se llama `main`.
El archivo de reglas puede llamarse `REGLAS.md`.
```

---

## 14. Bloques de código

Para escribir varias líneas de código, usa tres comillas invertidas antes y después del código.

````markdown
```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("Hola, mundo");
    }
}
```
````

Resultado:

```java
public class HolaMundo {
    public static void main(String[] args) {
        System.out.println("Hola, mundo");
    }
}
```

Puedes indicar el lenguaje para que GitHub resalte el código con colores.

Ejemplos:

````markdown
```html
<h1>Hola estudiantes</h1>
<p>Bienvenidos a Programación.</p>
```
````

```html
<h1>Hola estudiantes</h1>
<p>Bienvenidos a Programación.</p>
```

````markdown
```sql
SELECT * FROM estudiantes;
```
````

```sql
SELECT * FROM estudiantes;
```

---

## 15. Tablas

Las tablas sirven para organizar información.

```markdown
| Regla | Descripción | Responsable |
|------|-------------|-------------|
| Cuidar equipos | No dañar ni desconectar componentes | Todo el curso |
| Usar GitHub | Subir avances y documentar cambios | Cada estudiante |
| Respetar compañeros | Trabajar con buena convivencia | Todo el curso |
```

Resultado:

| Regla | Descripción | Responsable |
|------|-------------|-------------|
| Cuidar equipos | No dañar ni desconectar componentes | Todo el curso |
| Usar GitHub | Subir avances y documentar cambios | Cada estudiante |
| Respetar compañeros | Trabajar con buena convivencia | Todo el curso |

---

## 16. Alinear columnas en tablas

Puedes alinear texto usando dos puntos `:`.

```markdown
| Izquierda | Centro | Derecha |
|:---------|:------:|--------:|
| Texto | Texto | Texto |
| 100 | 200 | 300 |
```

Resultado:

| Izquierda | Centro | Derecha |
|:---------|:------:|--------:|
| Texto | Texto | Texto |
| 100 | 200 | 300 |

---

## 17. Escapar caracteres especiales

Si quieres mostrar un símbolo que Markdown normalmente interpreta como formato, puedes usar una barra invertida `\`.

```markdown
\# Esto no será un título
\* Esto no será una lista
```

Resultado:

\# Esto no será un título

\* Esto no será una lista

---

## 18. Emojis en GitHub

GitHub permite usar emojis escribiendo códigos entre dos puntos.

```markdown
:computer:
:rocket:
:warning:
:white_check_mark:
:bulb:
```

Resultado en GitHub:

:computer:  
:rocket:  
:warning:  
:white_check_mark:  
:bulb:

Ejemplo aplicado:

```markdown
## :computer: Reglas del laboratorio

- :white_check_mark: Cuidar los computadores.
- :warning: No instalar software sin autorización.
- :bulb: Avisar si encuentras una falla.
```

---

## 19. Menciones a usuarios

En GitHub puedes mencionar usuarios usando `@`.

```markdown
Gracias a @nombreUsuario por mejorar esta regla.
```

Ejemplo:

```markdown
Revisión realizada por @estudiante1.
```

---

## 20. Referencias a issues y pull requests

En GitHub puedes mencionar un issue o pull request usando `#` y el número.

```markdown
Esta regla fue discutida en el issue #3.
```

Ejemplo:

```markdown
La propuesta sobre uso de inteligencia artificial fue revisada en el pull request #5.
```

---

## 21. Crear un índice con enlaces internos

Puedes crear enlaces a secciones del mismo documento.

```markdown
## Índice

- [Reglas del laboratorio](#reglas-del-laboratorio)
- [Uso de GitHub](#uso-de-github)
- [Cultura de trabajo](#cultura-de-trabajo)

## Reglas del laboratorio

Contenido de la sección.

## Uso de GitHub

Contenido de la sección.

## Cultura de trabajo

Contenido de la sección.
```

En GitHub, los títulos se transforman automáticamente en enlaces internos.

Recomendación: escribe los títulos de forma simple para que los enlaces funcionen mejor.

---

## 22. Alertas o bloques destacados en GitHub

GitHub permite crear bloques destacados usando este formato:

```markdown
> [!NOTE]
> Esta es una información importante.

> [!TIP]
> Este es un consejo útil.

> [!IMPORTANT]
> Esta información es clave.

> [!WARNING]
> Esta es una advertencia.

> [!CAUTION]
> Esto requiere especial cuidado.
```

Ejemplo aplicado:

```markdown
> [!WARNING]
> No instales programas o juegos en los computadores del laboratorio sin autorización.
```

---

## 23. Ocultar contenido desplegable

Puedes crear secciones que se abren y se cierran usando HTML dentro de Markdown.

```markdown
<details>
<summary>Ver ejemplo de regla</summary>

## Regla: Cuidar los computadores

Los computadores son herramientas de trabajo compartidas por todos los estudiantes de la especialidad.

</details>
```

Resultado en GitHub:

<details>
<summary>Ver ejemplo de regla</summary>

## Regla: Cuidar los computadores

Los computadores son herramientas de trabajo compartidas por todos los estudiantes de la especialidad.

</details>

Esto sirve para documentos largos.

---

## 24. Usar HTML básico dentro de Markdown

GitHub permite usar algo de HTML dentro de archivos `.md`.

Ejemplo:

```markdown
<p align="center">
  <strong>Especialidad de Programación</strong>
</p>
```

También se puede centrar una imagen:

```markdown
<p align="center">
  <img src="imagenes/logo.png" width="200">
</p>
```

Recomendación: usa HTML solo cuando Markdown no sea suficiente.

---

## 25. Crear una tabla de contenidos simple

Ejemplo para un documento largo:

```markdown
# Manual de Cultura de Programación

## Índice

1. [Bienvenida](#bienvenida)
2. [Reglas principales](#reglas-principales)
3. [Cultura de trabajo](#cultura-de-trabajo)
4. [Uso de GitHub](#uso-de-github)
5. [Historial](#historial)

## Bienvenida

Texto de bienvenida.

## Reglas principales

Texto de reglas.

## Cultura de trabajo

Texto de cultura.

## Uso de GitHub

Texto sobre GitHub.

## Historial

Texto del historial.
```

---

## 26. Ejemplo de regla bien escrita en Markdown

```markdown
## Regla: Cuidamos los equipos del laboratorio

Los computadores, teclados, mouse, monitores, cables y sillas son herramientas de trabajo de toda la especialidad.

### Qué significa

- No comer ni beber cerca de los equipos.
- No desconectar cables sin autorización.
- No cambiar configuraciones sin motivo técnico.
- Avisar si un equipo presenta fallas.

### Por qué es importante

Porque el laboratorio es un espacio compartido. Si un equipo se daña, afecta el aprendizaje de todos.

### Ejemplo correcto

Un estudiante detecta que un mouse no funciona y avisa al profesor antes de cambiarlo por otro.

### Ejemplo incorrecto

Un estudiante desconecta cables de otro computador sin avisar.
```

---

## 27. Ejemplo de bitácora técnica en Markdown

```markdown
# Bitácora Técnica

## Datos generales

- **Nombre del estudiante:** Juan Pérez
- **Curso:** 4° medio Programación
- **Fecha:** 15 de abril de 2026
- **Equipo revisado:** PC-12

## Actividad realizada

Se realizó mantenimiento preventivo al computador del laboratorio.

## Acciones realizadas

- Se apagó correctamente el equipo.
- Se desconectaron los cables.
- Se abrió el gabinete.
- Se retiró polvo de ventiladores y componentes.
- Se revisaron conexiones internas.
- Se cerró el gabinete y se probó el encendido.

## Evidencia

![Evidencia del mantenimiento](imagenes/mantenimiento-pc12.jpg)

## Observaciones

El equipo encendió correctamente después del mantenimiento.
```

---

## 28. Ejemplo de README para un proyecto de programación

```markdown
# Sistema de Registro de Estudiantes

## Descripción

Este proyecto permite registrar, listar, actualizar y eliminar estudiantes usando Java, JSP, Servlets y MySQL.

## Tecnologías utilizadas

- Java
- JSP
- Servlets
- MySQL
- HTML
- CSS
- GitHub

## Funcionalidades

- [x] Registrar estudiantes.
- [x] Listar estudiantes.
- [ ] Editar estudiantes.
- [ ] Eliminar estudiantes.

## Instalación

1. Clonar el repositorio.
2. Abrir el proyecto en NetBeans.
3. Configurar la base de datos MySQL.
4. Ejecutar el proyecto en Tomcat.

## Autor

Proyecto creado por estudiantes de la Especialidad de Programación.
```

---

## 29. Buenas prácticas al escribir Markdown

- Usa títulos claros.
- Escribe párrafos cortos.
- No llenes el documento con demasiado texto.
- Usa listas para ordenar ideas.
- Usa ejemplos concretos.
- Usa tablas solo cuando ayuden a entender mejor.
- Revisa la ortografía antes de subir cambios.
- Usa nombres de archivos claros.
- Mantén un estilo respetuoso y profesional.

---

## 30. Errores comunes

### Error 1: No dejar espacio después del símbolo `#`

Incorrecto:

```markdown
#Título
```

Correcto:

```markdown
# Título
```

### Error 2: No cerrar bloques de código

Incorrecto:

````markdown
```java
System.out.println("Hola");
````

Correcto:

````markdown
```java
System.out.println("Hola");
```
````

### Error 3: Crear documentos demasiado largos sin índice

Si el documento es largo, agrega un índice al inicio.

---

## 31. Mini actividad para practicar

Crea un archivo llamado `MI-PRIMER-MARKDOWN.md` y agrega lo siguiente:

1. Un título principal.
2. Una breve presentación personal.
3. Una lista de tres cosas que quieres aprender en programación.
4. Una tabla con tres comandos de Git y su explicación.
5. Un bloque de código Java.
6. Una frase destacada usando `>`.
7. Una checklist con tareas pendientes.

Ejemplo de inicio:

```markdown
# Mi primer archivo Markdown

Hola, soy estudiante de la Especialidad de Programación.

## Cosas que quiero aprender

- Crear páginas web.
- Programar en Java.
- Usar GitHub correctamente.
```

---

## 32. Mini actividad para aportar al manual de la especialidad

Crea una propuesta de nueva regla usando este formato:

```markdown
# Propuesta de nueva regla

## Nombre de la regla

Escribe aquí el nombre de la regla.

## Qué significa

Explica la regla con tus palabras.

## Por qué es importante

Explica por qué esta regla ayuda a la especialidad.

## Ejemplo correcto

Describe una situación donde se cumple la regla.

## Ejemplo incorrecto

Describe una situación donde no se cumple la regla.
```

---

## 33. Plantilla recomendada para escribir reglas

Puedes copiar esta plantilla cada vez que quieras agregar una nueva regla al manual.

```markdown
## Regla: Nombre de la regla

### Qué significa

Explicación breve y clara.

### Por qué es importante

Razón de fondo de la regla.

### Ejemplo correcto

Situación concreta donde se aplica bien la regla.

### Ejemplo incorrecto

Situación concreta que se debe evitar.

### Propuesta de mejora

Espacio para futuras mejoras o comentarios.
```

---

## 34. Conclusión

Markdown es una herramienta simple, pero muy útil para documentar proyectos de programación.

Aprender Markdown sirve para:

- Crear documentación clara.
- Escribir buenos archivos `README.md`.
- Explicar proyectos en GitHub.
- Crear manuales y guías.
- Registrar avances de trabajo.
- Comunicar ideas de forma profesional.

> Un buen programador no solo escribe código. También sabe explicar, documentar y compartir lo que hace.
