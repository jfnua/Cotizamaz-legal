# Política de Privacidad — Cotiza+

**Última actualización:** 19 de noviembre de 2026  
**Aplicación:** Cotiza+ (Cotizamaz)  
**Versión web:** [privacy-policy.html](privacy-policy.html)

---

## 1. Principio Fundamental: Privacidad y Arquitectura Local (Offline-First)

**Cotiza+ está diseñada bajo el principio de almacenamiento local prioritario («offline-first» y «local-first»):**

1. **Sin servidores externos de negocio**: Toda la información comercial que registras en la Aplicación (nombres de clientes, números de teléfono, direcciones, catálogos de productos y servicios, precios, partidas, cotizaciones, notas, términos, folios y registros de pagos) se almacena **estrictamente de forma local en tu propio dispositivo** mediante una base de datos SQLite segura dentro del entorno protegido (*sandbox*) del sistema operativo.
2. **Sin cuentas obligatorias**: La Aplicación no te obliga a crear una cuenta, iniciar sesión ni proporcionar credenciales personales o bancarias para operar.
3. **Control total de tus datos**: Nosotros (los desarrolladores de Cotiza+) **no tenemos acceso, no recopilamos, no transferimos, no sincronizamos ni comercializamos** ninguna base de datos ni documento generado por los usuarios.

---

## 2. Publicidad de Terceros (Google AdMob)

La Aplicación integra el SDK oficial de **Google Mobile Ads** de Google LLC («Google AdMob») para mostrar anuncios estáticos (banners) y anuncios a pantalla completa (intersticiales de video o imagen) con frecuencia controlada.

### Qué información recopila Google AdMob:
Para servir anuncios relevantes y prevenir el fraude publicitario, el SDK de Google puede recopilar de forma automática cierta información técnica del dispositivo:
- **Identificadores publicitarios**: Identificador de publicidad de Google (GAID en Android) o Identificador para anunciantes (IDFA en iOS).
- **Dirección IP y ubicación aproximada** (a nivel de ciudad o país, no GPS exacto).
- **Métricas de interacción publicitaria**: Impresiones de anuncios, clics e información de diagnóstico de fallos (*crash logs*).

El tratamiento de estos datos por parte de Google se rige de forma independiente por las políticas de privacidad de Google:
- **Política de Privacidad de Google**: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Cómo utiliza Google la información de sitios o apps**: [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)

Puedes restablecer o deshabilitar la personalización de anuncios en cualquier momento desde los ajustes de tu teléfono (*Ajustes > Google > Anuncios* en Android, o *Ajustes > Privacidad > Rastreo* en iOS).

---

## 3. Permisos del Dispositivo y su Finalidad

Cotiza+ solicita únicamente los permisos estrictamente indispensables para brindar sus funciones de cotización y catálogo:

| Permiso | Plataforma | Finalidad |
|---|---|---|
| **Acceso a Fotos y Galería** (`READ_MEDIA_IMAGES` / Selector del sistema) | Android / iOS | Permite seleccionar el logotipo de tu negocio y fotografías de productos/servicios para adjuntarlas a tus cotizaciones y catálogos. La app no inspecciona otras fotografías fuera de las seleccionadas conscientemente por ti. |
| **Notificaciones Locales** (`POST_NOTIFICATIONS`) | Android / iOS | Permite enviar alertas y recordatorios programados en tu propio dispositivo (cotizaciones próximas a vencer y cobros pendientes). Estas notificaciones se generan y procesan 100% de manera local; no provienen de servidores de mensajería *push* remotos ni se utilizan para publicidad. |
| **Llamadas y Mensajería Externa** | Android / iOS | Al tocar sobre el teléfono de un cliente, la app invoca el marcador telefónico del sistema o la aplicación externa de WhatsApp mediante enlaces estándar (`tel:` / `wa.me`). Cotiza+ no accede a tu libreta de contactos general ni lee tus conversaciones privadas. |
| **Acceso a Red e Internet** (`INTERNET`, `ACCESS_NETWORK_STATE`) | Android | Utilizado exclusivamente por el SDK de Google Mobile Ads para descargar los bloques de anuncios cuando hay conexión a internet disponible. Toda la lógica de cotizaciones continúa funcionando plenamente sin conexión. |

---

## 4. Respaldo y Transferencia de Información

La Aplicación incluye una herramienta de **Respaldo Local** que te permite exportar todos tus datos e imágenes en un archivo comprimido (`.zip`).
- Eres el único propietario y responsable de dicho archivo.
- Si decides compartirlo o guardarlo (por ejemplo, enviándolo a Google Drive, WhatsApp o tu correo), la seguridad y transmisión del archivo dependerán del canal de terceros que elijas voluntariamente.

---

## 5. Retención y Eliminación de Datos

Dado que todos tus datos residen únicamente en tu dispositivo:
- Puedes modificar o eliminar cualquier registro (clientes, partidas, cotizaciones, pagos) en cualquier momento desde la interfaz de la Aplicación.
- La aplicación incluye una sección dedicada en **Más > Eliminación de datos** con un botón de borrado inmediato y total.
- Al **desinstalar la Aplicación** o al presionar **«Borrar datos»** en la configuración de aplicaciones de tu teléfono, todos los datos almacenados en la base de datos local y los archivos temporales se eliminarán de forma definitiva e irreversible de la memoria de tu dispositivo.

Consulta la guía detallada en [data-deletion.html](data-deletion.html) o [DATA_DELETION.md](DATA_DELETION.md).

---

## 6. Privacidad de Menores

La Aplicación está dirigida a profesionales, trabajadores independientes y pequeños negocios. No recopilamos conscientemente información personal de menores de 13 años (o la edad mínima legal en tu jurisdicción).

---

## 7. Modificaciones a esta Política

Podemos actualizar esta Política de Privacidad periódicamente para reflejar mejoras en la Aplicación o cambios normativos. Cualquier modificación entrará en vigor al momento de su publicación. Te recomendamos revisar esta política con regularidad.

---

## 8. Contacto y Soporte

Si tienes dudas, preguntas o comentarios sobre esta Política de Privacidad o sobre el funcionamiento de Cotiza+, puedes contactarnos en:

- **Desarrollador / Soporte**: Soporte Cotiza+ (Cotizamaz)
- **Correo electrónico**: [soporte@nullbros.com](mailto:soporte@nullbros.com)
