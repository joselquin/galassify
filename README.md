# Galassify

Segmentación automática de galaxias del SDSS y extracción de outliers.

Galassify es un sistema automático de clustering y extracción de outliers de galaxias a partir de los espectros de éstas en el SDSS (Sloan Digital Sky Survey).

Se muestran los notebooks principales empleados en el desarrollo de la solución técnica de Galassify.

Los notebooks con los que se obtiene la solución final entregada en el Sprint 1 al IAC son:

* ExtracciónInicial.ipynb
* Tratamiento.ipynb
* Algoritmo 3 - outliers (pipeline) - 3k_m.ipynb

Los demás son pruebas de concepto y desarrollos intermedios.

Este proyecto ha sido creado (y sigue desarrollándose) con mucho cariño por:

* Arvin Daswani Daswani, arvinpd@gmail.com
* Pedro Martín Gómez, pmargom@gmail.com
* Silvia Peraza Delgado, sperazad@gmail.com
* Jose Luis Quintero García, joselquin@gmail.com
* Vicente Tetuani Sánchez, vtetuani@gmail.com

El actual desarrollo está en el cuaderno Galassify.ipynb

### Puntos pendientes:

* Estudio del tratamiento del escalado del espectro antes de pasar por el autoe$
* Pruebas con otro tipo de autoencoders:
  - Stacked (actual).
  - Conv1D.
  - LSTM.
  - Variational.
* Estudio de validez en la aleatoriedad en la extracción de outliers.
* Estudio de validez en la aleatoriedad en la extracción de clusters.
* Embbebded clustering.

