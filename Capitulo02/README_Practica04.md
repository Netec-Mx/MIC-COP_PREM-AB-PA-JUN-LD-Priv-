# Práctica 4. Elaboración de una propuesta de mejora de la atención al cliente con Copilot en Word

## Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Generar un borrador en Word a partir de archivos de referencia.
- Transformar información en una tabla de acciones con responsables y prioridades.
- Revisar coherencia, tono y vacíos de información con Copilot.
- Generar un resumen ejecutivo e integrarlo al documento.

## Objetivo Visual

El siguiente diagrama resume las actividades a realizar.

```mermaid
flowchart LR
    I(["Inicio"])
    I --> T1["Tarea 1<br/>Generar el primer borrador con archivos de referencia<br/>⏱️ 6 min"]
    T1 --> T2["Tarea 2<br/>Reorganizar el contenido y crear la tabla de acciones<br/>⏱️ 5 min"]
    T2 --> T3["Tarea 3<br/>Revisar coherencia y tono<br/>⏱️ 5 min"]
    T3 --> T4["Tarea 4<br/>Generar e integrar el resumen ejecutivo<br/>⏱️ 4 min"]
    T4 --> F(["Propuesta_Atencion_Clientes_[INICIALES].docx con resumen ejecutivo"])
    classDef tarea fill:#e8f0fe,stroke:#1f4e79,color:#1f2a44
    classDef fin fill:#fff4ce,stroke:#b08900,color:#1f2a44
    class T1,T2,T3,T4 tarea
    class F fin
```

El documento de esta práctica alimenta las prácticas 5, 6 y 7 del módulo:

```mermaid
flowchart LR
    F1["Situacion_Atencion_Clientes.docx"] --> W
    F2["Notas_Reunion_Comercial.docx"] --> W
    W["P4 · Word<br/>Propuesta de mejora"] --> P["P5 · PowerPoint<br/>Presentación ejecutiva"]
    P --> O["P6 · Outlook<br/>Comunicaciones"]
    O --> T["P7 · Teams<br/>Reunión de coordinación"]
    style W fill:#e8f0fe,stroke:#1f4e79,stroke-width:3px
```

## Duración aproximada:

- 20 minutos.

## Tabla de ayuda:

Utiliza esta información durante el desarrollo de la práctica.

| Elemento | Valor |
|------------|------------|
| Entorno | Microsoft 365 del curso |
| URL | [https://m365.cloud.microsoft](https://m365.cloud.microsoft) |
| Usuario | Cuenta corporativa asignada al participante |
| Contraseña | Proporcionada por el instructor por el canal autorizado |
| Carpeta de trabajo | `OneDrive > Laboratorio_Copilot_JUN` |

## Entorno de laboratorio

| Componente | Versión | Uso | Fuente oficial |
|------------|------------|------------|------------|
| Microsoft Word | Microsoft 365 (escritorio o web) | Redacción y edición con Copilot | https://support.microsoft.com/es-es/copilot-word |
| OneDrive para el trabajo o la escuela | Servicio administrado | Almacenamiento de archivos de la práctica | https://support.microsoft.com/es-es/onedrive |
| Microsoft Edge | Versión actual | Acceso a Microsoft 365 | https://www.microsoft.com/es-es/edge |

> Microsoft 365 Copilot y sus agentes son servicios administrados que se actualizan de forma continua; los nombres de botones y menús pueden variar ligeramente respecto a esta guía.

## Recursos

| Recurso | Descripción |
|------------|------------|
| [Situacion_Atencion_Clientes.docx](recursos/Situacion_Atencion_Clientes.docx) | Indicadores, problemas y comentarios de clientes (ficticios). |
| [Notas_Reunion_Comercial.docx](recursos/Notas_Reunion_Comercial.docx) | Ideas propuestas por las áreas y restricciones. |
| `Propuesta_Atencion_Clientes_[INICIALES].docx` | Entregable que se reutiliza en las prácticas 5 a 7. |

Archivos de la práctica:

```text
Capitulo02/recursos/Situacion_Atencion_Clientes.docx
Capitulo02/recursos/Notas_Reunion_Comercial.docx
```

## Instrucciones

### Tarea 1. Generar el primer borrador con archivos de referencia (6 min)

**Objetivo de la tarea:** Tener un borrador con situación actual, oportunidades de mejora y acciones propuestas.

Paso 1. Descargar los dos archivos de la carpeta `Capitulo02/recursos` de este repositorio y subirlos a `OneDrive > Laboratorio_Copilot_JUN > Practica04`.

Paso 2. Abrir Word en la web desde [https://m365.cloud.microsoft](https://m365.cloud.microsoft), crear un **Documento en blanco** y guardarlo como `Propuesta_Atencion_Clientes_[INICIALES].docx` en `Entregables`.

Paso 3. En el cuadro **Crear con Copilot** (o con el ícono de Copilot del margen), escribir el prompt. Para referenciar los archivos, escribir `/` y elegir cada archivo en la lista:

```text
Redacta una propuesta de mejora de la atención y el seguimiento de clientes de intralogística con base en /Situacion_Atencion_Clientes y /Notas_Reunion_Comercial.
Incluye: 1) Situación actual con los indicadores, 2) Oportunidades de mejora, 3) Acciones propuestas, 4) Beneficios esperados.
Tono corporativo, en español, máximo 2 páginas.
```

Revisar que el borrador mencione el tiempo de primera respuesta de 38 horas y la meta de 8 horas. Seleccionar **Conservar**.

### Tarea 2. Reorganizar el contenido y crear la tabla de acciones (5 min)

**Objetivo de la tarea:** Tener la sección de acciones convertida en una tabla con actividad, responsable, prioridad y resultado esperado.

Paso 1. Seleccionar el texto de la sección **Acciones propuestas**.

Paso 2. Abrir Copilot desde el ícono junto a la selección y escribir:

```text
Convierte estas acciones en una tabla con las columnas: Actividad, Responsable (área), Prioridad (Alta, Media, Baja), Plazo y Resultado esperado. Respeta la restricción de iniciar en 60 días y sin nuevo software.
```

Paso 3. Revisar la tabla y seleccionar **Reemplazar** (o **Insertar debajo** y eliminar la lista original).

### Tarea 3. Revisar coherencia y tono (5 min)

**Objetivo de la tarea:** Tener el documento revisado, sin inconsistencias y con tono corporativo uniforme.

Paso 1. Abrir el panel de **Copilot** (botón Copilot de la cinta de opciones) y enviar:

```text
Revisa este documento e indica inconsistencias entre los indicadores y las acciones, información faltante y párrafos poco claros. Preséntalo en una lista.
```

Paso 2. Corregir los puntos señalados. Para reescribir un párrafo, seleccionarlo, elegir **Copilot > Reescribir** y aplicar la versión más clara.

### Tarea 4. Generar e integrar el resumen ejecutivo (4 min)

**Objetivo de la tarea:** Tener el resumen ejecutivo al inicio del documento y el archivo guardado.

Paso 1. En el panel de Copilot, enviar:

```text
Genera un resumen ejecutivo de máximo 120 palabras con los principales problemas, las acciones recomendadas y los beneficios esperados.
```

Paso 2. Colocar el cursor al inicio del documento, escribir el título **Resumen ejecutivo**, pegar el resumen y guardar el documento (se guarda automáticamente en OneDrive).

### Resultado esperado

Al finalizar la práctica deberás contar con:

- Propuesta con situación, oportunidades, acciones y beneficios.
- Tabla de acciones con responsables y prioridades.
- Resumen ejecutivo al inicio del documento.

<!-- Agregar captura del resultado esperado: ../images/p04-resultado.png -->

## Resumen

Durante esta práctica se realizó:

- Se generó un borrador a partir de archivos de referencia.
- Se transformó información en una tabla.
- Se revisó la coherencia y se agregó un resumen ejecutivo.

Como resultado se obtuvo:

- Propuesta de mejora lista para presentarse.
- Documento base para las prácticas 5, 6 y 7.

## Recursos opcionales

- [Copilot en Word](https://support.microsoft.com/es-es/copilot-word)
- [Documentación de Microsoft 365 Copilot](https://learn.microsoft.com/es-es/copilot/microsoft-365/)

---

[⬅ Anterior: Práctica 3](../Capitulo01/README_Practica03.md) | [Inicio](../README.md) | [Siguiente: Práctica 5 ➡](../Capitulo02/README_Practica05.md)
