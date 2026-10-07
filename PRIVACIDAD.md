# Política de privacidad de Game Over App

Última actualización: 07/10/2026

Game Over App es una aplicación de escritorio para Windows creada por **rulink007** para pilotos de simracing (iRacing). Esta política explica qué datos usa la app, para qué y dónde quedan.

**Resumen:** la app trabaja en tu PC. No tiene publicidad ni analítica, no vende datos y el desarrollador no recibe tu telemetría ni tus conversaciones. Solo se envían datos a otros servicios cuando tú usas una función que los necesita (lo explicamos abajo).

## 1. Datos que se quedan en tu PC

- **Telemetría y sesiones de iRacing:** la app lee la telemetría que iRacing deja en tu PC y guarda tus sesiones, informes, setups y la memoria de KITT en tu carpeta de datos (`%LOCALAPPDATA%\GameOverApp`, o la carpeta propia de la app si la instalaste desde la Microsoft Store).
- **Configuración y perfil:** tus ajustes, preferencias y tokens de los servicios que conectes. Los tokens se guardan en tu PC y, cuando Windows lo permite, cifrados con tu usuario.
- **Asistentes con IA (Lola y KITT):** usan un modelo de IA que se ejecuta **en tu propio PC** (Ollama). Tus preguntas y sus respuestas no salen de tu PC.
- **Registros de errores:** se guardan en la carpeta `logs` de tu carpeta de datos para poder diagnosticar fallos. No se envían a nadie salvo que tú los compartas.

## 2. Datos que se envían a otros servicios (solo si usas esa función)

| Función | A quién | Qué se envía |
|---|---|---|
| Órdenes por voz (micrófono) | Google (reconocimiento de voz) | El audio de la frase que dices mientras la app escucha, para convertirlo en texto. La app no guarda grabaciones. Puedes apagar el micrófono en la app. |
| Licencia PRO | Lemon Squeezy | Tu clave de licencia y un nombre de equipo (nombre del PC y un código anónimo) para activarla y comprobarla. |
| Compra de PRO | Lemon Squeezy (vendedor oficial) | Lo que pides en el pago (nombre, correo, país y método de pago). Lo gestiona Lemon Squeezy según su propia política de privacidad. El desarrollador ve el nombre y el correo del comprador para dar soporte. |
| Twitch, Spotify, Discord, Garage 61, API de iRacing, Trading Paints | El servicio que conectes | Lo necesario para esa función con los permisos que tú concedes (por ejemplo, leer el chat de tu canal o controlar tu música). Puedes desconectarlos cuando quieras. |
| Webhook de Discord | Tu servidor de Discord | El resumen de tu sesión (piloto, circuito, posición y tiempos), solo si pones tu webhook. |
| Imágenes y mapas | Servidores públicos de iRacing y de mapas por satélite | Solo la petición de la imagen (como cualquier navegador: tu dirección IP). |
| Copia en la nube (opcional) | Tu OneDrive, Google Drive o Dropbox | Tus datos de la app, copiados a tu carpeta sincronizada. La subida la hace tu propio cliente. |
| Móvil o tablet (opcional, apagado por defecto) | Tu red local | Los datos de la carrera en directo, solo dentro de tu Wi-Fi y con PIN. |
| Reportar contenido de la IA | El desarrollador, por correo | Solo si pulsas «Reportar»: se abre tu correo con la respuesta reportada y tu comentario. Tú decides si lo envías. |

## 3. Cómo usamos los datos

Solo para que funcione lo que pides: overlays, spotter, análisis de KITT, asistentes, licencia y soporte. No usamos tus datos para publicidad ni hacemos perfiles.

## 4. Tus opciones

- Apagar el micrófono, los asistentes y cada servicio conectado desde la propia app.
- Liberar la licencia de tu PC en **PERFIL › LICENCIA**.
- Borrar tus datos: desinstala la app y borra la carpeta `%LOCALAPPDATA%\GameOverApp` y `%APPDATA%\GameOverApp`.
- Pedir información o el borrado de los datos de tu compra escribiendo a **jcsrul@hotmail.com**.

## 5. Menores

La app no está dirigida a menores de 13 años y no recoge datos de ellos a sabiendas.

## 6. Cambios y contacto

Si esta política cambia, se actualizará aquí con su fecha. Para cualquier duda: **jcsrul@hotmail.com**.
