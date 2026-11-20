# Cotiza+ — Documentación Legal y Privacidad

Repositorio estático preparado para publicar en **GitHub Pages** la documentación legal, política de privacidad y política de eliminación de datos de **Cotiza+ (Cotizamaz)**.

---

## 📁 Contenido del Repositorio

| Archivo | Descripción | Uso en Google Play Console |
|---|---|---|
| `index.html` | Portal web principal con acceso a ambas políticas | Página de inicio del sitio legal |
| `privacy-policy.html` | Política de Privacidad completa (HTML responsivo) | URL de Política de Privacidad |
| `data-deletion.html` | Guía oficial de Eliminación de Datos (HTML responsivo) | URL de Solicitud de Eliminación de Datos |
| `PRIVACY_POLICY.md` | Versión Markdown de la Política de Privacidad | Documentación legible en GitHub |
| `DATA_DELETION.md` | Versión Markdown de Eliminación de Datos | Documentación legible en GitHub |

---

## 🚀 Cómo publicar este repositorio en GitHub Pages (Paso a Paso)

### Paso 1: Crear un nuevo repositorio en GitHub
1. Inicia sesión en [GitHub](https://github.com/new).
2. Crea un repositorio público nuevo con el nombre que prefieras (por ejemplo: `cotizamaz-legal` o `cotiza-legal`).
3. Deja desmarcadas las opciones de inicializar con README (lo subiremos desde aquí).

### Paso 2: Subir los archivos desde tu computadora
Abre una terminal en esta carpeta (`cotizamaz-legal`) y ejecuta:

```bash
git init
git add .
git commit -m "feat: initial commit with privacy policy and data deletion pages"
git branch -M main
git remote add origin https://github.com/<TU_USUARIO>/<NOMBRE_DE_TU_REPOSITORIO>.git
git push -u origin main
```

*(Reemplaza `<TU_USUARIO>` y `<NOMBRE_DE_TU_REPOSITORIO>` con tus datos de GitHub).*

### Paso 3: Activar GitHub Pages
1. En tu nuevo repositorio de GitHub, haz clic en **Settings** (pestaña superior).
2. En el menú lateral izquierdo, haz clic en **Pages**.
3. En la sección **Build and deployment > Source**, selecciona **«Deploy from a branch»**.
4. En **Branch**, selecciona `main` y en la carpeta deja `/(root)`.
5. Haz clic en **Save**.

En aproximadamente 1 o 2 minutos, GitHub Pages publicará tu sitio web automáticamente.

---

## 🌐 URLs Resultantes para Google Play Console

Una vez activado GitHub Pages con tu usuario y nombre de repositorio:

- **Portal Principal:**  
  `https://<TU_USUARIO>.github.io/<NOMBRE_DE_TU_REPOSITORIO>/`
- **URL de Política de Privacidad (para la ficha de Play Store):**  
  `https://<TU_USUARIO>.github.io/<NOMBRE_DE_TU_REPOSITORIO>/privacy-policy.html`
- **URL de Eliminación de Datos (para Data Safety / Seguridad de los datos):**  
  `https://<TU_USUARIO>.github.io/<NOMBRE_DE_TU_REPOSITORIO>/data-deletion.html`

---

## 📧 Contacto

- Correo: soporte@nullbros.com
