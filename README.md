# Antenati Book Downloader (es)
La finalidad de este programa es descargar libros de actas de la página web Antenati. Todas las páginas del libro serán almacenadas en una nueva carpeta, en la mayor resolución posible. De esta manera, podrás buscar actas más rápido usando la aplicación de fotos de tu PC, en vez de el visualizador de Antenati, que es lento e incómodo.

Ya que todas las imágenes están en alta resolución, el script tardará un tiempo en completar. Un libro de 800 páginas podrá tardar hasta una hora en descargarse, y ocupará aproximadamente 1GB de almacenamiento.

Deberás tener Python instalado con las siguientes librerias (use ``` pip install ``` para instalarlas):

- requests
- shutil
- pathlib
- json
- glob

Asimismo, deberás usar Jupyter para abrir el notebook: https://jupyter.org/install

Para descargar un libro, sigue las instrucciones:

1. Localiza el IIIF manifest en la sección 'Contenuti collegiati' del visualizador del libro:

![IIIF manifest instruction](https://user-images.githubusercontent.com/12202169/167278949-d73cd0e0-59d4-49bb-bc4a-ba6f4db66479.jpg)

2. Haz click derecho en el link, y selecciona 'Guardar link como'. Asegúrate de guardar el archivo JSON en el directorio del script.
3. Descarga tantos manifests como desees. Cuando corras el Jupyter Notebook, empezará a descargar todos los libros.
4. Todos los libros serán descargados en una carpeta separada. Asegurate de eliminar los archivos JSON después de descargar un libro, asi evitar que se vuelva a descargar la próxima vez que ejecutes el script.
5. Podrás descargar libros individualmente corriendo la función 'downloadBook' por separado.

# Antenati Book Downloader (en)
This purpose of this script is to download books from the webpage Antenati. All the pages will be stored in a newly created folder, at the highest resolution possible. This way, you can look for records faster with your PC's photo application, instead of the slower webpage viewer.

Thake in mind that since all the images are on high resolution, the script will take a while to complete. A 800 page book may take up to one hour to download, and will occupy approximately 1GB of space.

You must have Python installed with the following libraries (use ``` pip install ``` to install them):

- requests
- shutil
- pathlib
- json
- glob

Additionaly, you must use Jupyter to open the notebook: https://jupyter.org/install

To download a book, follow these instructions: 

1. Locate the IIIF manifest from the 'Contenuti collegati' section in the registry book viewer:

![IIIF manifest instruction](https://user-images.githubusercontent.com/12202169/167278949-d73cd0e0-59d4-49bb-bc4a-ba6f4db66479.jpg)

2. Right click on the link, and select 'Save link as'. Make sure you save the JSON file on the directory the jupyter notebook is located
3. Download as many manifests as you like. When you run the jupyter notebook, it will start downloading all the books.
4. All the books will be downloaded on a separate folder. Make sure to remove the JSON files once you downloaded a book, as to not download it again next time you run the script
5. You can download individual books by running the 'downloadBook' function separately.
