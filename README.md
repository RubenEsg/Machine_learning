# EDA — Fuga y valor del cliente en una *fintech* colombiana

**Universidad del Norte · Machine Learning · Entrega 1**
Martínez Pulido, Valerie · Basto Martínez, Abrahan · Esguerra Fernández, Rubén

📖 **Sitio publicado:** https://rubenesg.github.io/Machine_learning/

Análisis exploratorio y auditoría de calidad de datos sobre el conjunto público
[COFINFAD](https://data.mendeley.com/datasets/mhb4zn3258/1) — 48.723 clientes,
54 variables y 3.159.157 transacciones (2023).

## Contenido

| Archivo | Descripción |
|---|---|
| `eda_bancario.ipynb` | Notebook ejecutado con todo el análisis (18 figuras, 12 tablas) |
| `Entrega1_EDA_articulo.pdf` | Artículo del proyecto en formato Springer Nature |
| `docs/` | Sitio web ya compilado. Es lo que publica GitHub Pages |
| `_toc.yml`, `_config.yml`, `_static/custom.css` | Fuentes del libro (página única, a todo el ancho) |

## Publicación

GitHub Pages sirve la carpeta `docs/` de la rama `main`
(**Settings → Pages → Source: Deploy from a branch → main → /docs**).

## Recompilar (solo si se modifica el notebook)

```bash
pip install "jupyter-book<2"
jupyter-book build .
rm -rf docs && cp -r _build/html docs && touch docs/.nojekyll
git add -A && git commit -m "Actualizar sitio" && git push
```
