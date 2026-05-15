# jvf.io() — Siebel Developer Utilities

Extensión de Chrome con utilidades de desarrollo para Siebel CRM.

---

## Versiones disponibles

La extensión tiene 3 versiones según el conjunto de utilidades incluidas:

| Archivo | Descripción | Dirigido a |
|---|---|---|
| `jvfio-expert.zip` | Todas las utilidades (15 módulos) | Desarrolladores Siebel |
| `jvfio-dev.zip` | Utilidades de desarrollo (12 módulos) | Desarrolladores con acceso limitado |
| `jvfio-funcional.zip` | Utilidades básicas (4 módulos) | Consultores funcionales / QA |

> Cada versión tiene su propia contraseña de descompresión. Solicítala al administrador de la extensión.

---

## Instalación desde cero

### Paso 1 — Descargar

1. Ir a la sección de **[Releases](https://github.com/Jhonvf20/jvf-io-chrome-advanced/releases/latest)**.
2. En la sección **Assets**, descargar el archivo `.zip` que te corresponda.

### Paso 2 — Descomprimir

1. Crear una carpeta fija en tu equipo donde vivirá la extensión. Ejemplo:
   - Windows: `C:\ExtensionesChrome\jvfio`
   - Mac: `~/Extensiones/jvfio`
2. Descomprimir el `.zip` con la contraseña proporcionada **dentro de esa carpeta**.
3. Verificar que la carpeta contiene archivos como `manifest.json`, `content.js`, `background.js`, etc.

> **Importante:** No muevas ni renombres esta carpeta después de instalar. Chrome la necesita en la misma ubicación para que la extensión funcione.

### Paso 3 — Instalar en Chrome

1. Abrir Chrome y navegar a `chrome://extensions`.
2. Activar el **Modo desarrollador** (interruptor en la esquina superior derecha).
3. Hacer click en **Cargar extensión sin empaquetar** (o "Load unpacked").
4. Seleccionar la carpeta donde descomprimiste los archivos (la que contiene `manifest.json`).
5. La extensión aparecerá en la lista con el nombre **jvf.io() - Siebel Utilities**.
6. Fijar la extensión en la barra de Chrome haciendo click en el ícono de puzzle (🧩) y luego en el pin (📌).

### Paso 4 — Usar

1. Navegar a una sesión de Siebel CRM en Chrome.
2. Hacer click en el ícono de **jvf.io()** en la barra de extensiones.
3. Hacer click en **Activar Utilidades**.
4. Las herramientas se inyectan en la sesión activa de Siebel.

---

## Actualización de la extensión

Existen dos formas de actualizar según la conectividad de tu equipo.

### Actualización automática (equipos con internet)

La extensión verifica automáticamente cada 4 horas si hay una versión nueva disponible. Cuando detecta una actualización:

1. Aparece un indicador **!** de color rosa en el ícono de la extensión.
2. Al abrir el popup, se muestra un banner con la nueva versión y una descripción de los cambios.
3. Hacer click en **Descargar actualización**. Se abrirá la descarga del `.zip` correspondiente a tu versión.
4. Descomprimir el `.zip` descargado en la **misma carpeta** donde tienes la extensión actual (reemplazar archivos existentes).
5. Ir a `chrome://extensions` y hacer click en el botón de **recarga** (🔄) de la extensión jvf.io().
6. Listo. La extensión está actualizada.

### Actualización manual (equipos sin internet o restringidos)

Si tu equipo no tiene acceso a internet o no ves la notificación automática:

1. Desde un equipo con acceso, ir a **[Releases](https://github.com/Jhonvf20/jvf-io-chrome-advanced/releases/latest)**.
2. Descargar el `.zip` que corresponda a tu versión.
3. Transferir el archivo al equipo destino (USB, carpeta compartida, etc.).
4. Descomprimir con la contraseña en la **misma carpeta** de la extensión instalada (reemplazar archivos).
5. Ir a `chrome://extensions` y hacer click en el botón de **recarga** (🔄) de la extensión.

> Para verificar tu versión actual: abre el popup de jvf.io() y revisa el número de versión en la parte inferior.

---

## Solución de problemas

**La extensión no aparece después de instalar**
Verificar que se seleccionó la carpeta correcta (debe contener `manifest.json` directamente, no una subcarpeta).

**"Activar Utilidades" no hace nada**
Asegurarse de estar en una pestaña con una sesión de Siebel activa. La extensión solo funciona en páginas de Siebel.

**No veo la notificación de actualización**
La verificación ocurre cada 4 horas. Si necesitas verificar manualmente, quita y vuelve a cargar la extensión desde `chrome://extensions`.

**Error al descomprimir el .zip**
Verificar que estás usando la contraseña correcta para tu versión. Cada versión (expert, dev, funcional) tiene una contraseña diferente.

---

## Historial de versiones

Consultar la sección de **[Releases](https://github.com/Jhonvf20/jvf-io-chrome-advanced/releases)** para ver el historial completo de versiones y sus cambios.

---

*Desarrollado por Jhonnathan Varela Fonseca.*
*Copyright © 2026. Todos los derechos reservados.*
