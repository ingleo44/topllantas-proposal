# 🚀 Setup Rápido - TopLlantas AI GitHub Pages

## ✅ Archivos Jekyll Creados

¡Perfecto! Ya tienes todos los archivos Jekyll necesarios para publicar tu propuesta profesional:

### 📁 Estructura Creada:
```
├── _config.yml           # Configuración principal de Jekyll
├── Gemfile               # Dependencias de Ruby/Jekyll
├── _layouts/             # Plantillas de página
│   ├── default.html      # Layout principal
│   └── home.html         # Layout para página de inicio
├── _includes/            # Componentes reutilizables
│   ├── head.html         # Meta tags y CSS
│   ├── header.html       # Navegación superior
│   ├── footer.html       # Pie de página
│   ├── navigation.html   # Navegación entre páginas
│   └── social.html       # Enlaces sociales
├── assets/
│   └── main.css          # Estilos personalizados TopLlantas
└── .github/workflows/
    └── jekyll-gh-pages.yml # Deploy automático
```

## 🔧 Próximos Pasos:

### 1. **Crear Repositorio en GitHub** (5 min)
```bash
# Ve a github.com y crea un nuevo repositorio público
# Nombre sugerido: topllantas-ai-proposal
# Descripción: "Propuesta de Transformación Digital TopLlantas con Agentes de AI"
```

### 2. **Subir Archivos** (3 min)
```bash
# En tu terminal:
git init
git add .
git commit -m "🚀 Initial commit: TopLlantas AI Proposal with Jekyll"
git branch -M main
git remote add origin https://github.com/TU_USERNAME/topllantas-ai-proposal.git
git push -u origin main
```

### 3. **Activar GitHub Pages** (2 min)
1. Ve a **Settings** de tu repositorio
2. Scroll hasta **Pages** (lado izquierdo)
3. **Source:** Deploy from a branch
4. **Branch:** main / (root)
5. **Save**

### 4. **Personalizar Configuración** (Opcional)
Edita `_config.yml` y cambia:
```yaml
# Línea 9-10: Cambiar por tu GitHub username
url: "https://TU_USERNAME.github.io"
baseurl: "/topllantas-ai-proposal"

# Líneas con redes sociales si las tienes
```

## 🎯 **Resultado Final:**

Tu propuesta estará disponible en:
```
https://TU_USERNAME.github.io/topllantas-ai-proposal
```

### ✨ **Características Incluidas:**

- **🎨 Diseño Profesional** con colores corporativos TopLlantas
- **📱 Responsive** - Se ve bien en móviles y tablets
- **🔍 SEO Optimizado** con meta tags y Open Graph
- **⚡ Carga Rápida** optimizado para GitHub Pages
- **📊 Navegación Intuitiva** entre todos los documentos
- **🔄 Deploy Automático** cada vez que hagas cambios

### 🔧 **Para Desarrollo Local** (Opcional):
```bash
# Si quieres probar localmente antes de subir
bundle install
bundle exec jekyll serve

# Tu sitio estará en: http://localhost:4000
```

## 🎨 **Personalización Avanzada:**

### Agregar Logo de TopLlantas:
1. Crear carpeta: `assets/images/`
2. Subir logo como: `topllantas-logo.png`
3. Se mostrará automáticamente en el header

### Cambiar Colores:
Edita las variables CSS en `assets/main.css`:
```css
:root {
  --topllantas-primary: #TU_COLOR_PRIMARIO;
  --topllantas-secondary: #TU_COLOR_SECUNDARIO;
}
```

## 📞 **¿Necesitas Ayuda?**

Si tienes algún problema:
1. Revisa que todos los archivos se subieron correctamente
2. Verifica que GitHub Pages esté activado
3. Espera 2-3 minutos para que se procese el primer deploy

## 🎉 **¡Listo para Impresionar!**

Tu propuesta de TopLlantas AI ahora tiene una presentación web profesional que puedes compartir directamente con clientes, inversionistas o el equipo directivo.

**URL a compartir:** `https://TU_USERNAME.github.io/topllantas-ai-proposal`
