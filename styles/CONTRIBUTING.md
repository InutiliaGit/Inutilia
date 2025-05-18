# ✨ Contribuir con Estilos a InutilIA

¡Gracias por interesarte en vestir a InutilIA con un nuevo estilo!  

Este espacio es para compartir variantes visuales que transformen radicalmente (o sutilmente) la estética del sitio.  

No hay reglas estrictas, pero sí algunos acuerdos para que todo funcione bien en GitHub Pages y dentro del espíritu del proyecto.

## 🧬 Requisitos mínimos

Cada estilo debe incluir **dos archivos**:

1. `tu-estilo.css`: el archivo con tus reglas de estilo.
2. `tu-estilo.json`: un archivo de metadatos con la siguiente estructura:

```
{
  "nombre": "Nombre visible del estilo",
  "autor": "Tu nombre o seudónimo",
  "contacto": "Tu mail o red (opcional)",
  "descripcion": "Breve explicación del estilo",
  "version": "1.0",
  "fecha": "YYYY-MM-DD"
}
```

Tip: El nombre del .css y del .json deben ser idénticos (excepto por la extensión), en minúsculas, sin espacios.

## Qué tipo de estilos podés proponer?

Funcionales: temas oscuros, monocromos, tipografías editoriales, accesibilidad mejorada, etc.

Chindogu: estilos intencionalmente incómodos, absurdos, cambiantes, ilegibles o molestos.

Experimentales: animaciones raras, temas que cambian con el tiempo, efectos dinámicos.

## Recomendaciones técnicas

El CSS debe funcionar en todos los .html del sitio (especialmente index, chindogus, styles, contacto, manifiesto).

Probá tu estilo en modo oscuro y claro si corresponde.

Evitá modificar estructura del HTML vía CSS (nada de display: none a secciones enteras).

Usá clases específicas cuando puedas (.inutilia-header, .chindogu-card, etc.).

Evitá dependencias externas (fuentes, frameworks): mantenelo autónomo.

## Herramientas útiles

Podés testear localmente con Live Server en VSCode.

Usá Prettier o similar para mantener tu CSS prolijo.

Validá tu CSS en W3C CSS Validator.

## Pull Requests

Forkeá el repo.

Trabajá en una nueva rama: git checkout -b estilo-tu-nombre.

Asegurate de agregar tu .css y .json en la carpeta styles/.

Abrí un Pull Request con título: 💅 Nuevo estilo: [nombre-del-estilo].

## Filosofía

Un estilo inútil... también es un estilo.

Acá nada se tira: lo bello, lo feo, lo incómodo y lo inclasificable conviven en armonía caótica.