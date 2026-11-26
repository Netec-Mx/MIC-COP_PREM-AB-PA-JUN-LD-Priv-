# Setup Guide General

## Transformación Digital y Productividad con Microsoft 365 Copilot Premium, Agentes y Automatización

| Control documental | Información |
|---|---|
| Clave del curso | MIC COP_PREM AB PA JUN LD (Priv) |
| Versión del documento | 0.1 |
| Estado | BORRADOR |
| Instructor responsable | [NOMBRE] |
| Fecha de elaboración | 2026-11-26 |
| Fecha de última validación | [AAAA-MM-DD] |
| Repositorio de laboratorios | https://github.com/Netec-Mx/MIC-COP_PREM-AB-PA-JUN-LD-Priv- |
| Rama y revisión analizada | main, [COMMIT] |
| Alcance revisado | 6 capítulos, 18 prácticas, README principal y este documento |
| Modalidad del entorno | WEB: servicios administrados de Microsoft 365 |

> **Instrucciones para el instructor — eliminar antes de entregar:** completar los campos entre corchetes. Validar con una cuenta equivalente a la del participante que los agentes, la creación de agentes, Power Automate y la generación de imágenes estén habilitados en el inquilino. No registrar contraseñas en este documento.

# Objetivo

Contar, para cada participante, con una cuenta de Microsoft 365 con licencia de Microsoft 365 Copilot Premium y acceso a Word, Excel, PowerPoint, Outlook, Teams, OneDrive, Microsoft Forms, SharePoint, Power Automate, los agentes Prompt Coach, Idea Coach y Analyst, y Agent Builder. El entorno está listo cuando el participante puede usar Copilot en cada aplicación, consultar los agentes, crear un agente y crear un flujo de nube conectado a Forms, SharePoint y Outlook.

# Requisitos de Hardware

| Recurso | Mínimo requerido | Recomendado | Observaciones |
|---|---|---|---|
| Procesador y arquitectura | Doble núcleo, 64 bits | Cuatro núcleos | El trabajo se realiza en el navegador |
| Memoria RAM | 8 GB | 16 GB | Varias aplicaciones de Microsoft 365 abiertas a la vez |
| Espacio libre | 2 GB | 5 GB | Descarga de archivos de práctica |
| Pantalla | 1366 × 768 | 1920 × 1080 o dos monitores | Seguir la guía y trabajar en paralelo |
| Conectividad | 10 Mbps estables | 20 Mbps | Servicios en la nube y videoconferencia |

# Sistemas Operativos Compatibles

| Sistema operativo | Edición y versión | Arquitectura | Condición de soporte o validación |
|---|---|---|---|
| Windows | 10 o 11 con soporte vigente | x64 | Compatible según fabricante |
| macOS | Versiones con soporte de Microsoft 365 | x64 / ARM | Compatible según fabricante |

Las prácticas se realizan en Microsoft 365 desde el navegador; las aplicaciones de escritorio son opcionales.

# Software Requerido

| Componente | Edición y versión requerida | Arquitectura | Obligatorio u opcional | Fuente oficial |
|---|---|---|---|---|
| Microsoft Edge o Google Chrome | Versión actual | — | Obligatorio | https://www.microsoft.com/es-es/edge |
| Microsoft 365 Copilot | Servicio administrado, licencia Premium | — | Obligatorio | https://learn.microsoft.com/es-es/copilot/microsoft-365/ |
| Word, Excel, PowerPoint, Outlook, Teams | Microsoft 365 (web o escritorio) | — | Obligatorio | https://www.microsoft.com/es-es/microsoft-365 |
| Power Automate | Servicio administrado | — | Obligatorio (Capítulos 4 y 6) | https://make.powerautomate.com |
| Microsoft Forms y SharePoint Online | Servicio administrado | — | Obligatorio (Capítulo 4) | https://forms.office.com |
| Agent Builder | Servicio administrado | — | Obligatorio (Capítulos 5 y 6) | https://learn.microsoft.com/es-es/microsoft-365-copilot/extensibility/agent-builder |

# Herramientas y Dependencias

## Paquetes, frameworks y componentes adicionales

| Dependencia | Versión o restricción | Componente que la necesita | Método de instalación o habilitación |
|---|---|---|---|
| Agentes Prompt Coach e Idea Coach | Servicio administrado | Prácticas 1 y 3 | Habilitados por el administrador en el catálogo de agentes |
| Agente Analyst | Servicio administrado | Prácticas 11 y 17 | Habilitado por el administrador |
| Creación de agentes | Política del inquilino | Prácticas 15 a 17 | Habilitada por el administrador |
| Generación de imágenes con Copilot | Servicio administrado | Práctica 2 | Habilitada en el inquilino |
| Conectores de Forms, SharePoint, Outlook y Aprobaciones | Estándar | Prácticas 12 y 13 | Disponibles en Power Automate |

## Licencias, cuentas y permisos

| Recurso o servicio | Licencia o suscripción | Cuenta o rol requerido | Permiso mínimo | Responsable de habilitación |
|---|---|---|---|---|
| Microsoft 365 | Licencia empresarial con Exchange, SharePoint y OneDrive | Usuario | Uso de aplicaciones | Organización cliente / Netec |
| Microsoft 365 Copilot Premium | Licencia de Copilot asignada | Usuario | Uso de Copilot y agentes | Organización cliente / Netec |
| Power Automate | Incluido en Microsoft 365 (conectores estándar) | Usuario | Crear flujos de nube | Organización cliente / Netec |
| Sitio de SharePoint `Laboratorio Copilot JUN` | — | Miembro del sitio | Editar | Instructor |

Las credenciales se entregan por el canal autorizado; no se registran en este documento.

# Instalación y Configuración

## 1. Obtener los materiales

- Repositorio de laboratorios: https://github.com/Netec-Mx/MIC-COP_PREM-AB-PA-JUN-LD-Priv-
- Archivos de práctica (ficticios):

```text
Capitulo02/recursos/Situacion_Atencion_Clientes.docx   → Práctica 4
Capitulo02/recursos/Notas_Reunion_Comercial.docx       → Práctica 4
Capitulo03/recursos/Indicadores_Jungheinrich_2026.xlsx → Prácticas 8 a 10
Capitulo06/recursos/Operacion_Almacen_Centro.xlsx      → Práctica 17
```

## 2. Instalar o habilitar los componentes

### Cuenta y licencia del participante

1. Asignar a cada participante una cuenta de Microsoft 365 con licencia de Copilot Premium.
2. Habilitar los agentes Prompt Coach, Idea Coach y Analyst, la creación de agentes y la generación de imágenes.
3. Iniciar sesión en https://m365.cloud.microsoft con la cuenta y abrir Copilot Chat.

**Resultado esperado:** Copilot Chat muestra la opción **Trabajo** y el escudo de protección de datos empresariales.

### Sitio de SharePoint del curso

1. Crear un sitio de grupo `Laboratorio Copilot JUN`.
2. Agregar a todos los participantes como miembros con permiso de edición.

## 3. Preparar archivos de configuración

| Archivo | Ruta | Configuración necesaria | Origen |
|---|---|---|---|
| Carpeta de trabajo | `OneDrive > Laboratorio_Copilot_JUN` con subcarpetas `Entregables`, `Practica04`, `Practica17` | Ninguna | Crear (participante, primer día) |

# Variables de Entorno

No aplica: el curso se realiza en servicios web de Microsoft 365.

# Configuración Base para los Laboratorios

## Parámetros comunes

| Parámetro | Valor o convención | Observaciones |
|---|---|---|
| Carpeta de trabajo | `OneDrive > Laboratorio_Copilot_JUN` | Todos los entregables en `Entregables` |
| Sufijo de nombres | `[INICIALES]` del participante | Archivos, formularios, listas, flujos y agentes |
| Destinatarios de correo | La propia cuenta del participante | No enviar correos a terceros durante el curso |
| Datos | Ficticios | No usar información real de clientes |

## Recursos compartidos

| Recurso | Nombre o identificador | Estructura o configuración base | Responsable de creación |
|---|---|---|---|
| Sitio de SharePoint | `Laboratorio Copilot JUN` | Sitio de grupo con participantes como miembros | Instructor |
| Lista de SharePoint | `Solicitudes_Mantenimiento_[INICIALES]` | Título, Correo, TipoEquipo, Descripcion, Prioridad | Participante (Práctica 12) |

## Correcciones de coherencia

| Inconsistencia o dependencia omitida | Configuración unificada | Ajuste necesario en las copias de trabajo |
|---|---|---|
| Los nombres de menús de Copilot pueden cambiar con las actualizaciones del servicio | Validar las rutas de las prácticas en la semana del curso | [REGISTRAR CAMBIOS] |
| Las prácticas 4 a 7, 8 a 10, 12 a 13 y 14 a 17 dependen de la anterior | Conservar los entregables en `Entregables` | Ninguno |

# Servicios Externos Requeridos

| Servicio | URL, endpoint o región | Uso | Acceso requerido |
|---|---|---|---|
| Microsoft 365 | https://m365.cloud.microsoft | Aplicaciones y Copilot | Cuenta del curso |
| Power Automate | https://make.powerautomate.com | Flujos | Cuenta del curso |
| Sitio público de Jungheinrich | https://www.jungheinrich.com | Fuente de conocimiento del agente (Prácticas 14 a 17) | Acceso público |
| GitHub | https://github.com | Guías y archivos de práctica | Acceso público |

## Configuración de red

| Origen | Destino | Protocolo y puerto | Sentido | Condición |
|---|---|---|---|---|
| Equipo del participante | Dominios de Microsoft 365 | HTTPS 443 | Saliente | Obligatorio; ver la [lista oficial de URL e IP de Microsoft 365](https://learn.microsoft.com/es-es/microsoft-365/enterprise/urls-and-ip-address-ranges) |
| Equipo del participante | github.com, netec-mx.github.io | HTTPS 443 | Saliente | Obligatorio |

# Creación de Entornos / Máquinas Virtuales / Emuladores

No aplica: no se requieren máquinas virtuales.

# Validación del Entorno

| ID | Componente o capacidad | Procedimiento | Resultado esperado | Evidencia mínima |
|---|---|---|---|---|
| V-01 | Copilot Chat | Enviar un prompt en modo Trabajo | Respuesta con protección de datos empresariales | Captura del chat |
| V-02 | Copilot en aplicaciones | Abrir Copilot en Word, Excel, PowerPoint, Outlook y Teams | El botón Copilot está activo en las cinco | Captura |
| V-03 | Agentes | Abrir Prompt Coach, Idea Coach y Analyst | Los tres responden | Captura |
| V-04 | Creación de agentes | Seleccionar **Agentes > Crear agente** | Se abre Agent Builder | Captura |
| V-05 | Power Automate | Crear un flujo de prueba con Forms y SharePoint | El flujo se guarda y ejecuta | Historial de ejecución |
| V-06 | Generación de imágenes | Pedir a Copilot "Crea una imagen de un almacén" | Se genera una imagen | Captura |

**Criterio de entorno listo:** V-01 a V-05 obligatorias; V-06 recomendada (si no está disponible, la Práctica 2 se completa con la descripción visual).

# Comandos de Verificación

No aplica: la validación se realiza en las interfaces web descritas en *Validación del Entorno*.

# Troubleshooting

| Síntoma | Causa probable | Comprobación | Corrección | Validación posterior |
|---|---|---|---|---|
| No aparece el botón Copilot | Licencia no asignada o sesión con otra cuenta | Revisar la cuenta en la esquina superior derecha | Asignar licencia o iniciar sesión con la cuenta del curso | V-02 |
| No aparecen los agentes | Agentes no habilitados | Buscar en **Agentes > Todos los agentes** | Habilitarlos desde el centro de administración | V-03 |
| No aparece Crear agente | Política del inquilino | Revisar con el administrador | Habilitar la creación de agentes | V-04 |
| El flujo falla al crear elemento | Sin permisos en el sitio | Revisar membresía del sitio | Agregar al participante como miembro | V-05 |

# Checklist Final

- [ ] Cuentas con licencia de Microsoft 365 Copilot Premium asignada.
- [ ] Agentes Prompt Coach, Idea Coach y Analyst habilitados.
- [ ] Creación de agentes y generación de imágenes habilitadas.
- [ ] Sitio de SharePoint `Laboratorio Copilot JUN` con participantes como miembros.
- [ ] Power Automate con conectores de Forms, SharePoint, Outlook y Aprobaciones disponibles.
- [ ] Archivos de práctica disponibles en el repositorio.
- [ ] Validaciones V-01 a V-05 completadas.

# Resumen

Cada participante trabaja en Microsoft 365 desde el navegador con una cuenta con Copilot Premium, una carpeta `Laboratorio_Copilot_JUN` en OneDrive, acceso de edición al sitio de SharePoint del curso, Power Automate y Agent Builder habilitados.

## Registro de validación

| Fecha | Responsable | Plataforma o entorno probado | Resultado | Limitaciones o acciones pendientes |
|---|---|---|---|---|
| [AAAA-MM-DD] | [NOMBRE] | [INQUILINO DE MICROSOFT 365] | [APTO / NO APTO] | [DETALLE O NINGUNA] |

## Referencias oficiales

| Documento o recurso | URL | Fecha de consulta |
|---|---|---|
| Microsoft 365 Copilot | https://learn.microsoft.com/es-es/copilot/microsoft-365/ | [AAAA-MM-DD] |
| Agent Builder | https://learn.microsoft.com/es-es/microsoft-365-copilot/extensibility/agent-builder | [AAAA-MM-DD] |
| Copilot en Power Automate | https://learn.microsoft.com/es-es/power-automate/get-started-with-copilot | [AAAA-MM-DD] |
| URL e IP de Microsoft 365 | https://learn.microsoft.com/es-es/microsoft-365/enterprise/urls-and-ip-address-ranges | [AAAA-MM-DD] |
