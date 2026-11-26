# Práctica 2. De una idea a una comunicación visual con IA

**Capítulo 1. Fundamentos de IA Generativa, Microsoft Copilot Premium y Prompt Engineering**

---

# Metadatos

| Campo | Valor |
|------------|------------|
| Duración | 8 minutos |
| Complejidad | Fácil |
| Nivel de Bloom | Aplicar |
| Tecnología Principal | Microsoft 365 Copilot (generación de imágenes) |

---

# Descripción General

El área de Recursos Humanos necesita comunicar a los colaboradores una iniciativa interna: el uso responsable de Microsoft 365 Copilot en el trabajo diario. El participante desarrollará con Copilot el concepto de una infografía, refinará la descripción del contenido, la audiencia y el estilo, y generará la pieza visual para observar cómo las instrucciones influyen en el resultado.

---

# Objetivos de Aprendizaje

Al finalizar la práctica, el participante será capaz de:

- Definir con Copilot el concepto de una pieza visual a partir de una necesidad de comunicación.
- Redactar una instrucción de imagen con contenido, audiencia y estilo.
- Generar y refinar una infografía con las capacidades generativas de Copilot.

---

# Objetivo Visual

El siguiente diagrama resume las tareas de la práctica, su duración y el resultado que se obtiene.

```mermaid
flowchart LR
    I(["Inicio"])
    I --> T1["Tarea 1<br/>Definir el concepto de la pieza visual<br/>⏱️ 3 min"]
    T1 --> T2["Tarea 2<br/>Generar y refinar la infografía<br/>⏱️ 5 min"]
    T2 --> F(["infografía de la iniciativa guardada en Entregables"])
    classDef tarea fill:#e8f0fe,stroke:#1f4e79,color:#1f2a44
    classDef fin fill:#fff4ce,stroke:#b08900,color:#1f2a44
    class T1,T2 tarea
    class F fin
```

Cómo la instrucción define la pieza visual:

```mermaid
flowchart LR
    N["Necesidad de<br/>comunicación"] --> M["Mensaje + audiencia<br/>+ estilo"]
    M --> G["Generación<br/>de imagen"]
    G --> V{"¿Claro y legible?"}
    V -- No --> A["Ajustar instrucción"] --> G
    V -- Sí --> I(["Infografía"])
    style I fill:#fff4ce,stroke:#b08900
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
| Microsoft 365 Copilot (licencia Premium) | Servicio administrado | Chat y asistente en las aplicaciones de Microsoft 365 | https://learn.microsoft.com/es-es/copilot/microsoft-365/ |
| Microsoft Edge | Versión actual | Acceso a Microsoft 365 | https://www.microsoft.com/es-es/edge |
| OneDrive para el trabajo o la escuela | Servicio administrado | Almacenamiento de archivos de la práctica | https://support.microsoft.com/es-es/onedrive |

> Microsoft 365 Copilot y sus agentes son servicios administrados que se actualizan de forma continua; los nombres de botones y menús pueden variar ligeramente respecto a esta guía.

---

# Recursos

Utilice los siguientes recursos durante el desarrollo de la práctica.

| Recurso | Descripción |
|------------|------------|
| [Microsoft 365 Copilot](https://m365.cloud.microsoft/chat) | Chat y creación de imágenes con Copilot. |
| Imagen `P02_Infografia_[INICIALES].png` | Entregable de la práctica. |

## Archivos de la práctica

```text
Esta práctica no requiere archivos de entrada.
```

---

# Tarea 1. Definir el concepto de la pieza visual (3 min)

## Objetivo

Obtener el mensaje principal, tres ideas de apoyo y la descripción visual de la infografía.

## Instrucciones

### Paso 1

Abrir Copilot Chat en modo **Trabajo** e iniciar un **Nuevo chat**.

### Paso 2

Enviar el prompt:

```text
Necesito comunicar a los colaboradores de una empresa de intralogística la iniciativa "Copilot responsable: más tiempo para lo importante".
Audiencia: personal comercial, administrativo y de servicio.
Propón: un mensaje principal de máximo 8 palabras, tres ideas de apoyo de una línea (verificar siempre los resultados, no compartir información confidencial fuera de Microsoft 365 y usar prompts claros) y una descripción visual para una infografía vertical con estilo corporativo, colores azul y amarillo, íconos simples y poco texto.
```

---

# Tarea 2. Generar y refinar la infografía (5 min)

## Objetivo

Tener guardada la infografía `P02_Infografia_[INICIALES].png`.

## Instrucciones

### Paso 1

Enviar el prompt de generación, ajustándolo con el mensaje elegido:

```text
Crea una imagen tipo infografía vertical con el título "Copilot responsable: más tiempo para lo importante" y tres bloques con íconos: 1) Verifica los resultados, 2) Protege la información, 3) Pide con claridad. Estilo corporativo, fondo claro, colores azul marino y amarillo, sin personas, texto grande y legible.
```

### Paso 2

Revisar la imagen. Si el texto aparece con errores o hay demasiados elementos, enviar:

```text
Simplifica la imagen: deja solo el título y los tres bloques, aumenta el tamaño del texto y elimina elementos decorativos.
```

### Paso 3

Seleccionar la imagen, elegir **Descargar** y guardarla con el nombre `P02_Infografia_[INICIALES].png` en `OneDrive > Laboratorio_Copilot_JUN > Entregables`.

---

# Validación y Pruebas

Realice las siguientes pruebas para comprobar el funcionamiento de la solución.

| Caso | Acción o Prompt | Resultado Esperado |
|------------|------------|------------|
| Caso 1 | Prompt de concepto | Mensaje principal, tres ideas y descripción visual |
| Caso 2 | Prompt de generación de imagen | Infografía vertical con título y tres bloques |
| Caso 3 | Prompt de simplificación | Imagen con menos elementos y texto más legible |
| Caso adversarial | Pedir el logotipo oficial de una marca | Copilot no reproduce logotipos protegidos o advierte la restricción |

---

# Resultado Esperado

Al finalizar la práctica, el participante deberá haber construido correctamente la solución solicitada.

- Concepto de la comunicación definido.
- Infografía generada y refinada.
- Imagen guardada en `Entregables`.

## Imagen del Resultado Final

Agregar una captura de pantalla del resultado final esperado.

```markdown
../images/p02-resultado-final.png
```

---

# Solución de Problemas

## Problema 1: Copilot no genera imágenes

### Síntomas

Copilot responde solo con texto.

### Causa

La generación de imágenes no está disponible en el inquilino o el prompt no la solicita explícitamente.

### Solución

1. Iniciar el prompt con "Crea una imagen".
2. Probar desde la aplicación Microsoft 365 Copilot en **Crear**.
3. Si sigue sin estar disponible, informar al instructor y conservar la descripción visual como entregable.

---

## Problema 2: El texto de la imagen tiene errores

### Síntomas

Palabras mal escritas en la infografía.

### Causa

Los modelos de imagen pueden deformar textos largos.

### Solución

1. Reducir el texto de la imagen a títulos cortos.
2. Solicitar una nueva versión.
3. Agregar el texto definitivo después en PowerPoint si es necesario.

---

# Limpieza

1. Conservar los entregables en `OneDrive > Laboratorio_Copilot_JUN > Entregables`; se reutilizan en prácticas posteriores.
2. No compartir los archivos de la práctica fuera del grupo del curso.
3. Cerrar las conversaciones de Copilot que contengan información de la práctica si se trabaja en un equipo compartido.

---

# Resumen

Durante esta práctica se realizó:

- Se definió el concepto de una comunicación interna.
- Se generó una infografía con IA.
- Se refinó el resultado con instrucciones adicionales.

Como resultado se obtuvo:

- Una pieza visual lista para revisión.
- Experiencia sobre cómo el detalle del prompt cambia la imagen.

---

# Recursos Opcionales

- [Documentación de Microsoft 365 Copilot](https://learn.microsoft.com/es-es/copilot/microsoft-365/)
- [Crear imágenes con Copilot](https://support.microsoft.com/es-es/copilot)

---

[⬅ Anterior: Práctica 1](../Capitulo01/README_Practica01.md) | [Inicio](../README.md) | [Siguiente: Práctica 3 ➡](../Capitulo01/README_Practica03.md)
