# Instrucciones

Ir al botón de "Use this template" -> "Create a new repository"

Llenar los campos

Ir a Settings -> Pages -> Build and deployment -> Source -> GitHub Actions

En el archivo "_quarto.yml" encontrarás una parte que se ve así

```
format:
  html:
    theme: minty
    toc: true
    lang: es
```

Pues cambiar el `theme`. Ahora está en minty. Puedes seleccionar de entre las opciones

https://quarto.org/docs/output-formats/html-themes.html

Supongamos que me gustó el tema "superhero". Entonces lo cambio

```
format:
  html:
    theme: superhero
    toc: true
    lang: es
```
