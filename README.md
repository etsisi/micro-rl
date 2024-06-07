# Microcredencial en Aprendizaje por refuerzo y optimización de sistemas

Repositorio para almacenar la web y demás recursos de la titulación
«Formación Específica en Aprendizaje por Refuerzo y Optimización» (ya se
llamará microcredencial).

## ¿Cómo hacer cambios?

Lo he preparado para intentar que haya que tocar lo menos posible en
estilo y forma. el fichero `index.md` tiene todo el contenido que se
refleja en el sitio. Luego, el fichero `assets/css/styles.css` tiene las
variables de los colores que se usan en la web. En `assets/img` están
las imágenes que se usan. Y ya está. El resto es cosa de jekyll, así que
o lo miras o me preguntas.

## Entorno de desarrollo

La web está hecha con Jekyll, así que habrá que instalar el entorno si
no está instalado.

Luego es tan sencillo como:

1. Clonar el repositorio

    ```bash
    git clone https://github.com/etsisi/micro-rl
    ```

2. Entrar en el directorio del sitio

    ```bash
    cd docs
    ```

3. Ejecutar el servidor local

    ```bash
    bundle exec jekyll serve
    ```

Cada vezs que hagamos un cambio en el código, se reflejará en el
servidor local.

## ¿Dónde has generado el favicon?

Aquí: <https://favicon.io/favicon-generator/>. Es un sitio que te
permite crearlo a partir de un texto. Concretamente este lo he generado
con:

- Nombre: **µRL**
- Background: **Rounded**
- Font Family: **League Gothic**
- Font Variant: **Regular 400 Normal**
- Font Size: **100**
- Font Color: **#FFFFFF**
- Background Color: **#9B59B6**
