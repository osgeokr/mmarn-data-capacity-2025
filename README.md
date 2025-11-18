<p align="center">
  <img src="images/kr.png" width="50">
  <img src="images/do.png" width="50">
</p>

<p align="center">
  <img src="images/minpre.png" height="35">
  <img src="images/mmarn.png" height="30">
  <img src="images/korea.png" height="30">
  <img src="images/koica.png" height="25">
  <img src="images/knps.png" height="30">
  <img src="images/gdc.png" height="30">
</p>

---

# Práctica de uso de datos en Python
## Análisis y Visualización de Datos Climáticos (Avanzado)  
**Fechas:** Del 18 al 19 de nov. de 2025  
**Lugar:** [Universidad Nacional Pedro Henríquez Ureña (UNPHU)](https://unphu.edu.do/), Aula 109 del Edificio 2
**Byeong-Hyeok Yu** Analista de Datos Espaciales (Correo: bhyu@knps.or.kr)

## Contenidos del Curso

1. Introducción a la sintaxis básica de Python  
2. Análisis temporal del viento en el Caribe con NCEP-DOE Reanalysis-2  
3. Análisis de mapas de calor espaciales con datos de ocurrencia de GBIF  
4. Análisis de daños por incendios forestales basado en Sentinel-2  
5. Descarga de Sentinel-2 usando Microsoft Planetary Computer  
6. Obtención de DEM ajustado al área RGB de Sentinel-2  
7. Script APA para detectar vegetación acuática y algas con Sentinel-2  
8. Análisis del índice de algas flotantes (Sargassum) usando AVISO+  

---

# Instalación para las Prácticas

## 1. Descargar e instalar Python  
Python 3.13.6  
https://www.python.org/ftp/python/3.13.6/python-3.13.6-amd64.exe

## 2. Descargar este repositorio  
GitHub → Code → Download ZIP  
Descomprime el archivo.

## 3. Crear y activar un entorno virtual  
```bash
python -m venv mmarn
mmarn\Scripts\activate
```

## 4. Actualizar pip
```bash
python.exe -m pip install --upgrade pip
```

## 5. Instalar Jupyter Notebook
```bash
pip install notebook
```

## 6. Instalar dependencias necesarias
```bash
pip install leafmap
pip install xarray rioxarray netcdf4 localtileserver
pip install pystac-client planetary-computer
pip install h5netcdf
```

## 7. Ejecutar Jupyter Notebook
```bash
jupyter notebook
```

Abre los archivos `.ipynb` dentro de la carpeta **espanol**.
