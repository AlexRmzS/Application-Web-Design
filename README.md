# Application-Web-Design

**Nombre:** [Luis Alejandro Ramirez Salazar]  
**Matrícula:** [2918965]  
**Carrera:** [IDS]  
**Semestre:** [5to Semestre]  

**Materia:** [Diseno de Aplicaciones Web]  
**Profesor:** [Cristopher Gerardo Gaytan Diaz]

## ¿Qué es Markdown?
Markdown es un lenguaje de marcado ligero que se usa para formatear texto. Permite escribir en un formato fácil de leer y convertir a HTML. Es comúnmente utilizado en la creación de documentación, blogs, y otros textos que requieren una conversión a HTML sencilla.

## Opciones de etiquetado que ofrece Markdown

Markdown ofrece varias opciones para dar formato a un documento. A continuación, algunos ejemplos de uso:

### Encabezados
Los encabezados se crean usando `#` para diferentes niveles (1 a 6):
```markdown
# Encabezado nivel 1
## Encabezado nivel 2
### Encabezado nivel 3


Para negrita, usa **texto** o __texto__. Para cursiva, usa *texto* o _texto_:
**Este es un texto en negrita**  
*Este es un texto en cursiva*


Para listas no ordenadas, usa -, * o +. Para listas ordenadas, usa números seguidos de un punto:
- Elemento 1
- Elemento 2

1. Primer elemento
2. Segundo elemento

Puedes crear enlaces con [texto](url) e imágenes con ![alt](url):
[Visitar GitHub](https://github.com)  
![Logo de GitHub](https://github.githubassets.com/images/modules/logos_page/Octocat.png)

Para bloques de código, usa tres acentos graves (```) para abrir y cerrar el bloque:
echo "Esto es un bloque de código"

## Verificar el estado de un repositorio local
git status

## Agregar archivos individuales o globalmente
git add nombre_del_archivo

## Agregar comentarios a la confirmación (commit)
git commit -m "Descripción del commit"

## Cargar los cambios en el repositorio remoto
git push origin nombre_de_la_rama

## Crear, explorar y eliminar ramas
git checkout -b nombre_de_la_rama

## Revertir un repositorio a una confirmación específica
git log
git checkout identificador_del_commit