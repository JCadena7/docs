# GEAB — Sitio de documentación del semillero

Sitio web oficial del **Grupo de Estudios en Analítica y Big Data (GEAB)**,
construido con [Mintlify](https://mintlify.com).

## Requisitos

- [Node.js](https://nodejs.org) v18 o superior
- [Mintlify CLI](https://mintlify.com/docs)

## Instalación

```bash
# Instalar la CLI de Mintlify
npm i -g mint

# Clonar el repositorio
git clone https://github.com/geab-semillero/docs.git
cd docs
```

## Desarrollo local

```bash
# Iniciar el servidor de desarrollo
mint dev
```

El sitio estará disponible en [http://localhost:3000](http://localhost:3000).

## Verificación

```bash
# Verificar links rotos
mint broken-links

# Validar estructura del sitio
mint validate

# Verificar accesibilidad
mint a11y
```

## Estructura del proyecto

```
docs/
├── docs.json                # Configuración del sitio
├── favicon.svg              # Favicon
├── logo/                    # Logos light/dark
├── images/                  # Imágenes estáticas
├── snippets/                # Componentes reutilizables
├── index.mdx                # Página principal
├── team.mdx                 # Equipo
├── join-us.mdx              # Únete al semillero
├── research-lines.mdx       # Líneas de investigación
├── active-projects.mdx      # Proyectos activos
├── completed-projects.mdx   # Proyectos completados
├── research-papers.mdx      # Artículos de investigación
├── divulgation-articles.mdx # Artículos divulgativos
├── conference-papers.mdx    # Ponencias
├── mentions.mdx             # Menciones y reconocimientos
├── tools.mdx                # Herramientas
├── datasets.mdx             # Conjuntos de datos
├── references.mdx           # Bibliografía
└── blog/                    # Posts del blog
```

## Despliegue

Mintlify despliega automáticamente al hacer push a la rama conectada
en el [Dashboard de Mintlify](https://dashboard.mintlify.com).

## Licencia

MIT
