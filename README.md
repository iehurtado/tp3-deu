# Presentación TP3 - DEU/DCU 2026

Presentación generada con Marpit.

## Dependencias

Para instalar las dependencias necesarias ejecutar:

```bash
npm install
```

## Compilación

Para generar la presentación ejecutar:

```bash
npm run pptx
```
Se genera en `dist/presentacion.pptx`.


## Servidor

Para servir la presentación durante el desarrollo ejecutar:

```bash
npx marp --html --allow-local-files --watch presentacion.md
```