# Búsqueda Semántica de Películas

Este proyecto implementa un sistema de búsqueda semántica para películas utilizando técnicas de procesamiento de lenguaje natural y aprendizaje profundo. El objetivo es permitir a los usuarios buscar películas basadas en descripciones y otros criterios relacionados.

## Tabla de Contenidos

- [Características](#características)
- [Requisitos](#requisitos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Pruebas](#pruebas)
- [Contribuciones](#contribuciones)
- [Licencia](#licencia)

## Características

- Búsqueda semántica basada en descripciones de películas.
- Integración con modelos de transformadores para el cálculo de similitud.
- Soporte para múltiples criterios de búsqueda.
- Interfaz de línea de comandos simple.

## Requisitos

Asegúrate de tener instalados los siguientes programas y bibliotecas:

- Python 3.7 o superior
- Pip (gestor de paquetes de Python)

## Instalación

1. Clona el repositorio:

   ```bash
   git clone https://github.com/tu_usuario/busqueda_semantica_2.git

   cd busqueda_semantica_2
2. Navega al directorio del proyecto:
   
   ```bash
   pip install -r requirements.txt
4. Instala las dependencias:
   
    ```bash
   pip install -r requirements.txt

## Uso

Para ejecutar la aplicación, utiliza el siguiente comando en la terminal:

   ```bash
python src/main.py

## Pruebas

Para ejecutar las pruebas unitarias, asegúrate de estar en el directorio raíz del proyecto y utiliza el siguiente comando:
python -m unittest discover -s src/tests -p "test_*.py"


## Cobertura de Pruebas
Para ejecutar la cobertura de pruebas, puedes usar el siguiente comando:

 ```bash

coverage run -m unittest discover -s src/tests -p "test_*.py"
coverage report -m



