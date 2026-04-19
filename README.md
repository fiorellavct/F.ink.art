# F.INK.ART — Web + Decap CMS

## Estructura
```
/
├── index.html              # Página principal
├── netlify.toml            # Configuración Netlify
├── admin/
│   ├── index.html          # Panel CMS
│   └── config.yml          # Colecciones CMS
├── content/
│   ├── home.json           # Textos del home
│   └── precios.json        # Precios
├── tatuajes/               # Portafolio (archivos .md)
└── images/uploads/         # Imágenes subidas desde CMS

## Deploy en Netlify
1. Sube esta carpeta a GitHub
2. Conecta el repo en netlify.com
3. En Netlify: Identity → Enable → Git Gateway → Enable
4. Visita tudominio.com/admin para editar
```
