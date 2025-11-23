# EDA

# Proyecto Final EDA: WordCloud

Profesor: Erick Mauricio Gomez Nieto
Alumno : Manuel Eduardo Zeze Charaja Quispe

# Descripcion:
Este proyecto busca procesar noticias exclusivamente en idioma ingles para extraer topics y generar un Word-Cloud de los top m trending topics. Este proyecto se divide en 3 secciones principales

Preprocesamiento: Hace uso de tokenizacion, eliminacion de stop-words, stemming.
Estructura de Datos: Hibrido Hash + Buckets Ordenados por frecuencia, manejado desde un Gestor Ventana.
Visualizacion: Word-Cloud en Python

# Arquitectura:
<img width="1639" height="1217" alt="image" src="https://github.com/user-attachments/assets/362a58fa-348b-4a9f-beff-09c2d360e159" />


# Archivos incluidos

##ProyectoFinalEDA.cpp
Aqui se encuentra la implementacion de las estructuras que sostienen el proyecto, aqui se ejecuta la simulacion.

##preproc.h
Aqui se encuentran las funciones necesarias para ejecutar el preprocesamiento, se incluye stopwords, stemming

##KM.txt
Configuraciones iniciales para K y M

##topm.csv
Archivo CSV vacio

##WC.py
Codigo en python que contiene la implementacion de la Wordcloud

# Pasos para ejecutar
1. Realizar la descarga o clonar la carpeta completa para evitar fallos
2. Tener instalado  un compilador de C++ (Originalmente se compilo con gcc(15.2)) y compilar con "g++ -std=c++17 *.cpp -o ProyectoEDA y compilarlo con ./ProyectoEDA
3. Contar con la versione stable de python mas reciente (Este codigo se hizo con la version 3.12.3), Dispoinible Aqui:
4. Instalar las librerias matplotlib, wordcloud, pandas con el siguiente comando:
   pip install matplotlib wordcloud pandas

En caso desee cambiar su dataset, o agregar mas archivos debe colocarlos en la carpeta data (Tiene que tener ese nombre), estos deben de ser txts




