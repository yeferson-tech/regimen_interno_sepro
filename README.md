# SEPRO Control de Personal — iPhone y Android

Herramienta HTML autocontenida para el funcionario de régimen interno. Permite consolidar los partes de GINAD, GUTUR, UBIC, GUPRO y SEPRO, identificar descuadres y preparar el PIN para compartir por WhatsApp. No se necesita que cada grupo se registre en la aplicación.

**Plataforma creada por el ingeniero Yeferson Payares Ayala.** El crédito muestra el año actual del dispositivo.

## Cómo abrirla en iPhone

**Para que funcionen los cálculos, abra la página `index.html` publicada en un sitio HTTPS institucional autorizado, desde Safari.** La vista previa de archivos HTML en la aplicación Archivos, WhatsApp o Quick Look de iPhone puede mostrar una versión estática y no ejecutar JavaScript. Si eso ocurre, esta versión presenta un aviso claro de que la aplicación no está en ejecución. El propio código HTML no puede obligar a esas vistas previas a ejecutar scripts.

En Android puede abrirse desde el mismo enlace HTTPS en Chrome. En muchos dispositivos Android también puede ejecutarse como archivo local. En computador funciona desde un navegador moderno compatible.

**Importante:** no publique la aplicación ni datos operativos en páginas públicas o visualizadores de terceros sin autorización. Para uso institucional, el servidor y el acceso deben gestionarse conforme a las políticas aplicables.

## Mejoras de esta versión móvil

- Diseño adaptado para iPhone de 320 a 430 px y otras pantallas, sin necesidad de desplazamiento horizontal.
- Etiquetas completas por concepto y casillas separadas claramente para oficiales, nivel ejecutivo y patrulleros.
- Resultado de cada grupo visible justo después de calcular, con fuerza efectiva, novedades y fuerza disponible.
- Acceso rápido a **Resumen**, **Cargar partes** y **PIN** desde la barra inferior del móvil.
- Acceso a compartir desde el menú nativo del teléfono cuando el navegador lo permite; copia manual cuando no.
- Aviso para vistas previas de iOS sin ejecución de JavaScript.

## Uso diario

1. Seleccione la fecha del parte (por defecto mañana) y el destinatario.
2. Seleccione el grupo y pegue su mensaje de WhatsApp, completo o abreviado. Pulse **Calcular este grupo**.
3. Revise el resultado inmediato y las diferencias detectadas. Haga lo mismo con los cinco grupos.
4. Escriba las actividades y complete los datos de quien reporta.
5. Copie o comparta el PIN validado. No se permite copiar si quedan descuadres o datos obligatorios pendientes.
6. Al terminar, pulse **Ya envié el PIN · borrar datos**.

El saludo puede ser automático o manual: **00:00–11:59, Buenos días; 12:00–18:59, Buenas tardes; 19:00–23:59, Buenas noches**. Se utiliza la hora local del dispositivo.

## Privacidad y limitaciones

No hay base de datos, cuentas ni envío automático a servidores. Los datos se mantienen en la memoria de la página mientras se utiliza y se descartan al recargarla, cerrarla o pulsar borrar. Esto no borra las copias que existan en WhatsApp, el portapapeles, capturas de pantalla o programas ajenos. El archivo contiene el código, no los partes ingresados durante el régimen.

**Pruebas:** se validaron cálculos, mensajes abreviados, avisos de inconsistencias, copia alternativa, limpieza de sesión y diseño responsivo en Chromium con tamaños de pantalla móviles y de escritorio. No reemplaza una prueba final en un dispositivo físico con Safari iOS.
