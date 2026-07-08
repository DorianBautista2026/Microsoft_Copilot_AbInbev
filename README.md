[INSTRUCCIONES_PUBLICACION.md](https://github.com/user-attachments/files/29805040/INSTRUCCIONES_PUBLICACION.md)
# Publicar Dashboard HTML - Licenciamiento Copilot

## Abrir localmente en Windows
1. Copia la carpeta `copilot_html_dashboard` a tu PC.
2. Da doble clic en `index.html`.
3. Usa el boton `Exportar PDF` si necesitas presentarlo como PDF.

## Publicarlo en SharePoint
1. Entra al sitio de SharePoint donde quieres publicarlo.
2. Ve a `Documentos` o a la biblioteca donde compartirás el archivo.
3. Crea una carpeta, por ejemplo `Dashboard Copilot Q2 2026`.
4. Sube `index.html`.
5. Comparte el enlace del archivo con permisos de lectura.

Nota: algunas configuraciones corporativas de SharePoint descargan archivos HTML en lugar de renderizarlos. Si eso pasa, usa GitHub Pages, Azure Static Web Apps, Netlify o un servidor interno.

## Publicarlo en GitHub Pages
1. Crea un repositorio nuevo.
2. Sube `index.html` a la raíz del repositorio.
3. Ve a `Settings > Pages`.
4. En `Build and deployment`, selecciona `Deploy from a branch`.
5. Elige `main` y carpeta `/root`.
6. Guarda. GitHub generará una URL pública.

## Publicarlo en Netlify
1. Entra a https://app.netlify.com/drop.
2. Arrastra la carpeta `copilot_html_dashboard`.
3. Netlify generará una URL para compartir.

## Publicarlo en IIS o servidor interno
1. Copia `index.html` a una carpeta del sitio, por ejemplo `C:\inetpub\wwwroot\copilot-dashboard\`.
2. Abre en navegador: `http://servidor/copilot-dashboard/index.html`.

## Seguridad
El HTML contiene los datos embebidos dentro del archivo. Publícalo solo en un espacio con permisos adecuados si los nombres/correos son información interna.
