# Clínicas Doctor Jota - Tienda Online

Sitio web responsive para Clínicas Doctor Jota, especializada en productos dermatológicos y cosmética de alta calidad.

## Características

- Diseño responsive con Tailwind CSS
- Modo oscuro/claro
- Catálogo de productos interactivo
- Testimonios de clientes
- Galería de imágenes de Instagram
- Sección de suscripción a newsletter
- Carrito de compras (interfaz)

## Estructura del Proyecto

```
clinicas-doctor-jota/
├── index.html          # Página principal
├── assets/             # Recursos estáticos
│   ├── logo.jpg        # Logo de la marca
│   ├── heronew.jpg     # Imagen principal
│   ├── piel.jpg        # Imagen de producto
│   ├── 01.png          # Imágenes de productos
│   ├── 02.png
│   ├── c1.jpg          # Galería Instagram
│   ├── c2.jpg
│   ├── c3.jpg
│   ├── c4.jpg
│   ├── c5.jpg
│   ├── subanner.png    # Banner principal
│   ├── woman01.png     # Testimonio
│   └── ...             # Otras imágenes
├── README.md           # Este archivo
└── .gitignore          # Archivos ignorados por Git
```

## Tecnologías Utilizadas

- **HTML5**: Estructura semántica
- **Tailwind CSS**: Framework CSS para diseño responsive
- **JavaScript**: Interactividad y animaciones
- **Google Fonts**: Tipografías personalizadas
- **Material Symbols**: Iconos

## Marcas Destacadas

- SkinCeuticals
- Colorescience
- Isdin
- Fillmed
- La Roche Posay
- SkinClinic

## Categorías de Productos

- Sérum faciales
- Cremas hidratantes
- Protectores solares
- Tratamientos especializados
- Maquillaje dermatológico

## Instalación y Uso

### Para Desarrollo Local

1. Clona este repositorio
2. Abre `index.html` en tu navegador
3. O usa un servidor local como XAMPP, Live Server, etc.

### Para Publicar en GitHub Pages

1. Sube este repositorio a GitHub
2. Ve a Settings > Pages
3. Selecciona "Deploy from a branch"
4. Elige la rama `main` y carpeta `/ (root)`
5. Tu sitio estará disponible en `https://tu-usuario.github.io/nombre-repo/`

### Para Desarrollo con Cloudflare Tunnel

```bash
cloudflared tunnel --url http://localhost/protodemo
```

## Personalización

### Colores

Los colores principales están definidos en la configuración de Tailwind:

- Primary: `#583E27` (Marrón oscuro)
- Secondary: `#CAB097` (Beige)
- Background Light: `#F0E7E2` (Beige claro)
- Background Dark: `#161513` (Carbón muy oscuro)

### Tipografías

- Display: Montserrat
- Body: Lato
- Italic: Playfair Display

## Contribuir

1. Fork este repositorio
2. Crea una rama para tu feature (`git checkout -b feature/NuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Añadir nueva característica'`)
4. Push a la rama (`git push origin feature/NuevaCaracteristica`)
5. Abre un Pull Request

## Licencia

Este proyecto es para uso demostrativo. © 2025 Clínicas Doctor Jota.

## Contacto

- Email: info@clinicasdoctorjota.com
- Web: www.clinicasdoctorjota.com
- Instagram: @clinicasdoctorjota