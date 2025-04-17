# MatrixCV
Crea tu CV sin teenr conocimientos de Astro ni HTML.  
Tendrás una apariencia friki + profesional que impulsará tu apariencia.

## Haz un Fork del repositorio de MatrixCV
Si no sabes como mira [este vídeo](https://youtu.be/3GymExBkKjE?t=12091&si=3w5yeG52wmHYjVMQ)

## Edita los archivos
Para añadir tus palabras a MatrixCV tendrás que editar:
- Portada.astro
- Text.astro
- Contenido.astro

## Como editar los archivos
Tienes dos opciones para editar los archivos:
1. Haciéndolo tú mismo con tus conocimientos y añadiendo nuevas funcionalidades
2. Usando el editor incorporado en MatrixCV.

## Como hacer con la segunda opción
Dirígete a MatrixCV en el repositorio de Inled-Group.
Abre en el navegador [inled-group.github.io/matrixcv/personalizar.portada](https://inled-group.github.io/matrixcv/personalizar.portada) o [inled-group.github.io/matrixcv/personalizar.sobremi](https://inled-group.github.io/matrixcv/personalizar.sobremi) o [inled-group.github.io/matrixcv/personalizar.text](https://inled-group.github.io/matrixcv/personalizar.text)  y escoge la sección a personalizar.

### Personalizando la portada
Tendrás un asistente que te guiará por el proceso de edición de la portada. En un minuto al tendrás lista.
Haberás de que descargarla y guardarla en tu repositorio en matrixcv/src/components/Portada.astro  
¡Y ya tendrías lista la portada!

### Personalizando un CV en la página de MatrixCV
Para añadir una sección sobre tí puedes usar el personalizador de "personalizar.sobremi".
Podrás editar texto formateado que luego será insertado en un fichero .astro que haberás de guardar como "contenido.astro" en components.
Verifica que funciona llendo desde la portada a /sobremi

### Añadiendo texto y noticias.
Para ello deberás crear páginas basadas en /pages/code.astro cambiándoles el nombre y cambiando el nombre de la página Text.astro importada, por Text1.astro y etc... y cambiar por ello el `import`de la sección superior de code.astro y asimismo cambiar `<Layout>
	<Header />
	<Text />
	<Footer />
</Layout>` por `<Layout>
	<Header />
	<Text1 />
	<Footer />
</Layout>` y viceversa.
