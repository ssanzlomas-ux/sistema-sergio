# 📋 INSTRUCCIONES: Subir a GitHub Pages

## Paso 1: Crear Repositorio en GitHub

1. Ve a: https://github.com/new
2. Configuración:
   - **Repository name:** `sistema-sergio`
   - **Description:** Sistema personalizado de mejora 2026
   - **Public** ✓ (debe ser público para GitHub Pages gratis)
   - **NO marques** "Add a README" (ya lo tenemos)
3. Click en **"Create repository"**

---

## Paso 2: Subir Archivos

### Opción A: Desde la Web (Más Fácil)

1. En tu nuevo repo, click **"uploading an existing file"**
2. Arrastra estos archivos desde `C:\Users\ssanz\Desktop\sistema-sergio\`:
   - `index.html` ← **IMPORTANTE: Este es el principal**
   - `README.md`
   - `.gitignore`
3. Commit message: "Primera versión del sistema"
4. Click **"Commit changes"**

### Opción B: Con Git (Si tienes instalado)

Abre PowerShell en `C:\Users\ssanz\Desktop\sistema-sergio\`:

```powershell
git init
git add index.html README.md .gitignore
git commit -m "Primera versión del sistema"
git branch -M main
git remote add origin https://github.com/TU-USUARIO/sistema-sergio.git
git push -u origin main
```

---

## Paso 3: Activar GitHub Pages

1. En tu repo, ve a **Settings** (arriba derecha)
2. En el menú izquierdo, click **"Pages"**
3. Configuración:
   - **Source:** Deploy from a branch
   - **Branch:** `main` 
   - **Folder:** `/ (root)`
4. Click **"Save"**
5. ⏱️ Espera 1-2 minutos
6. **Refresca la página** → Verás un mensaje verde:
   ```
   Your site is live at https://tu-usuario.github.io/sistema-sergio/
   ```

---

## Paso 4: Acceder a tu Sistema

Tu URL será:
```
https://TU-USUARIO.github.io/sistema-sergio/
```

**Reemplaza `TU-USUARIO`** con tu nombre de usuario de GitHub.

**Ejemplo:**
- Usuario: `sergiosanz`
- URL: `https://sergiosanz.github.io/sistema-sergio/`

---

## ✅ Verificar que Funciona

1. Abre la URL en tu navegador
2. Deberías ver el sistema completo funcionando
3. Prueba las pestañas (Dashboard, Semana 1, etc.)
4. Prueba marcar algo en "Hoy" → Se guarda automáticamente
5. **Guarda la URL en favoritos** o pantalla de inicio móvil

---

## 📱 Usar desde Móvil

### iPhone:
1. Abre Safari
2. Ve a tu URL: `https://tu-usuario.github.io/sistema-sergio/`
3. Toca botón "Compartir" (cuadro con flecha)
4. Scroll down → **"Añadir a pantalla de inicio"**
5. ¡Tendrás un icono como app!

### Android:
1. Abre Chrome
2. Ve a tu URL
3. Menú (3 puntos) → **"Añadir a pantalla de inicio"**
4. ¡Listo!

---

## 🔄 Actualizar en el Futuro

Si haces cambios en `index.html`:

1. Ve a tu repo en GitHub
2. Click en `index.html`
3. Click en el lápiz (Edit)
4. Pega el nuevo código
5. Commit changes
6. ⏱️ Espera 1-2 min → Cambios en vivo

---

## ❓ Problemas Comunes

**"404 Not Found"**
→ Espera 2-3 minutos más. GitHub Pages tarda en desplegar.

**"No se ve nada"**
→ Verifica que el archivo se llama `index.html` (no `app.html`)

**"Los datos no se guardan"**
→ Normal. LocalStorage es local del navegador. Cada dispositivo tiene sus propios datos.

---

## 🎯 Siguiente Paso

¡Crea tu repo y sube los archivos! 

Cuando tengas tu URL, compártela y podrás acceder desde cualquier lugar.
