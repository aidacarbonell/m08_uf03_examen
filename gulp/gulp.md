# Examen Gulp

- Inicialitzar un projecte Nodejs amb npm dins la carpeta gulp
- El nom del projecte ha de ser ExamenGulp
---
- Crea un arxiu gulpfile.js ha de tenir les següents tasques:
- "mincss": Ha d'agafar els arxius de la carpeta "scr/css", els ha de concatenar i minificar en un arxiu anomenat "estils.min.css" a la carpeta "dist/css"
- "compilarjs": Ha d'agafar els arxius JavaScript de la carpeta "src/js", el s'ha de concatenar i compilar amb Babel en un arxiu anomenat "app.js" a la carpeta "dist/js"
- "control": Ha de controlar els canvis en els arxius css i javascript de les carpetes "src/css" i "scr/js", ha d'executar automàticament les tasques "mincss" i "compilarjs" quan es realitzin canvis en els arxius.