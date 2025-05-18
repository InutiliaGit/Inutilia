# 🛠️ Guía Técnica para Colaboradores InutilIA

Este documento está orientado a colaboradores con conocimientos técnicos que deseen aportar sus propios Chindogus Digitales.

## 🗂️ Estructura esperada

Cada chindogu debe tener su propia carpeta en `chindogus/` con al menos estos archivos:

- `index.html` o `main.js` o `README.md`: el núcleo del proyecto.
- `metadata.json`: la metadata obligatoria, siguiendo el esquema `meta/schema.json`.

## 📄 Cómo validar metadata

Podés usar herramientas como [JSONLint](https://jsonlint.com/) o `ajv-cli` para validar localmente contra el esquema.

```
ajv validate -s meta/schema.json -d chindogus/michindogu/metadata.json
´´´

🌱 Workflow de colaboración

Forkea el repo.

Crea una nueva carpeta dentro de /chindogus/ con tu chindogu.

Incluí el archivo metadata.json correctamente validado.

Hacé PR a la rama principal (main). Si está bien estructurado, lo fusionamos.

🎨 Sobre el diseño

El HTML debe poder visualizarse correctamente en GitHub Pages sin backend adicional. Preferimos HTML/CSS/JS puros o frameworks que puedan compilarse a estáticos.

¿Preguntas raras? ¿Soluciones absurdas? Nos encantan. Contactanos: queriaunhotmail@gmail.com

