# IPTV Gratis · Documentación Read the Docs

Sitio basado en **Sphinx** + **sphinx_rtd_theme**, listo para publicar en
[Read the Docs](https://readthedocs.org).

## Estructura

```
.
├── .readthedocs.yaml      # Configuración de build de RTD
├── README.md
└── docs/
    ├── conf.py            # Configuración de Sphinx
    ├── requirements.txt   # Dependencias de build
    ├── index.rst          # Página principal
    ├── listas.rst
    ├── paises.rst
    ├── deportes.rst
    ├── compatibilidad.rst
    └── instrucciones.rst
```

## Build local (opcional)

```bash
pip install -r docs/requirements.txt
sphinx-build -b html docs docs/_build/html
```

Abre `docs/_build/html/index.html` en tu navegador.

## Publicar en Read the Docs

Pasos a continuación en el chat.
