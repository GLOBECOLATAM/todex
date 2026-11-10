# TODEX · Globeco Smart

**T**odas las **O**peraciones de **D**ocumentos **EX**press.

TODEX es la herramienta de documentos de Globeco Smart. Abres un PDF y lo trabajas directamente en el navegador: editas su texto como en Word, agregas texto nuevo con la fuente del propio documento, escribes o subrayas a mano, sacas páginas o lo divides en varios archivos, y descargas el resultado.

**Úsalo aquí:** https://globecolatam.github.io/todex/

**Todo ocurre en tu equipo.** El PDF no se sube a ningún servidor. La página solo descarga las librerías de código abierto que usa.

## Qué puede hacer

- **Editar texto**: haz clic sobre cualquier texto y escribe. Puedes cambiar tamaño, color, negrita y cursiva, y moverlo arrastrando el asa azul.
- **Ver qué fuente usa cada texto**: el panel muestra el nombre real de la fuente, su tamaño y estilo, y la lista de todas las fuentes del documento.
- **Agregar texto con la fuente del documento**: con «+ Texto» eliges primero la fuente (o copias el estilo de un texto existente) y luego haces clic donde va.
- **Dibujar a mano**: pluma, resaltador y borrador, con colores y grosor. Sirve para firmas, subrayados y notas.
- **Dividir PDF y sacar páginas** (botón «✂ Dividir»):
  - *Por rangos*: por ejemplo páginas 1–5 y 7–9. Cada rango sale en su propio PDF (todos juntos en un ZIP) o unidos en un solo PDF.
  - *Elegir páginas*: escribes `2, 4-5, 10` o haces clic en las miniaturas. Atajos para todas, impares o pares. Sale un solo PDF o una página por archivo.
  - *Cada N páginas*: corta el documento en partes iguales, por ejemplo de 3 en 3.
  - Opción para incluir o no tus ediciones y dibujos en las páginas que sacas.
- **Deshacer y rehacer**: Ctrl+Z / Ctrl+Y (Cmd en Mac), o los botones ↶ ↷.
- **Modo claro y oscuro** con botón manual.
- **Descargar** el PDF editado. El original no se modifica.

## Limitaciones

- Los PDF suelen incluir solo las letras que ya usan. Si escribes una letra que la fuente original no trae, ese texto se guarda con la fuente estándar más parecida (Helvetica, Times o Courier), y el panel te avisa antes.
- El texto editado se escribe encima del original y lo tapa con el color de fondo. El texto original sigue dentro del archivo, debajo. No uses esta herramienta para ocultar información confidencial.
- Los PDF escaneados (imágenes) no tienen texto editable. Sí se puede dibujar sobre ellos.
- Los PDF protegidos con contraseña no se pueden abrir.

## Librerías

- [PDF.js](https://github.com/mozilla/pdf.js) 3.11.174 (Apache-2.0): lee y muestra el PDF.
- [pdf-lib](https://github.com/Hopding/pdf-lib) 1.17.1 (MIT): escribe el PDF editado.
- [@pdf-lib/fontkit](https://github.com/Hopding/fontkit) 1.1.1 (MIT): revisa qué letras trae cada fuente.
- [JSZip](https://github.com/Stuk/jszip) 3.10.1 (MIT): arma el ZIP cuando divides en varios archivos.

Se cargan desde cdnjs y jsDelivr con la versión fija.

## Licencia

MIT. Ver [LICENSE](LICENSE).

---

Una herramienta de **Globeco Smart** · Designed by W.I.G. — CTO & DoA
