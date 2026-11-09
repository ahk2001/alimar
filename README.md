# Autoescuela Alimar — San Vicente del Raspeig (Alicante) 🚗🇪🇸

Sitio web oficial y portal de alta conversión para **Autoescuela Alimar** (Centro de Formación Campdrive S.L.), centro de formación vial homologado por la DGT (**Código Oficial: A 0830-01**) con más de 50 años de trayectoria (desde 1972) y circuito cerrado de prácticas propio en **San Vicente del Raspeig** (Alicante, España).

🌐 **Demo Online (GitHub Pages):** [https://ahk2001.github.io/alimar/](https://ahk2001.github.io/alimar/)  
📦 **Repositorio Oficial:** [https://github.com/ahk2001/alimar](https://github.com/ahk2001/alimar)

---

## 🌟 Características Principales

- **Identidad Corporativa Oficial:**
  - Logotipo original vectorial y rasterizado en alta resolución (`assets/logo.png`).
  - Favicon multirresolución oficial (`fivecon.webp`, `favicon.png`, `apple-touch-icon.png` y `favicon.ico`).
  - Paleta cromática corporativa: Azul Real Alimar (`#0020A2`), Amarillo Vial (`#FDE001`), Blanco Puro y Negro Superficie.
- **Diseño Editorial & UI/UX Premium:**
  - Tipografía jerárquica con **Inter Tight**, **Plus Jakarta Sans** y **JetBrains Mono**.
  - **Cards 2x2 Equilibradas:** Sección de Cualificación Profesional optimizada con distribución horizontal compacta, eliminando alturas excesivas.
  - **Catálogo Interactivo de Permisos DGT:** 9 tarjetas interactivas con íconos específicos por vehículo (coche, motos A1/A2/A, camiones, tráiler, autobús, remolques y reciclaje vial) con acordeón desplegable y filtros dinámicos.
  - **Los 3 Pilares del Método Formativo:** Tarjetas modernas con checklists de ventajas y micro-insignias.
- **Conversión Directa por WhatsApp:**
  - Botón flotante siempre visible y botones integrados en cada permiso y curso con enlaces directos al canal oficial (`+34 747 46 77 42`).
- **Rendimiento y Accesibilidad:**
  - Código HTML5 semántico puro sin dependencias pesadas.
  - Carga diferida (`lazy loading`) en imágenes de alta resolución.
  - Menú overlay full-screen responsive con animación fluida.

---

## 📁 Estructura del Proyecto

```text
alimar/
├── .github/
│   └── workflows/
│       └── deploy.yml               # Workflow de despliegue automatizado a GitHub Pages
├── assets/                          # Activos visuales, fotografías reales y logotipos
│   ├── apple-touch-icon.png         # Icono para dispositivos Apple iOS
│   ├── favicon.png                  # Favicon PNG de alta resolución
│   ├── favicon.svg                  # Favicon vectorial con placa L oficial DGT
│   ├── fivecon.webp                 # Favicon oficial en formato WebP moderno
│   ├── logo.png                     # Logotipo oficial recortado en alta resolución
│   ├── logo com fundo.png           # Versión original con fondo
│   ├── home.png                     # Imagen Open Graph para redes sociales
│   ├── coche-aealimar.jpg           # Audi Q3 en la pista propia de maniobras
│   ├── moto-aealimar.jpg            # Flota de motocicletas en circuito cerrado
│   ├── fachada-768x1365.jpg         # Fachada oficial en Calle Villafranqueza, 53
│   ├── recuperacion-puntos.jpg      # Aula presencial de Recuperación de Puntos DGT
│   ├── recuperacionpuntos.png       # Atención personalizada en secretaría
│   └── Captura de tela *.png        # Galería real de alumnos aprobados con la "L"
├── docs/                            # Documentación técnica y estratégica del proyecto
│   ├── dados.txt                    # Datos de contacto, teléfonos, redes y enlaces
│   └── dossie_autoescola.md         # Dossier estratégico de mercado, SEO y UI/UX
├── .gitignore                       # Filtro de archivos para Git
├── favicon.ico                      # Favicon raíz universal para navegadores
├── index.html                       # Página web principal de producción
└── README.md                        # Documentación técnica y general del repositorio
```

---

## 🚀 Cómo Visualizar Localmente

Basta con abrir el archivo `index.html` en cualquier navegador web moderno (Google Chrome, Microsoft Edge, Mozilla Firefox o Safari):
1. Haga doble clic sobre `index.html` en el explorador de archivos; o
2. Abra una terminal en esta carpeta y ejecute un servidor local rápido:
   ```bash
   python -m http.server 8000
   ```
   Luego abra [http://localhost:8000](http://localhost:8000) en su navegador.

---

## 🌐 Despliegue en GitHub Pages

Este repositorio cuenta con un flujo automatizado de GitHub Actions (`.github/workflows/deploy.yml`):
1. Vaya a la pestaña **Settings** del repositorio en GitHub: [https://github.com/ahk2001/alimar/settings/pages](https://github.com/ahk2001/alimar/settings/pages).
2. En la sección **Build and deployment > Source**, seleccione **GitHub Actions**.
3. El despliegue se ejecutará automáticamente tras cada `git push` a la rama `main`.
4. El sitio estará disponible en:
   👉 **`https://ahk2001.github.io/alimar/`**

---

## 📍 Datos de Contacto y Sede Oficial

- **Sede Principal:** Calle Villafranqueza, 53 (esquina Calle Doctor Marañón, 7-9), 03690 San Vicente del Raspeig (Alicante, España).
- **Código DGT:** A 0830-01 (Jefatura Provincial de Tráfico de Alicante).
- **WhatsApp Oficial:** [+34 747 46 77 42](https://wa.me/34747467742)
- **Teléfono Fijo:** +34 965 20 15 66
- **E-mail:** info@autoescuelaalimar.com
- **Sitio Web Oficial:** [https://autoescuelaalimar.com/](https://autoescuelaalimar.com/)
- **Instagram:** [@alimar_autoescuelas](https://www.instagram.com/alimar_autoescuelas/)
