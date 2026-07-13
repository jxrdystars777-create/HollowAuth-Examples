<div align="center">

# HollowAuth Examples

**Ejemplos oficiales de integración para HollowAuth**

![Status](https://img.shields.io/badge/status-beta-orange)
![Project](https://img.shields.io/badge/project-personal-blue)
![C%23](https://img.shields.io/badge/C%23-available-512BD4)
![C++](https://img.shields.io/badge/C++-available-00599C)
![Python](https://img.shields.io/badge/Python-coming%20soon-3776AB)
![JavaScript](https://img.shields.io/badge/JavaScript-coming%20soon-F7DF1E)

</div>

---

Repositorio oficial de ejemplos de integración para `HollowAuth`.

Aquí encontrarás proyectos de referencia diseñados para mostrar cómo integrar el sistema de autenticación de HollowAuth en diferentes lenguajes y entornos de desarrollo.

> [!IMPORTANT]
> `HollowAuth` es un proyecto personal que actualmente se encuentra en fase `Beta`.
>
> Aunque los examples de `C#` y `C++` ya están disponibles, algunas funciones, métodos, SDKs, respuestas de la API o estructuras internas pueden cambiar durante el desarrollo.

## Sobre HollowAuth

`HollowAuth` es un sistema de autenticación desarrollado para facilitar la validación de usuarios, licencias, suscripciones y aplicaciones.

El propósito de este repositorio es proporcionar ejemplos claros, organizados y fáciles de adaptar para distintos proyectos.

> [!NOTE]
> Este repositorio contiene ejemplos de integración.
>
> La documentación, los SDKs y la compatibilidad con nuevos lenguajes serán ampliados progresivamente.

## Compatibilidad

| Lenguaje | Estado |
|---|---|
| `C#` | Disponible |
| `C++` | Disponible |
| `Python` | Próximamente |
| `JavaScript` | Próximamente |
| Otros lenguajes | Planeados |

> [!TIP]
> Los examples de `C#` y `C++` pueden utilizarse actualmente como referencia para comenzar una integración con HollowAuth.

## Examples disponibles

### C#

El example de `C#` está orientado principalmente a aplicaciones de escritorio desarrolladas con Windows Forms.

Puede incluir funciones como:

- Inicialización del cliente de HollowAuth.
- Inicio de sesión mediante licencia.
- Validación de respuestas.
- Manejo de errores.
- Visualización de información del usuario.
- Integración con una interfaz gráfica.

Consulta la carpeta:

```text
/csharp
```

### C++

El example de `C++` está orientado a aplicaciones de escritorio para Windows.

Puede utilizarse como referencia para:

- Configurar el cliente.
- Conectarse con HollowAuth.
- Validar licencias.
- Procesar respuestas.
- Manejar errores de autenticación.
- Integrar HollowAuth en una aplicación de Windows.

Consulta la carpeta:

```text
/cpp
```

### Python

La compatibilidad oficial con `Python` está planeada para una próxima actualización.

Consulta la carpeta:

```text
/python
```

### JavaScript

La compatibilidad oficial con `JavaScript` también será agregada próximamente.

Consulta la carpeta:

```text
/javascript
```

> [!NOTE]
> Las fechas de lanzamiento para `Python`, `JavaScript` y otros lenguajes todavía no son definitivas.

## Estado Beta

HollowAuth continúa en desarrollo activo.

Durante la fase `Beta` podrían producirse:

- Cambios en los métodos disponibles.
- Modificaciones en las respuestas de la API.
- Actualizaciones en los SDKs.
- Cambios en nombres de funciones.
- Ajustes de compatibilidad.
- Errores inesperados.
- Interrupciones temporales.
- Reestructuración de algunos examples.

> [!WARNING]
> No se recomienda utilizar HollowAuth en aplicaciones críticas sin realizar primero pruebas completas en un entorno controlado.

La disponibilidad actual de los examples de `C#` y `C++` no significa que HollowAuth haya salido de su fase Beta.

## Proyecto personal

`HollowAuth` es actualmente un proyecto personal e independiente.

No representa una empresa registrada ni un servicio empresarial consolidado.

Su desarrollo se realiza de forma progresiva con el objetivo de aprender, mejorar y crear una plataforma de autenticación compatible con diferentes lenguajes y tipos de aplicaciones.

> [!IMPORTANT]
> Al utilizar HollowAuth durante su fase Beta, debes tener en cuenta que el proyecto puede recibir cambios importantes sin previo aviso.

## Antes de comenzar

Para utilizar los examples necesitarás registrar una aplicación en HollowAuth y obtener las credenciales correspondientes.

Dependiendo del SDK o lenguaje, podrías necesitar:

```text
Application Name
Application ID
Application Secret
Version
API URL
```

Reemplaza siempre los valores de ejemplo con la información correspondiente a tu aplicación.

## Ejemplo de configuración en C#

```csharp
public HollowAuth.api HollowApp = new HollowAuth.api(
    "YOUR_APP_NAME",
    "YOUR_APP_ID",
    "YOUR_APP_SECRET",
    "1.0",
    "https://hollowauth.onrender.com/api/client"
);
```

> [!CAUTION]
> Nunca publiques tu `Application Secret`, tokens, licencias reales, contraseñas o credenciales privadas dentro de GitHub.

## Seguridad

Antes de subir un proyecto público, verifica que no contenga:

- `Application Secret` real.
- Licencias activas.
- Tokens privados.
- Contraseñas.
- Variables de entorno.
- Credenciales de base de datos.
- Información privada de usuarios.

Utiliza valores de demostración como:

```text
YOUR_APP_NAME
YOUR_APP_ID
YOUR_APP_SECRET
YOUR_LICENSE
```

> [!WARNING]
> Un repositorio público puede ser visto, descargado y copiado por cualquier persona.

## Estructura del repositorio

```text
HollowAuth-Examples/
│
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── SECURITY.md
├── .gitignore
│
├── csharp/
│   ├── README.md
│   └── example/
│
├── cpp/
│   ├── README.md
│   └── example/
│
├── python/
│   └── README.md
│
├── javascript/
│   └── README.md
│
├── docs/
│   └── README.md
│
└── assets/
```

## Reportar errores

Si encuentras un error en uno de los examples, abre un `Issue` e incluye:

- Lenguaje utilizado.
- Nombre del example.
- Versión de HollowAuth.
- Versión del SDK.
- Descripción del problema.
- Pasos para reproducirlo.
- Mensaje de error.
- Capturas de pantalla, cuando sean necesarias.

> [!CAUTION]
> Antes de publicar un reporte, elimina cualquier licencia, secreto, token o información privada.

## Contribuciones

Las contribuciones pueden incluir:

- Correcciones de documentación.
- Mejoras en los examples.
- Nuevas implementaciones.
- Manejo adicional de errores.
- Recomendaciones de seguridad.
- Compatibilidad con nuevos lenguajes.

Antes de enviar una contribución, consulta el archivo:

```text
CONTRIBUTING.md
```

## Soporte

Este repositorio está destinado principalmente a examples y documentación.

Para solicitar soporte relacionado con HollowAuth, utiliza solamente los canales oficiales del proyecto.

No publiques información privada dentro de los `Issues`.

## Aviso

Los examples proporcionados pueden necesitar modificaciones para adaptarse a cada proyecto.

No se garantiza compatibilidad con todos los sistemas operativos, versiones, configuraciones o entornos de desarrollo.

---

<div align="center">

**HollowAuth**

Proyecto personal en fase `Beta`.

`C#` y `C++` disponibles actualmente.

`Python`, `JavaScript` y otros lenguajes próximamente.

</div>
