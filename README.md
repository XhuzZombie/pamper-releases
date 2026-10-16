# Pamper para Windows

Pamper es un asistente local con una esfera dorada, conversación por voz y texto, consultas rápidas y ayuda sobre lo que aparece en pantalla. Este repositorio distribuye **solo instaladores y actualizaciones**. El código fuente se conserva en un repositorio privado.

**[Descargar la versión más reciente](https://github.com/XhuzZombie/pamper-releases/releases/latest)**

## Instalar

1. Descarga `Pamper-Setup-<versión>.exe` de la publicación y abre el instalador.
2. Pulsa **Instalar Pamper**. Si hay una versión publicada más reciente y conexión, el setup la descarga e instala automáticamente. Sin conexión puede instalar la versión incluida.
3. Abre Pamper y completa la preparación de los modelos, la voz y la prueba de activación.

No hace falta instalar Python, Node o .NET por separado, ni usar permisos de administrador. Necesitas Windows 10 versión 2004 o posterior / Windows 11 **x64**, micrófono para la voz y varios gigabytes libres para los modelos. La preparación inicial requiere Internet. Después, la conversación y la voz locales pueden funcionar sin conexión; las búsquedas y la meteorología sí necesitan Internet.

El rendimiento depende del ordenador y de las aplicaciones abiertas. No se garantiza una latencia fija ni reconocimiento perfecto. El instalador aún no tiene certificado Authenticode comercial; Windows puede mostrar una advertencia de reputación.

## Qué puedes pedirle

- «Crea un archivo de texto»: pide el nombre, el contenido y dónde guardarlo. Puede escribirlo en Escritorio o Documentos y editar físicamente archivos `.txt`.
- «Abre Chrome», «abre Discord» o «abre Fortnite»: busca la aplicación instalada por su nombre habitual. Para servicios conocidos que no estén instalados, ofrece abrir el sitio oficial en el navegador y espera tu confirmación.
- Consultas breves, búsqueda de información, resumen y ayuda contextual sobre la pantalla.
- Cambios de modo, interrupción de la respuesta y cierre de la conversación por voz.

El nombre y la voz son configurables. Pamper muestra las tareas que está realizando y pide confirmación antes de acciones que puedan sustituir contenido o causar pérdidas. Los consejos e indicaciones visuales acompañan su explicación.

**Google Docs:** se ha preparado la edición de texto, fuente y tamaño, pero el recorrido dentro de un documento real sigue pendiente de validación interactiva. La herramienta de pruebas bloqueó esa comprobación porque no pudo verificar la URL del navegador. Las pruebas de edición física se realizaron en un editor aislado; no se garantiza todavía el mismo resultado en cualquier documento o aplicación.

## Modos

- **Normal:** conversación y ayuda al pedirla, con uso moderado de CPU.
- **Activo:** permite dedicar más CPU al trabajo y ofrece ayuda contextual. Con la configuración predeterminada comparte el modelo local de 2B con Normal; la diferencia no consiste en cambiar a otro modelo mayor.
- **Bajo consumo:** libera los modelos y detiene la escucha y la observación. Se reactiva desde la aplicación o mediante su atajo.
- **Off:** cierra Pamper. Para volver a usarlo hay que abrirlo.

## Actualizaciones

Al abrirse, Pamper busca actualizaciones automáticamente. Si hay una disponible, la descarga y muestra una ventana con progreso mientras se instala. También comprueba periódicamente mientras está abierto y aplica una actualización preparada cuando está libre. No tienes que buscar versiones ni aceptar cada actualización.

La firma criptográfica y la huella del paquete se verifican antes de instalarlo. Si la comprobación o el arranque fallan, se conserva o recupera la versión anterior. Los modelos y las preferencias se mantienen entre versiones. En modo Off no hay procesos de Pamper comprobando actualizaciones.

Puedes desinstalarlo desde **Configuración → Aplicaciones** y elegir si quieres conservar tus datos y modelos.

## Privacidad y componentes

La inferencia, la voz y el análisis de pantalla se ejecutan en el ordenador. Las funciones en línea contactan los servicios necesarios para buscar, consultar el tiempo o descargar recursos. Pamper no guarda contraseñas ni automatiza inicios de sesión. Las peticiones avanzadas para ChatGPT se preparan para que tú las revises y envíes.

Las preferencias y las pruebas mejoran el funcionamiento de la aplicación; no reentrenan automáticamente el modelo. El instalador incluye `THIRD_PARTY_NOTICES.md` y una carpeta `Licenses` con las condiciones de los componentes utilizados. Los modelos y motores descargados conservan sus licencias originales.
