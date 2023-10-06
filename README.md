# GeospaCy


**GeospaCy** is a web application built in Python language used for extracting spatial relation entities (spatRE) from text and Geo-referenced them. 

## Installation
There are few Python packages that are needed to install for running the application

1. Install spacy for natural language processing (NLP) tasks 
```sh
pip install spacy
```
2. Install gensim library for data preprocessing
```sh
pip install gensim
```
3. Install streamit library for running web application 
```sh
pip install streamlit
```
4. Install spacy-streamlit for display named entities (spatRE) in the text 
```sh
pip install spacy-streamlit
```

5. Install GeoPandas
```sh
pip install geopandas
```
6.  Install folium library for manipulating your data in Python, then visualize it in a Leaflet map via folium.

```sh
pip install folium
```
7. Install streamlit-folium library to visualize Leaflet map in streamlit web application

```sh
pip install streamlit-folium
``` 

## How to run the web application

```sh
streamlit run 1_🏠_Parser.py
```

## [Cite this work](https://github.com/mehtab-alam/GeospaCy/)

```latex
@software{syed_geospacy_2023,
    author = {Syed, Mehtab Alam; Aresevska, Elena; Roche, Mathieu and Teisseire, Maguelonne},
    doi = {10.5281/zenodo.8415401},
    license = {GNU GPLv3},
    title = {{GeospaCy}},
    url = { https://github.com/mehtab-alam/GeospaCy/},
    version = {1.0.0},
    year = {2023}
}
```

