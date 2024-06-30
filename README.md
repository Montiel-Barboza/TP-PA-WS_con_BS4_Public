# TP-PA-WS_con_BS4_Public
Repositorio público para el trabajo práctico de programación avanzada, Web Scraping con Beautiful Soup 4.


# Applicaión

## Descripción

Esta aplicación es una herramienta simple que permite obtener enlaces, direcciones y precios de propiedades en venta o en alquiler en dos sitios web: [Argenprop](https://www.argenprop.com/) y [BuscadorProp](https://www.buscadorprop.com.ar/). Utiliza las bibliotecas `requests` y `BeautifulSoup` para hacer scraping de los datos, y `tkinter` para la interfaz gráfica de usuario.

## Estructura del Proyecto

El código está dividido en los siguientes archivos:

1. **scraper.py**: Contiene la clase `PropertyScraper`, la cual se encarga de realizar el scraping de los sitios web.
2. **gui.py**: Contiene la clase `PropertyApp`, la cual construye la interfaz gráfica de usuario utilizando `tkinter`.
3. **main.py**: Archivo principal que inicializa la aplicación.
4. **Readme.md**: Este archivo, que proporciona una descripción del funcionamiento de la aplicación.

## Instalación y Uso

1. Asegúrese de tener Python 3.x instalado en su sistema.
2. Instale las dependencias necesarias:
    ```sh
    pip install requests beautifulsoup4
    ```
3. Ejecute el archivo `main.py` para iniciar la aplicación:
    ```sh
    python main.py
    ```
4. En la interfaz de usuario, seleccione el sitio web desde el cual desea obtener las propiedades y haga clic en "Scrape" para obtener los resultados.

## Notas

- La estructura HTML de los sitios web puede cambiar con el tiempo, lo cual podría afectar la capacidad de la aplicación para hacer scraping correctamente. Es posible que se requieran ajustes en el método `parse_properties` para adaptarse a estos cambios.
- La aplicación está diseñada para ser un ejemplo simple y puede mejorarse con características adicionales como manejo de errores más robusto, paginación y opciones de búsqueda más avanzadas.
