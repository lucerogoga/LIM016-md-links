# Markdown Links

## 1. MD-BEAR-LINKS

:bear: md-bear-links es una libreria de linea de comando CLI el cual permite indentificar, validar y dar estadisticas
de loas URL que contengan los archivos de formato MarkDown .

<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/mdlinks.png" title ="mdlinks" width="700">

## 2. Link de instalacion

Instalar la [libreria](https://www.npmjs.com/package/md-bear-links) via npm i md-links

## 3. Guia de Uso
A través de la terminal:

HELP OPTION : md-bear-links --help o md-bear-links --h.
<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/help.png" title ="help" width="700">

WITHOUT OPTIONS : md-bear-links --validate o md-bear-links --v.
<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/validateFalse.png" title ="help" width="700">

VALIDATE OPTION : md-bear-links --validate o md-bear-links --v.
<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/validateTrue.png" title ="help" width="700">

VALIDATE & STATS OPTION : md-bear-links --validate --stats o md-bear-links --v --s.
<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/statsValidate.png" title ="help" width="700">

STATS OPTION : md-bear-links --stats o md-bear-links --s.
<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/stats.png" title ="help" width="700">

MANEJANDO ERRORES

Ruta no existe

<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/error1.png" title ="help" width="700">
Directorio vacio

<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/error2.png" title ="help" width="700">
No es archivo MD

<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/error3.png" title ="help" width="700">

## 4. Diagramas

Diagrama API

<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/API-diagram.jpg" title ="help" width="700">

Diagrama CLI

<img src="https://github.com/lucerogoga/LIM016-md-links/blob/main/images/CLI-diagram.jpg" title ="help" width="700">


## 5. Dependencias Utilizadas
   
    "chalk": "^2.4.1",
    "jsdom": "^19.0.0",
    "markdown-it": "^12.3.2",
    "node-fetch": "^2.6.7",
    "yargs": "^17.3.1"

## 6. Fuente

[Repositorio de Laboratoria: ](https://github.com/Laboratoria/LIM016-md-links) :Se encuentran todas las condiciones y herramientas a trabajar para el proyecto.

## 7. Autora

[Lucerogoga](https://github.com/lucerogoga) :bear:

## 8. Checklist

### General

* [:bear: ] Puede instalarse via `npm install --global <github-user>/md-links`

### `README.md`

* [ :bear:] Un board con el backlog para la implementación de la librería.
* [ :bear: ] Documentación técnica de la librería.
* [ :bear:] Guía de uso e instalación de la librería

### API `mdLinks(path, opts)`

* [ :bear:] El módulo exporta una función con la interfaz (API) esperada.
* [ :bear:] Implementa soporte para archivo individual
* [ :bear:] Implementa soporte para directorios
* [ :bear:] Implementa `options.validate`

### CLI

* [ :bear:] Expone ejecutable `md-links` en el path (configurado en `package.json`)
* [ :bear: ] Se ejecuta sin errores / output esperado
* [ :bear:] Implementa `--validate`
* [ :bear:] Implementa `--stats`

### Pruebas / tests

* [ :bear: ] Pruebas unitarias cubren un mínimo del 70% de statements, functions,
  lines, y branches.
* [ :bear:] Pasa tests (y linters) (`npm test`).