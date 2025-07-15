# Explicacion sencilla
- **Dar de alta** nuevos coches.
- **Modificar** los datos de un coche si hubo un error o si ha cambiado alguna información.
- **Eliminar** coches del registro.
- Además, incluye un **buscador** que permite **filtrar fácilmente** el coche que estamos buscando.

---

# Explicación técnica

Dentro de la carpeta principal del proyecto encontrarás **5 archivos PHP** y una **subcarpeta llamada `files`**.

La carpeta `files` contiene:

- `coches.xml`: el archivo donde se almacenan todos los registros de los coches.
- `coches.xsd`: define la estructura y validaciones que debe cumplir el XML (por ejemplo, el formato de la matrícula, el rango de puertas, etc.).
- `coches.xsl`: incluye un diseño básico pensado para transformar el XML, aunque actualmente no está en uso.

Fuera de la subcarpeta `files`, se encuentran los archivos `.php`, que manejan la lógica de inserción, modificación, eliminación y visualización de los datos. Cada archivo está comentado para facilitar su comprensión.

