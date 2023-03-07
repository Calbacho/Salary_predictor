# Salary_predictor

## Objetivo

El objetivo del proyecto es crear un modelo de predicción de los salarios, según sus roles, el país y el puesto, entre otros parámetros. 


## Puntos clave para la creación del modelo

#### Lectura de tablas y columnas

Leemos tanto 'salary_data' como 'testeo' y quitamos las columnas que no coincidan en las dos.

#### Revisión  de correlaciones

Dibujamos un mapa de calor con las correlaciones por columnas. Nada significatívo.

#### get_dummies() y align()

Transformamos todos los predictores en columnas booleanas y aligneamos después las columnas para testear de manera apropiada.

#### LazyRegressor

Dividimos la tabla transformada en train y test y usamos LazyRegressor para ver cual es el modelo de ML óptimos dados los datos.


## LGBMRegressor 

Con un **RMSE de 52030.55**, es el modelo mas efectivo.

Predecimos la muestra.
Score público: 47130.17270



