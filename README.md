# Propensity-Score-Matching-with-R

El objetivo es analizar los probables efectos del programa FORTASEG que se implementó en México en 2020 ha tenido los efectos esperados en dos indicadores de violencia criminal a nivel municipal: homicidio y lesiones por arma de fuego.
La técnica empleada es el pareamiento por puntaje de propensión o Propensity Score Matching (PSM) una técnica que permite estimar los efectos de un tratamiento con datos no experimentales u observacionales [1],
por medio de la estimación de puntajes de propensión como criterios estadísticos para vincular observaciones del tratamiento y fuera del tratamiento y reducir el sesgo de selección de covariables no observadas.

La carpeta data contiene los conjuntos de datos necesarios para realizar el analisis PSM.
Los mapas ZM_presupuesto_tasa_homicido20XX.html contienen informacion sobre el número de homicidios para los años 2019, 2020 y 2021 en los municipios beneficiarios del fortaseg, en general, lo que cada mapa muestra es el total del presupuesto
asociado a cada municipio representado por el tamaño del circulo y el número de homicidios se representa por la escala de colores.
