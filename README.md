
# Convertidor de archivos word a pdf

Esta aplicación recibe un archivo word, lo transforma en pdf, cuenta el número de páginas, le extrae la primer página y la guarda como pdf, devolviendo éste último como respuesta.


## Tecnología usada


**Server:** Java con sprint boot

**Script auxiliares:** Python


## Requerimientos

Se requiere tener instalado:

1. **Python 3.x.x**

Dependiendo del script elegido, se necesitan:

* **Microsoft Office** si utilizas el script ConversorImagen.py (Librerías de Python: docx2pdf y pikepdf).
* **LibreOffice** si utilizas el script ConversorLibreOffice.py (Librería de Python: pikepdf).

2. En el archivo ´application.properties´, descomenta la ruta correspondiente al script que vayas a utilizar.






## Ejecución local

1. Clona el repositorio:

```bash
  git clone https://github.com/Is2095/convertidorWordAPdf.git
```

2. Accede al directorio raíz del proyecto:

```bash
  cd convertidor_word_a_pdf
```

3. Instala las dependencias requeridas

```bash
  * Para Python: utiliza ´pip install´ para instalar las librerías necesarias según el script que elijas.
  * Para Java: asegúrate de tener configurado el entorno de desarrollo (por ejemplo, IntelliJ IDEA).
```

4. Inicia el servidor:

```bash
  Ejecuta el proyecto desde tu IDE preferido.
```


## Referencias de la API

#### Convertir archivo Word a PDF

##### Endpoint
```
  POST /api/documents
```

Parámetro:

| Parámetro | Tipo    | Descripción            |
| :-------- | :------- | :------------------------- |
| `file` | `archivo.docx` | enviar archivo como form data|

Respuesta:
Devuelve un archivo PDF que contiene la primera página del archivo original.
## 🔗 Links
[![PortFolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://portfolio-ismael-diaz.vercel.app)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ismael-diaz-3b440b27a)



## Autor

- Creado por [@Is2095](https://github.com/Is2095)

