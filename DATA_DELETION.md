# Política de Eliminación de Datos — Cotiza+

**Última actualización:** 19 de noviembre de 2026  
**Aplicación:** Cotiza+ (Cotizamaz)  
**Versión web:** [data-deletion.html](data-deletion.html)

---

## 1. Principio Fundamental: Privacidad 100% Local (Offline-First)

**Cotiza+** está diseñada bajo el principio de almacenamiento local prioritario (*offline-first*):

1. **Sin servidores externos ni cuentas en la nube**: Toda la información comercial que registras (clientes, cotizaciones, partidas, folios, listas de precios, descuentos, impuestos, pagos, comprobantes, logotipos y fotografías) se almacena **estrictamente de forma local en tu propio dispositivo móvil** mediante una base de datos SQLite segura dentro del entorno protegido (*sandbox*) de tu sistema operativo.
2. **Sin cuentas de usuario obligatorias**: No recopilamos credenciales, contraseñas ni registros de inicio de sesión.
3. **Control total**: Nosotros no tenemos acceso, no transmitimos, no sincronizamos ni comercializamos tu información comercial.

---

## 2. Datos Almacenados por la Aplicación

- **Datos comerciales y de clientes**: Nombres, domicilios, números telefónicos, correos electrónicos, catálogos de productos y servicios, precios, partidas y cotizaciones.
- **Registros de cobro**: Abonos, fechas, montos y métodos de pago registrados en tus cotizaciones.
- **Archivos multimedia**: Logotipo de empresa y fotos de catálogo almacenadas en el almacenamiento privado de la app.
- **Identificadores técnicos/publicitarios**: Recopilados de manera anónima y no vinculada por el SDK oficial de Google AdMob para entregar anuncios y prevenir fraudes (conforme a la [Política de Privacidad de Google](https://policies.google.com/privacy)).

---

## 3. Instrucciones para Eliminar tus Datos

El usuario dispone de tres métodos directos para eliminar por completo y de forma irreversible sus datos:

### Método 1: Desde la propia aplicación Cotiza+ (Recomendado)
1. Abre **Cotiza+** en tu teléfono.
2. Ve a la pestaña **Más** en la barra de navegación inferior.
3. Toca la opción **«Eliminación de datos»**.
4. Pulsa el botón rojo **«Eliminar todos mis datos»**.
5. Confirma la acción en el diálogo emergente seleccionando **«Sí, eliminar todo»**.

> **Efecto:** Se purgan todas las tablas de SQLite (clientes, cotizaciones, partidas, pagos, catálogo), se eliminan todas las imágenes locales en disco y se restablece la aplicación a su estado inicial de fábrica.

### Método 2: Desde los Ajustes del Sistema Operativo Android
1. Abre los **Ajustes** o **Configuración** de tu teléfono Android.
2. Selecciona **Aplicaciones** > **Cotiza+**.
3. Ingresa a **Almacenamiento y caché**.
4. Pulsa **«Borrar almacenamiento»** o **«Borrar datos»** y confirma.

> **Efecto:** Android borra de inmediato todos los archivos locales y bases de datos asociadas a la app.

### Método 3: Desinstalando la Aplicación
1. Mantén presionado el icono de **Cotiza+** en tu pantalla de inicio.
2. Selecciona **«Desinstalar»** (o hazlo desde Google Play Store).

> **Efecto:** El sistema operativo purga inmediatamente el contenedor protegido de la aplicación y todos los archivos generados.

---

## 4. Retención de Datos

Dado que Cotiza+ **no almacena tus datos en servidores remotos**, la eliminación local es **instantánea, total y definitiva**, sin período de retención ni copias residuales en la nube.

Si creaste copias de seguridad manuales en archivos `.zip` y las transferiste a servicios de terceros (como Google Drive, WhatsApp o correo electrónico), tú mantienes el control exclusivo sobre dichos archivos en tu cuenta personal y puedes eliminarlos en cualquier momento desde dichos servicios.

---

## 5. Contacto y Soporte

Para cualquier duda, asistencia o solicitud sobre tus datos, puedes contactarnos en:
- **Correo electrónico:** [soporte@nullbros.com](mailto:soporte@nullbros.com)
