# Miguel Alejandro Díaz Gaytán — Personal Portfolio & Engineering Lab

Sitio web profesional y portafolio interactivo de proyectos en ingeniería química sustentable, desarrollo de software, modelado de sistemas e instrumentación.

Desplegado en producción mediante GitHub Pages: **[alejandrodiazgaytan.github.io](https://alejandrodiazgaytan.github.io/)**

## Características Principales

- **Arquitectura SPA (Single Page Application)**: Navegación fluida y modular desarrollada en JavaScript ES6+ vanilla sin dependencias externas.
- **Personal Lab & Simulaciones Físicas**:
  - Modelado y renderizado dinámico de reactores Arc en Canvas/SVG (reactor circular Mark I y reactor triangular de paladio Mark VI).
  - Simulación física de partículas moleculares en tiempo real en segundo plano.
  - Modulación interactiva de potencia lumínica y frecuencia de pulso.
- **Terminal CLI Emulada**: Consola técnica interactiva para exploración ágil de habilidades, trayectoria y comandos de diagnóstico.
- **Diseño Responsivo Dark Tech**: Paleta técnica basada en Tailwind/CSS moderno con variables personalizadas y tipografía en `Inter` y `JetBrains Mono`.

## Estructura del Proyecto

```
.
├── index.html        # Estructura semántica principal y vistas modulares SPA
├── css/
│   └── style.css     # Sistema de diseño, variables CSS y animaciones
├── js/
│   └── main.js       # Control de vistas SPA, emulador de terminal y motores gráficos
├── assets/           # Recursos estáticos (documentos, imágenes y especificaciones)
└── README.md         # Documentación general del repositorio
```

## Ejecución Local

Para visualizar el sitio localmente en un entorno de desarrollo:

```bash
# Servidor HTTP local con Python
python -m http.server 8000

# O mediante Node.js
npx serve .
```

Acceder a `http://localhost:8000` en cualquier navegador moderno.
