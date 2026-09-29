# Dr. Alfredo de la Rosa · CLEMI NFC

Landing estática basada en el sistema visual aprobado de Dra. Claudia Reyes, versión 09a8193. Conserva estructura, iconos, navegación, efectos metálicos, cristal y animaciones. Paleta propia: verde petróleo, perla y oro.

Destino: https://yeferclemijpg.github.io/Dr.AlfredodelaRosa/

## Desarrollo

- `npm ci`
- `npm run dev`
- `npm run verify`
- `npm run export:preview`

Editar datos en `content/profile.json`, estructura en `src/page.html` y ajustes propios en `src/alfredo-theme.css`. Los archivos `index.html`, `public/contacto.vcf` y el QR histórico se generan automáticamente.

GitHub Pages publica `dist/` desde la rama main mediante Actions. La exportación autónoma está en `artifacts/Alfredo_De_La_Rosa_Vista_Previa.html`.

Guardar contacto descarga una vCard directamente. El sistema del dispositivo puede pedir confirmar su importación; la página no guarda silenciosamente en la agenda.

Procedencia de imágenes, prompts y fuentes: `docs/RECURSOS.md`.
