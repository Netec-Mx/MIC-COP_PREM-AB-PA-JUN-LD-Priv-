# Práctica 5. Del documento a una presentación ejecutiva con Copilot en PowerPoint

## Objetivo de la práctica:

Al finalizar la práctica, serás capaz de:

- Crear una presentación a partir de un documento de Word con Copilot.
- Reorganizar la narrativa de la presentación.
- Incorporar imágenes y mejorar el diseño con Copilot.
- Generar notas del orador y un resumen de la presentación.

## Objetivo Visual

El siguiente diagrama resume las actividades a realizar.

```mermaid
flowchart LR
    I(["Inicio"])
    I --> T1["Tarea 1<br/>Crear la presentación desde el documento<br/>⏱️ 6 min"]
    T1 --> T2["Tarea 2<br/>Mejorar la estructura y los títulos<br/>⏱️ 5 min"]
    T2 --> T3["Tarea 3<br/>Incorporar elementos visuales<br/>⏱️ 5 min"]
    T3 --> T4["Tarea 4<br/>Generar notas del orador y el resumen<br/>⏱️ 5 min"]
    T4 --> F(["Presentacion_Mejora_[INICIALES].pptx con notas del orador"])
    classDef tarea fill:#e8f0fe,stroke:#1f4e79,color:#1f2a44
    classDef fin fill:#fff4ce,stroke:#b08900,color:#1f2a44
    class T1,T2,T3,T4 tarea
    class F fin
```

Narrativa que debe seguir la presentación:

```mermaid
flowchart LR
    S["Situación actual<br/>38 h de respuesta"] --> O["Oportunidades<br/>de mejora"]
    O --> A["Acciones<br/>propuestas"]
    A --> R["Resultados<br/>esperados"]
    R --> D(["Decisión<br/>solicitada"])
    style D fill:#fff4ce,stroke:#b08900
```

## Duración aproximada:

- 21 minutos.

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
| Microsoft PowerPoint | Microsoft 365 (escritorio o web) | Creación de presentaciones con Copilot | https://support.microsoft.com/es-es/copilot-powerpoint |
| Microsoft Word | Microsoft 365 (escritorio o web) | Redacción y edición con Copilot | https://support.microsoft.com/es-es/copilot-word |
| OneDrive para el trabajo o la escuela | Servicio administrado | Almacenamiento de archivos de la práctica | https://support.microsoft.com/es-es/onedrive |

> Microsoft 365 Copilot y sus agentes son servicios administrados que se actualizan de forma continua; los nombres de botones y menús pueden variar ligeramente respecto a esta guía.

## Recursos

| Recurso | Descripción |
|------------|------------|
| `Propuesta_Atencion_Clientes_[INICIALES].docx` | Documento elaborado en la Práctica 4. |
| `Presentacion_Mejora_[INICIALES].pptx` | Entregable de la práctica. |

Archivos de la práctica:

```text
OneDrive/Laboratorio_Copilot_JUN/Entregables/Propuesta_Atencion_Clientes_[INICIALES].docx
```

## Instrucciones

### Tarea 1. Crear la presentación desde el documento (6 min)

**Objetivo de la tarea:** Tener una presentación de 7 a 9 diapositivas creada a partir de la propuesta.

Paso 1. Abrir PowerPoint en la web, crear una **Presentación en blanco** y guardarla como `Presentacion_Mejora_[INICIALES].pptx` en `Entregables`.

Paso 2. Abrir **Copilot** y enviar el prompt, referenciando el documento con `/`:

```text
Crea una presentación a partir de /Propuesta_Atencion_Clientes_[INICIALES].
Audiencia: responsables de las áreas Comercial, Servicio y Administración.
Propósito: obtener su compromiso para iniciar las acciones en 60 días.
Extensión: 8 diapositivas. Mensajes clave: tiempo de respuesta actual vs meta, acciones prioritarias y beneficios.
```

Paso 3. Revisar el esquema propuesto por Copilot y seleccionar **Generar diapositivas**. Conservar el resultado.

### Tarea 2. Mejorar la estructura y los títulos (5 min)

**Objetivo de la tarea:** Tener una secuencia situación → oportunidades → acciones → resultados con títulos que expresen una conclusión.

Paso 1. En el panel de Copilot, enviar:

```text
Revisa la organización de las diapositivas. Propón un orden que conecte situación actual, oportunidades, acciones y resultados esperados, y reescribe cada título como una frase que comunique la conclusión principal.
```

Paso 2. Aplicar el orden sugerido arrastrando las miniaturas del panel izquierdo y reemplazar los títulos con las versiones propuestas.

### Tarea 3. Incorporar elementos visuales (5 min)

**Objetivo de la tarea:** Tener al menos dos diapositivas con imágenes o diagramas coherentes con el mensaje.

Paso 1. Ir a la diapositiva de acciones y enviar a Copilot:

```text
Agrega una imagen relacionada con atención al cliente en un almacén y convierte las acciones en un diagrama de proceso de 4 pasos.
```

Paso 2. Seleccionar **Diseñador** (*Designer*) para elegir una distribución que equilibre texto e imagen. Verificar que las imágenes no muestren marcas ni datos sensibles.

### Tarea 4. Generar notas del orador y el resumen (5 min)

**Objetivo de la tarea:** Tener notas del orador en todas las diapositivas y un resumen de 5 líneas.

Paso 1. Enviar a Copilot:

```text
Genera notas del orador para cada diapositiva con los mensajes que debo enfatizar y una duración total de 8 minutos.
```

Paso 2. Enviar:

```text
Resume esta presentación en 5 líneas para compartirla por correo.
```

Paso 3. Copiar el resumen a la nota de la última diapositiva y guardar la presentación.

### Resultado esperado

Al finalizar la práctica deberás contar con:

- Presentación ejecutiva creada desde Word.
- Narrativa y títulos mejorados con elementos visuales.
- Notas del orador y resumen listos.

<!-- Agregar captura del resultado esperado: ../images/p05-resultado.png -->

## Resumen

Durante esta práctica se realizó:

- Se creó una presentación a partir de un documento.
- Se mejoró la narrativa, el diseño y los elementos visuales.
- Se prepararon notas del orador.

Como resultado se obtuvo:

- Presentación ejecutiva lista para la reunión.
- Resumen reutilizable en la Práctica 6.

## Recursos opcionales

- [Copilot en PowerPoint](https://support.microsoft.com/es-es/copilot-powerpoint)
- [Documentación de Microsoft 365 Copilot](https://learn.microsoft.com/es-es/copilot/microsoft-365/)

---

[⬅ Anterior: Práctica 4](../Capitulo02/README_Practica04.md) | [Inicio](../README.md) | [Siguiente: Práctica 6 ➡](../Capitulo02/README_Practica06.md)
