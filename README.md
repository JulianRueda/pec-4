# Lore TØP — Web de apoyo

Web estática (HTML + CSS + JS) sobre el lore de **Dema**, el universo narrativo de Twenty One Pilots.

## Diseño en Figma

🔗 **[Ver el diseño en Figma](https://www.figma.com/design/3HeNfjjdMkVA1IHiB9JfbQ/Lore-TOP-Web-Apoyo-con-IA?node-id=29-4667&t=92XKnrzfw7WoDGx1-1)**

| Modo claro | Modo oscuro |
|---|---|
| ![Home - modo claro](docs/figma-home-light.png) | ![Home - modo oscuro](docs/figma-home-dark.png) |

## Mapa del sitio

```mermaid
flowchart TD
    Home["index.html<br/>Inicio - Dema"]
    Home --> Timeline["Línea de tiempo"]
    Home --> Archives["archives.html<br/>Archivos de Dema"]
    Archives --> Doc["archives-document.html<br/>Documento del archivo"]
    Home --> Dict["Diccionario del Lore"]
    Home --> Chars["characters.html<br/>Personajes y Facciones"]
    Home --> Eras["Eras de la historia"]
    Home --> Disco["Discografía completa"]
    Home --> Theories["theories.html<br/>Teorías"]
    Home --> Contact["Contacto"]
```

## Estructura de cada página

```mermaid
flowchart LR
    Page[Página] --> Sidebar
    Page --> Main
    Page --> Footer
    Sidebar --> Menu["Menú de navegación"]
    Sidebar --> Theme["Apariencia: claro / oscuro"]
    Main --> Hero
    Main --> Secciones["Secciones de contenido"]
```

## Estructura del proyecto

```
├── index.html               # Inicio
├── archives.html            # Archivos de Dema
├── archives-document.html   # Documento individual
├── characters.html          # Personajes y facciones
├── theories.html            # Teorías
├── template-structure.html  # Plantilla base
├── css/                     # Un CSS por página
├── js/                      # Scripts
└── docs/                    # Capturas del diseño
```

## Cómo verlo

Abre `index.html` en el navegador. No necesita instalación.
