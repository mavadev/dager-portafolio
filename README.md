<p align="center">
  <img alt="Expense Tracker Interface" src="https://github.com/user-attachments/assets/40d97034-427c-4488-94e7-65b45c4c05a0" />
</p>

> Interfaz oscura, dinámica y 100% responsiva con animaciones interactivas impulsadas por Framer Motion.

# Dager Portfolio 🐶🎸

### 📖 Descripción

**Dager Portfolio** es una aplicación web interactiva y moderna desarrollada con Next.js 15 (App Router), TypeScript / JavaScript y Tailwind CSS. Está concebida como un desafío y proyecto creativo inspirado en el universo, el contenido y el estilo único de Dog Dager (Mariano Atravesado), integrando animaciones fluidas, galerías visuales, secciones dinámicas y componentes interactivos.

---

### ✨ Características

- ⚡ **Next.js 15 (App Router):** Aprovechamiento de las últimas características del framework con renderizado optimizado y turbopack.
- ✨ **Animaciones Fluidas:** Transiciones y efectos visuales dinámicos integrados mediante Framer Motion.
- 🎨 **Diseño Temático Adaptativo:** Estética moderna en modo oscuro con componentes personalizados y tipografías cuidadas.
- 🖼️ **Galería Interactiva:** Secciones de poses exclusivas, canales, y componentes multimedia (react-image-gallery).
- 📱 **Diseño Full Responsive:** Experiencia de usuario optimizada para dispositivos móviles, tablets y escritorios.

---

### 🏗️ Arquitectura del proyecto

La aplicación sigue la estructura modular del App Router de Next.js, organizada por capas de componentes, secciones y datos estáticos:

```text
src/
├── app/
│   ├── fonts/          # Tipografías personalizadas (Geist)
│   ├── sections/       # Secciones principales de la landing (Hero, AboutMe, Canales, ConectaConmigo)
│   ├── globals.css     # Estilos globales y configuración de Tailwind
│   ├── layout.js       # Layout principal de la aplicación
│   └── page.js         # Página de inicio
├── components/         # Componentes UI reutilizables (Header, Footer, Menu, Loader, LumberGame)
├── data/               # Fuentes de datos estáticos (channels, menuData, socials)
├── lib/                # Utilidades generales (clsx, twMerge)
└── public/             # Recursos estáticos (imágenes de galería, canales y banners)
```

---

### 💻 Instalación local

**1. Clona el repositorio:**

```bash
git clone https://github.com/mavadev/dager-portfolio.git
cd dager-portfolio
```

**2. Instala las dependencias:**

```bash
npm install
```

**3. Ejecuta el servidor de desarrollo:**

```bash
npm run dev
```

**4. La aplicación estará disponible en: `http://localhost:3000`**

---

### 🌐 Despliegue & Producción

El proyecto está optimizado para desplegarse fácilmente en plataformas como **Netlify** o **Vercel**.

**Stack del Proyecto:**

[![Stack](https://skillicons.dev/icons?i=nextjs,tailwind)](https://skillicons.dev)

---

### 📄 Licencia

Este proyecto se distribuye bajo la licencia **MIT**.

Desarrollado con ❤️ por **Gianmarco Chistama**
