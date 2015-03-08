# Presentación para la defensa de pgHumor

## Compilación

```bash
latexmk main.tex
```

## Dejar generando mientras se trabaja

```bash
latexmk -pvc main.tex
```

### Para que no pare de generar si hay un error

```bash
latexmk -pvc -interaction=nonstopmode main.tex
```
