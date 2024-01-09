# APA-PRACTICA

## Autors
Júlia Alice Amenós Dien, Èric Ryhr Mateu

## Dependències:
``pip install -r requirements.txt``

## Estructura de fitxers:
- ``dataset``: Dataset original + metadades
- ``dataset.txt``: Dataset original
- ``datasets/``: Carpeta amb datasets processats
- ``models/``: Carpeta amb models entrenats
- ``visualization.ipynb``: Visualització del dataset
- ``preprocessing_classification.ipynb``: Preprocessing per models de classificació
- ``classification_models.ipynb``: Entrenament dels models de classificació
- ``interpretability.ipynb``: Anàlisi d'interpretabilitat
- ``preprocessing_regression.ipynb``: Preprocessing per models de regressió
- ``regression_models.ipynb``: Entrenament dels models de regressió

## Execució:
- Per executar els models primer realitzar el preprocessing pertintent (el qual generarà dos datasets a ``datasets/``) i després executar els models pertinents.
- Per realitzar l'anàlisi d'interpretabilitat primer realitzar el preprocessing de classificació.
- Per realitzar la visualització no cal cap pas previ.