# Práctica 10. Creación de visualizaciones y reportes con Copilot en Excel

**Capítulo 3. Análisis de Datos, Generación de Reportes e Insights en Excel**

---

# Metadatos

| Campo | Valor |
|------------|------------|
| Duración | 10 minutos |
| Complejidad | Intermedia |
| Nivel de Bloom | Aplicar |
| Tecnología Principal | Microsoft 365 Copilot en Excel |

---

# Descripción General

A partir de los indicadores de la Práctica 9, el participante generará con Copilot gráficos y tablas dinámicas para visualizar tendencias comerciales, comparar resultados por región y detectar oportunidades de mejora. Organizará las visualizaciones en una hoja de resumen que facilite su interpretación.

---

# Objetivos de Aprendizaje

Al finalizar la práctica, el participante será capaz de:

- Generar gráficos con Copilot a partir de indicadores.
- Crear tablas dinámicas con lenguaje natural.
- Organizar una hoja de resumen para la toma de decisiones.

---

# Objetivo Visual

El siguiente diagrama resume las tareas de la práctica, su duración y el resultado que se obtiene.

```mermaid
flowchart LR
    I(["Inicio"])
    I --> T1["Tarea 1<br/>Generar gráficos y tablas dinámicas<br/>⏱️ 6 min"]
    T1 --> T2["Tarea 2<br/>Preparar la hoja de resumen<br/>⏱️ 4 min"]
    T2 --> F(["hoja Resumen con gráficos y tabla dinámica"])
    classDef tarea fill:#e8f0fe,stroke:#1f4e79,color:#1f2a44
    classDef fin fill:#fff4ce,stroke:#b08900,color:#1f2a44
    class T1,T2 tarea
    class F fin
```

De los indicadores al reporte:

```mermaid
flowchart LR
    I["Hoja Indicadores"] --> G["Gráfico por<br/>región y trimestre"]
    I --> TD["Tabla dinámica<br/>mantenimiento"]
    G --> R(["Hoja Resumen<br/>con conclusiones"])
    TD --> R
    style R fill:#fff4ce,stroke:#b08900
```

---

# Prerrequisitos

## Conocimientos

- Conocimientos básicos de correo electrónico, calendario, documentos y herramientas de colaboración de Microsoft 365.
- Experiencia en actividades como envío de correos, seguimiento de clientes o actividades, elaboración de reportes, coordinación entre áreas o actualización de archivos.
- Conocimiento de las políticas internas de seguridad, confidencialidad y manejo de información de la organización.
- No se requiere experiencia previa en desarrollo, programación o automatización.

## Accesos Requeridos

- Cuenta de Microsoft 365 con licencia de Microsoft 365 Copilot Premium asignada.
- Acceso a OneDrive con la carpeta `Laboratorio_Copilot_JUN` creada (ver [Setup Guide](../Setup_Guide.md)).

---

# Tabla de Ayuda

Utilice esta información durante el desarrollo de la práctica.

| Elemento | Valor |
|------------|------------|
| Entorno | Microsoft 365 del curso |
| URL | [https://m365.cloud.microsoft](https://m365.cloud.microsoft) |
| Usuario | Cuenta corporativa asignada al participante |
| Contraseña | Proporcionada por el instructor por el canal autorizado |
| Carpeta de trabajo | `OneDrive > Laboratorio_Copilot_JUN` |

---

# Entorno de Laboratorio

| Componente | Versión | Uso | Fuente Oficial |
|------------|------------|------------|------------|
| Microsoft Excel | Microsoft 365 (escritorio o web) | Análisis de datos con Copilot | https://support.microsoft.com/es-es/copilot-excel |
| OneDrive para el trabajo o la escuela | Servicio administrado | Almacenamiento de archivos de la práctica | https://support.microsoft.com/es-es/onedrive |

> Microsoft 365 Copilot y sus agentes son servicios administrados que se actualizan de forma continua; los nombres de botones y menús pueden variar ligeramente respecto a esta guía.

---

# Recursos

Utilice los siguientes recursos durante el desarrollo de la práctica.

| Recurso | Descripción |
|------------|------------|
| `Indicadores_[INICIALES].xlsx` | Libro con la hoja Indicadores de la Práctica 9. |

## Archivos de la práctica

```text
OneDrive/Laboratorio_Copilot_JUN/Entregables/Indicadores_[INICIALES].xlsx
```

---

# Tarea 1. Generar gráficos y tablas dinámicas (6 min)

## Objetivo

Tener un gráfico de importe por región y trimestre y una tabla dinámica de mantenimiento por prioridad.

## Instrucciones

### Paso 1

Abrir `Indicadores_[INICIALES].xlsx`, ir a la hoja **Ventas** y abrir **Copilot**.

### Paso 2

Enviar:

```text
Crea un gráfico de columnas agrupadas con el importe por región y trimestre.
```

Seleccionar **Agregar a una hoja nueva**.

### Paso 3

Ir a **Mantenimiento** y enviar:

```text
Crea una tabla dinámica con el número de solicitudes y el promedio de horas de atención por región y prioridad.
```

Seleccionar **Agregar a una hoja nueva**.

---

# Tarea 2. Preparar la hoja de resumen (4 min)

## Objetivo

Tener una hoja Resumen con las visualizaciones y una interpretación breve.

## Instrucciones

### Paso 1

Crear una hoja llamada **Resumen**, mover a ella el gráfico y copiar la tabla dinámica (o un gráfico dinámico de ella).

### Paso 2

Con la hoja **Resumen** seleccionada, enviar a Copilot:

```text
Redacta tres conclusiones de una línea sobre las tendencias que muestran estas visualizaciones y una oportunidad de mejora.
```

### Paso 3

Pegar las conclusiones en la parte superior de la hoja **Resumen** y guardar.

---

# Validación y Pruebas

Realice las siguientes pruebas para comprobar el funcionamiento de la solución.

| Caso | Acción o Prompt | Resultado Esperado |
|------------|------------|------------|
| Caso 1 | Prompt de gráfico | Gráfico de columnas por región y trimestre |
| Caso 2 | Prompt de tabla dinámica | Tabla con conteo y promedio por región y prioridad |
| Caso 3 | Conclusiones | Tres conclusiones y una oportunidad de mejora |
| Caso adversarial | Pedir un gráfico de una columna inexistente | Copilot indica que la columna no existe |

---

# Resultado Esperado

Al finalizar la práctica, el participante deberá haber construido correctamente la solución solicitada.

- Gráfico comparativo por región y trimestre.
- Tabla dinámica de mantenimiento.
- Hoja Resumen con conclusiones.

## Imagen del Resultado Final

Agregar una captura de pantalla del resultado final esperado.

```markdown
../images/p10-resultado-final.png
```

---

# Solución de Problemas

## Problema 1: La tabla dinámica no se crea

### Síntomas

Copilot responde solo con texto.

### Causa

Los datos no tienen formato de tabla o hay encabezados duplicados.

### Solución

1. Seleccionar el rango y presionar **Ctrl+T**.
2. Volver a enviar el prompt.

---

## Problema 2: El gráfico mezcla trimestres

### Síntomas

Las barras no distinguen T1 y T2.

### Causa

No existe la columna Trimestre.

### Solución

1. Agregar la columna Trimestre como en la Práctica 9.
2. Repetir el prompt indicando la columna.

---

# Limpieza

1. Conservar los entregables en `OneDrive > Laboratorio_Copilot_JUN > Entregables`; se reutilizan en prácticas posteriores.
2. No compartir los archivos de la práctica fuera del grupo del curso.
3. Cerrar las conversaciones de Copilot que contengan información de la práctica si se trabaja en un equipo compartido.

---

# Resumen

Durante esta práctica se realizó:

- Se generaron gráficos y tablas dinámicas con Copilot.
- Se preparó una hoja de resumen.

Como resultado se obtuvo:

- Reporte visual de indicadores.
- Conclusiones listas para la planificación.

---

# Recursos Opcionales

- [Copilot en Excel](https://support.microsoft.com/es-es/copilot-excel)
- [Tablas dinámicas](https://support.microsoft.com/es-es/excel)

---

[⬅ Anterior: Práctica 9](../Capitulo03/README_Practica09.md) | [Inicio](../README.md) | [Siguiente: Práctica 11 ➡](../Capitulo03/README_Practica11.md)
