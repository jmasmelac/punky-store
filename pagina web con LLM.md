# pagina web con LLM

1. le digo a mi LLM lo siguiente: ¿Cómo puedo redactar un prompt efectivo para que me generes el código de una página web en un solo archivo que incluya: el título de mi marca de ropa "Fashion Store", una sección destacada con 5 productos principales y cada uno con un botón que diga "Comprar ahora" y redirija a WhatsApp?

el LLM me respondió: 


Para redactar un prompt efectivo que me permita generar un código para tu página web en un solo archivo, es importante ser específico sobre lo que quieres que incluya la estructura y funcionalidad. Aquí tienes un ejemplo del prompt que puedes utilizar:

Prompt:

Genera el código HTML, CSS y JavaScript en un solo archivo para una página web de una tienda de ropa llamada "Fashion Store". La página debe tener las siguientes características:

Un título en la parte superior que diga "Fashion Store".
Una sección destacada con 5 productos principales. Cada producto debe mostrar:
Una imagen genérica del producto.
El nombre del producto.
El precio del producto.
Un botón que diga "Comprar ahora".
El botón "Comprar ahora" debe redirigir a una conversación de WhatsApp con un mensaje predefinido que diga "Hola, estoy interesado en este producto: [nombre del producto]".
El diseño debe ser limpio y sencillo, con colores básicos y un enfoque en la experiencia del usuario.
El archivo debe contener todo el código necesario, incluyendo el estilo y el comportamiento del botón, en un solo archivo.

2. ese mismo texto lo copio y lo pego en el LLM y me da un código .html , ese .html lo pego en index.html
3. lo abro dándole doble clic y en el navegador se abre una pagina acorde al html

4. le pregunto lo siguiente: 

¿como identificar los enlaces de WhatsApp en el código que me proporcionaste y personalizar el mensaje en dichos enlaces?

me responde, indicándome como se envía un mensaje a WhatsApp modificando una linea del código

5. le digo que me modifique una función para ver mejor esos mensajes y poder editar tanto el mensaje como el numero

pongo la nueva función en el código

en la web cambio el area de donde deberían ir las fotos

al dar clic en comprar me manda a una api de WhatsApp con el mensaje del código

6. yo por mi parte le voy a cambiar el nombre a la tienda y a los productos

le dije al LLM : le cambie el nombre a la tienda y ahora se llama Punky Store, me gustaría cambiarle la estética a algo mas punk 
me cambio el diseño a algo mas punk

me dio por mirarlo a ver si se veía bien en móvil con la opción de inspeccionar y no se ve bien

7. las imágenes de la tienda las voy a generar con ia (NMKD) y las 5 mejores las subo a imgur

ya subidas a imgur pongo los enlaces en las url del código .html

8. le digo "ya vi y no se ve bien en mobiles, te paso el nuevo código con mis ediciones y tu lo modificas para que se vea bien en cualquier dispositivo: " le paso el código aca"

el LLM me dio 2 respuestas voy a probarlas

las probe y me gusto una, la convertí en mi index.html

también modifico cosas de los nombres de los productos y el mensaje de WhatsApp

9. le digo al LLm "perfecto, es el momento de subir a la web esta pagina (creo yo), dame las indicaciones para subirlo a github pages"

me responde con los pasos para crear una cuenta en github, y demás para subir los archivos y que quede la web

