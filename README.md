# Nuestro Equipo - Website

Una página web moderna y minimalista que presenta los perfiles de nuestro equipo de 5 personas, junto con una galería de productos y un chatbot integrado.

## 🚀 Características

- **Diseño Minimalista**: Colores cálidos (verde thalo, terracota, tonos de bosque tropical)
- **Perfiles del Equipo**: 5 perfiles detallados con biografías y hobbies
- **Galería de Productos**: Comida asiática y equipamiento de senderismo
- **Chatbot Integrado**: Asistente virtual interactivo
- **Responsive Design**: Optimizado para todos los dispositivos
- **Navegación Suave**: Scroll suave entre secciones

## 🛠️ Tecnologías Utilizadas

- **Next.js 14**: Framework de React
- **TypeScript**: Tipado estático
- **Tailwind CSS**: Estilos utilitarios
- **Radix UI**: Componentes accesibles
- **Lucide React**: Iconos modernos

## 📦 Instalación y Desarrollo

1. **Clonar el repositorio**
\`\`\`bash
git clone <tu-repositorio>
cd team-profiles-website
\`\`\`

2. **Instalar dependencias**
\`\`\`bash
npm install
\`\`\`

3. **Ejecutar en desarrollo**
\`\`\`bash
npm run dev
\`\`\`

4. **Compilar para producción**
\`\`\`bash
npm run build
\`\`\`

## 🚀 Despliegue

### Vercel (Recomendado)
1. Conecta tu repositorio a Vercel
2. Vercel detectará automáticamente que es un proyecto Next.js
3. El despliegue se realizará automáticamente

### Netlify
1. Ejecuta `npm run build`
2. Sube la carpeta `out` a Netlify

### Otros Hostings
1. Ejecuta `npm run build`
2. Sube la carpeta `out` generada a tu hosting

## 📁 Estructura del Proyecto

\`\`\`
├── app/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
├── components/
│   ├── ui/
│   │   ├── button.tsx
│   │   ├── card.tsx
│   │   ├── badge.tsx
│   │   └── input.tsx
│   ├── navigation.tsx
│   ├── hero.tsx
│   ├── team-profiles.tsx
│   ├── product-gallery.tsx
│   ├── chatbot.tsx
│   └── footer.tsx
├── lib/
│   └── utils.ts
├── package.json
├── tailwind.config.ts
├── tsconfig.json
└── next.config.js
\`\`\`

## 🎨 Personalización

### Colores
Los colores del tema se pueden modificar en `tailwind.config.ts`:
- `thalo-green`: Verde principal
- `terracotta`: Color de acento
- `forest-light` y `forest-dark`: Tonos de bosque
- `warm-cream`: Fondo cálido

### Contenido
- **Perfiles**: Modifica el array `teamMembers` en `components/team-profiles.tsx`
- **Productos**: Actualiza el array `products` en `components/product-gallery.tsx`
- **Chatbot**: Personaliza las respuestas en `components/chatbot.tsx`

## 📱 Responsive Design

El sitio está optimizado para:
- 📱 Móviles (320px+)
- 📱 Tablets (768px+)
- 💻 Desktop (1024px+)
- 🖥️ Large screens (1280px+)

## 🤖 Chatbot

El chatbot incluye respuestas automáticas para:
- Información del equipo
- Consultas sobre productos
- Información de contacto
- Respuestas generales

## 📄 Licencia

Este proyecto está bajo la Licencia MIT.
\`\`\`

Archivo de configuración de ESLint:
