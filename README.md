# Guía Apizaco & Tlaxcala — Comer Bonito

Una guía interactiva y mapa para comer bonito en Apizaco, Tlaxcala Capital y sus alrededores.

## 🚀 Desarrollo local

1. **Instalar dependencias:**
   ```bash
   npm install
   ```

2. **Iniciar servidor de desarrollo:**
   ```bash
   npm run dev
   ```
   Abre [http://localhost:5173](http://localhost:5173) en tu navegador.

3. **Construir para producción:**
   ```bash
   npm run build
   ```
   Los archivos optimizados se generarán en la carpeta `dist/`.

4. **Previsualizar construcción de producción:**
   ```bash
   npm run preview
   ```

---

## 🌐 Subir a Vercel

Este proyecto está listo para ser desplegado en [Vercel](https://vercel.com/):

### Opción 1: Con Git (GitHub, GitLab, Bitbucket)
1. Crea un nuevo repositorio en GitHub y sube tu código:
   ```bash
   git init
   git add .
   git commit -m "Commit inicial"
   git branch -M main
   git remote add origin <TU-URL-DEL-REPOSITORIO>
   git push -u origin main
   ```
2. Entra a tu panel de Vercel y haz clic en **"Add New Project"**.
3. Importa el repositorio de GitHub.
4. Vercel detectará automáticamente que es un proyecto **Vite** y configurará:
   - **Build Command:** `npm run build`
   - **Output Directory:** `dist`
5. Haz clic en **Deploy**.

### Opción 2: Usando Vercel CLI
Si tienes Vercel CLI instalado en tu terminal:
```bash
npx vercel
```
Sigue las instrucciones en consola para desplegar directamente.
