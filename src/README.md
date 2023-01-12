# Análisis Exploratorio de Datos (EDA) - Data Science

![img](src/../assets/Fondo.png)

## _Acceso a la vivienda para los jovenes en 2023_



Este es mi primer EDA realizado con `Python` en Jupyter Notebooks. El trabajo consiste en explorar los datos más relevantes de la vivienda en España, así como también datos relativos a los jovenes residentes en el país. Se intentará dar respuesta a hipotesis como:
> ¿Puede un joven acceder con relativa facilidad a una vivienda?
> 
> Esta generación de jovenes, ¿está en igualdad de oportunidades en comparación con otras?
> 
> ¿La vivienda en propiedad sigue siendo la mayor preferencia de los jovenes? ...
> 
> Entre otras cuestiones que intentaremos dar respuesta.

El EDA utiliza diferentes técnicas de visualización que serán comentadas en la memoria del trabajo.

Este estudio se basa en los datos obtenidos para el territorio español, haciendo comparativas con los demás paises de la UE.
Pretende ser un reflejo de la actual situación de acceso a la vivienda y del mercado inmobiliario, observando los datasets disponibles en fuentes de acceso público.




## Librerías

- Pandas
- Numpy
- Seaborn 
- Matplotlib 
- Folium


Este trabajo será una presentación, seguiré trabajando en él hasta acabarlo posteriormente a enero de 2023.


## Estructura

El EDA sigue la siguiente estructura:

1. `src/`: directorio principal
2. `src/data`: todos los archivos de datos en crudo utilizados en el analisis. Dentro habrá otra carpeta nombrada `clean` que será donde se guarden los datasets ya trabajados y limpios para su manipulación.
3. `src/notebooks`: los notebooks usados para pruebas.
4. `src/memoria.ipynb`: en este notebook se resume los pasos de la analítica.

```
src/
├─ data/
│  ├─ clean/
│  │ 	└── datasets_limpios.csv ...
│  ├─ datasets_crudos.csv ...
│  └── ...
│  
├─ notebooks/
│  ├─ pruebas.ipynb ...
│  └── ...
│
├─ memoria.ipynb
│
└── readme.md
```

## Como leer el trabajo

Todos los estadísticos estarán ya dispuestos en los diferentes archivos, por lo que solo debe visualizar los datos y leer las conclusiones.
Sin embargo, si desea modificar o manipular los datos, le recomiendo que instale como pre-requisito: 




```sh
folium==0.14.0
geocoder==1.38.1
geopy==2.3.0
matplotlib==3.5.3
matplotlib-inline==0.1.6
numpy==1.21.6
pandas==1.3.5
squarify==0.4.3
```



## Fuentes 

Este análisis se ha realizado con datos recogidos de las siguientes fuentes:

| Fuente | Link |
| ------ | ------ |
| INE | [Instituto Nacional de Estadística][INE] |
| Eurostat | [Data browser][Euro] |
| datos . gob | [Gobierno de España][gob] |
| CIS | [plugins/onedrive/README.md][CIS] |




   [INE]: <https://www.ine.es/index.htm>
   [Euro]: <https://ec.europa.eu/eurostat/en/>
   [gob]: <https://datos.gob.es/es>
   [CIS]: <https://www.cis.es>
