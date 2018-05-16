# Memoria Trabajo Fin de Grado

 * Título: Herramienta para Identificar y Extraer Masivamente Artefactos de GitHub
 * Autor: Miguel Ángel Fernández
 * Tutor: Dr. Gregorio Robles
 * Titulación: Grado Ingeniería en Sistemas Audiovisuales y Multimedia, ETSIT, URJC
 * Curso académico: 2017/18
 * Formato: LATEX

## Dependecias e instalación

```
$ sudo apt install texlive-latex-base texlive-lang-spanish
```
### Dependencia opcional
```
$ sudo apt install texmaker
```

## Compilar fichero TEX y producir PDF

La primera vez, hay que dar permisos de ejecución a los scripts:
```
$ chmod +x compile.sh
$ chmod +x clean.sh
```
Compilar PDF y abrirlo en el visor PDF por defecto en Ubuntu:
```
$ ./compile.sh && evince memoria.pdf
```
Borrar archivos auxiliares generados al compilar (también archivos PDF):
```
$ ./clean.sh
```
