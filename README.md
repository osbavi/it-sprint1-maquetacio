# Nombre del proyecto

Petopia - Sitio web de adopción de mascotas

## Descripcion

Este proyecto es una página de aterrizaje (landing page) para una protectora de animales ficticia. Incluye secciones de menú, galería y formulario de contacto

## Estructura del proyecto

```text
/
├── index.html          # Página principal
├── src/
│   ├── css/
│   │   └── style.css   # Estilos CSS
│   └── assets/
│       ├── img/        # Imágenes del proyecto
│       └── icons/      # Iconos
├── recommendations/    # Documentación de buenas prácticas
├── .gitignore
└── README.md
```

Además este proyecto tiene una estrategia particular de ramas de git, por lo que cada iteración la he desarrollado en una rama de función (feature-branch) separada. Cada rama mantiene un archivo README.md independiente con instrucciones específicas relacionadas con las tecnologías utilizadas en esa iteración.
En este caso desarrollo la seccion hero

```text
/
└── main
    └── develop
        ├── vainilla-iteration
            ├── feature/hero
```

## Tecnologias usadas

- **HTML5** - Estructura semántica
- **CSS3** - Estilos y diseño responsivo

## Instalacion y ejecucion

### Prerequistos

- Un navegador web moderno (Chrome, Firefox, Edge, Safari)
- Un editor de código (recomendado: VS Code)
- Git instalado (opcional pero recomendado)

### Pasos para ejecutar el proyecto

1.**Clonar el repositorio** (o descargar el archivo ZIP):

```bash
git clone https://github.com/your-username/your-repository.git **PONER MI ENLACE**
```

2.**Navegar a la carpeta del proyecto**:

```bash
cd your-repository
```

3.**Abrir el archivo HTML en tu navegador**:

- Opción 1: Haz doble clic en `index.html`
- Opción 2: Usa Live Server en VS Code (recomendado)

### Uso de Live Server en VS Code (recomendado)

1. Instala la extensión [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) extension
2. Haz clic derecho en `index.html`
3. Selecciona "Open with Live Server"

## Colaboradores

- **Oscar Ballart Vilella** - [GitHub](https://github.com/osbavi)

## Licencia

Este proyecto está bajo la Licencia MIT; consulta el archivo [LICENSE](LICENSE) para obtener más detalles.
