## Contributing a InutilIA

¡Gracias por tu interés en contribuir a InutilIA!

Este espacio es una guardería de chindogus digitales: inventos absurdos, improbables, disfuncionales o inquietantes que puedan, sin querer, hacernos pensar.

Para que tu contribución pueda ser aceptada, debe cumplir las siguientes condiciones técnicas y estructurales.

### Estructura obligatoria de cada Chindogu

Cada chindogu debe vivir en su propia carpeta dentro del directorio /chindogus/, siguiendo esta estructura:

/chindogus/

  /tu_chindogu/

    ├── index.html

    ├── metadata.json

    └── assets/

         ├── css/

         ├── js/

         └── imgs/

El nombre del directorio debe estar en kebab-case, sin espacios, tildes ni mayúsculas. 

Ejemplo: chatdoubt, raton-via-bluetooth, calefon-qr.

### metadata.json (obligatorio)

Este archivo es fundamental para que el sistema identifique, catalogue y eventualmente destaque tu creación.

Ejemplo:

´´´
{
  "nombre": "ChatDoubt",
  "autor": "Ada Lovelace",
  "contacto": "ada@ejemplo.com",
  "descripcion": "Un chatbot que responde con dudas, contradicciones y ambigüedades.",
  "tags": ["chatbot", "ironía", "ambigüedad", "experimento"],
  "fecha": "2025-05-17"
}
´´´

Campos obligatorios:
- nombre: nombre público del chindogu
- autor: nombre o pseudónimo del creador
- contacto: email, red social o GitHub válido
- descripcion: breve descripción del chindogu
- tags: al menos 1 tag
- fecha: en formato YYYY-MM-DD

El metadata.json debe ser válido y parseable por cualquier validador JSON estándar.

### Requisitos técnicos

Debe funcionar en GitHub Pages sin backends ni servidores.

Solo HTML, CSS y JavaScript del lado cliente.

No se permiten llamadas a servidores privados ni APIs externas sin consentimiento.

Podés usar bibliotecas JS front-end (como p5.js, three.js, etc.) siempre que estén importadas vía CDN.

No uses rutas absolutas.

Todas las rutas deben ser relativas (./, ../), para que funcionen desde cualquier entorno sin configuraciones especiales.

No deben requerirse instalaciones locales para ejecutar tu chindogu.

Basta con abrir el index.html desde el navegador.

Debe abrir correctamente desde GitHub Pages.

Usá https://inutiliagit.github.io/inutilia/chindogus/nombre-de-tu-chindogu/ como prueba.

### Cómo colaborar paso a paso

Hacé un fork de este repositorio.

Crea tu rama con un nombre representativo: add/chatdoubt, feature/termostato-de-manzana, etc.

Agregá tu carpeta a chindogus/ con la estructura mencionada.

Asegurate de que metadata.json esté completo y correcto.

Commiteá tus cambios con un mensaje claro.

Hacé un Pull Request contra main.

Nos reservamos el derecho de no aceptar PRs que no cumplan estos requisitos o que no sumen al espíritu del proyecto (aunque igual podés romper las reglas con estilo, si sabés lo que estás haciendo).

### Consejos extra
El humor, la incomodidad o la belleza técnica son bienvenidos.

Si tu chindogu incluye audio, video o interacciones, asegurate que pesen lo menos posible y se carguen rápido.

Todo el contenido debe ser original o con licencia libre atribuida.