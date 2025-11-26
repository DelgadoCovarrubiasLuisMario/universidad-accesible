# Universidad Accesible - Sitio Web

Sitio web accesible para una universidad, diseñado siguiendo las pautas WCAG 2.1 para garantizar la accesibilidad web.

## 📋 Descripción

Este proyecto es un sitio web de tres páginas que demuestra prácticas de accesibilidad web implementando varios criterios de éxito de WCAG 2.1. El sitio incluye:

- **Página principal (index.html)**: Información general sobre la universidad
- **Programas (programas.html)**: Información sobre programas académicos
- **Contacto (contacto.html)**: Formulario de contacto accesible

## ✨ Características de Accesibilidad

### Criterios de Éxito WCAG Implementados

1. **SC 1.1.1 Non-text Content (Level A)**
   - Todas las imágenes tienen texto alternativo descriptivo
   - Imágenes decorativas marcadas con `aria-hidden="true"`

2. **SC 1.2.2 Captions (Prerecorded) (Level A)**
   - Video de YouTube con subtítulos habilitados automáticamente
   - Descripción de audio proporcionada

3. **SC 2.4.4 Link Purpose (In Context) (Level A)**
   - Enlaces con texto descriptivo y contextual
   - Enlaces internos y externos claramente identificados

4. **SC 3.3.2 Labels or Instructions (Level A)**
   - Formulario con etiquetas asociadas correctamente
   - Campos requeridos marcados visualmente y no visualmente
   - Mensajes de error accesibles

5. **SC 2.4.7 Focus Visible (Level AA)**
   - Indicadores de foco visibles para navegación por teclado
   - Estilos de foco consistentes en todos los elementos interactivos

## 🏗️ Estructura del Proyecto

```
Proyecto/
├── index.html          # Página principal
├── programas.html      # Página de programas académicos
├── contacto.html       # Página de contacto con formulario
├── styles.css          # Estilos CSS accesibles
├── subtitles.vtt      # Subtítulos para video (referencia)
├── images/            # Carpeta de imágenes
│   ├── logo.png
│   └── logo.webp
└── README.md          # Este archivo
```

## 🚀 Uso

1. Clona el repositorio o descarga los archivos
2. Abre `index.html` en tu navegador
3. Navega entre las páginas usando el menú de navegación

## ♿ Pruebas de Accesibilidad

Este sitio ha sido diseñado para cumplir con:
- **WCAG 2.1 Level A y AA**
- Navegación por teclado funcional
- Compatible con lectores de pantalla
- Contraste de colores adecuado
- Estructura semántica HTML5

## 🛠️ Tecnologías Utilizadas

- HTML5 semántico
- CSS3 con variables CSS
- YouTube API (para video embebido)
- ARIA labels y roles

## 📝 Notas

- El video utiliza un iframe de YouTube con subtítulos habilitados automáticamente
- Las imágenes utilizan placeholders - reemplázalas con imágenes reales en producción
- El formulario de contacto requiere backend para procesar los envíos

## 📄 Licencia

Este proyecto es un ejemplo educativo de accesibilidad web.

