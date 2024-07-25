# Laboratorio 1 Rasterización de Modelos 3D

Este proyecto carga un modelo 3D básico desde un archivo `.obj`, aplica transformaciones básicas (traslación, rotación y escala) e implementa una matriz de objeto básica. Finalmente, el modelo es dibujado en un archivo BMP utilizando líneas para visualizar los polígonos.

## Requisitos Previos

Necesitarás tener Python y Pillow instalados en tu sistema para ejecutar este proyecto.

## Instalación

Clona este repositorio y navega al directorio del proyecto:

```bash
git clone <URL_DEL_REPOSITORIO>
cd <NOMBRE_DEL_DIRECTORIO>
```

## Instalar Pillow
Instala Pillow si no lo tienes instalado:

```bash
pip install pillow
```
## Uso
Para ejecutar el script y generar la imagen BMP del modelo 3D:

```bash
python rasterizador.py
```

## Detalles del Código
1. **Carga del Archivo .obj**: Se carga un modelo 3D desde un archivo .obj, leyendo los vértices y las caras del modelo.
2. **Transformaciones del Modelo**: Se aplican transformaciones de traslación, escala y rotación al modelo utilizando matrices.
3. **Renderizado del Modelo**: Se proyecta el modelo 3D en un plano 2D y se dibuja en un archivo BMP utilizando líneas.
4. **Centrado del Modelo**: Se asegura que el modelo esté centrado y tenga un tamaño adecuado para ser completamente visible en la imagen.

## Documentación
El script principal (rasterizador.py) contiene el código necesario para cargar el modelo .obj, aplicar las transformaciones y renderizar el modelo en un archivo BMP.

## Estructura del Proyecto
**rasterizador.py**: Contiene el código fuente principal para cargar, transformar y renderizar el modelo 3D.
**README.md**: Este archivo, que proporciona información sobre el proyecto.

## Licencia
Este proyecto está bajo la licencia de MIT. 
