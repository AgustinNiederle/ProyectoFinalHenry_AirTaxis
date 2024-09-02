
<p align=center><img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>

# <h1 align=center> **PROYECTO FINAL - Grupo 4 (Data PT 09)** </h1>

# <h1 align=center>**`Servicio de Taxis Verdes Complementarios (Arquitectura del proyecto)`**</h1>

<p align="center">
<img src="https://github.com/AgustinNiederle/ProyectoFinalPrueba/blob/main/gr%C3%A1ficos/primera%20arquitectura%20de%20proyecto.jpg"  height=300>
</p>

¡Bienvenidos al  proyecto FInal del Bootcamp de SoyHenry!
<hr>  

## **Descripción del proyecto**

## Contexto
En la ciudad de nueva york existen miles de taxis en servicio de manera continua. Existen tres tipos diferentes de taxis: Amarillos, Verdes y Negros. Cada tipo de taxi tiene sus zonas designadas, el amarillo es el único que puede subir y bajar pasajeros en Manhattan, por ejemplo. Para esto, los taxis amarillos tiene que comprar su registro de habiltitación para poder otorgar dicho servicio en esta zona, que además, es por mucho, la de mayor caudal de pasajeros de nueva york. Este registro ha llegado a valer un millón de dolares antes de la aparición de Uber; hoy fluctua entre los 200 mil dolares. Esto generó un conflicto por los registros de habilitación para ser taxis amarillos, que es la más rentable. 
Por otro lado, en 2021, a cuasa de la crisis ambiental, el presidente Biden aprobó una ley que busca renovar los taxis por modelos modernos con combustibles de energía alternativa, con el fin de reducir el impacto ambiental de este servicio de transporte. En nueva york, existen diversas estaciones de energía electrica -principal energía alternativa en el país-, lo que hace posible y operativamente posible el objetivo de la ley: un recambio total de los automóviles para finales el 2025. Actualmente los taxis amarillos se encuentran en crisis, debido a que los taxis particulares como Uber, captan sus clientes y no les permiten subir la tarifa a un valor que les resulte rentable para pagar los prestamos que sacaron para comprar las habilitaciones. Por esto, los taxis verdes (que trabajan fuera de Manhattan), son los que aún permiten el ingreso de nuevos servicio, pero ¿de què manera se podría realizar de una manera rentable?. En este trabajo buscaremos responder esta pregunta clave.

## Público Objetivo
Empresa de transporte de pasajeros a larga distancia que busca introducir taxis en Nueva York.

## Propuesta de sectorización del negocio
Creemos conveniente para esta empresa que busca ingresar a otorgar servicios de taxis, introducir su servicio específico para los pasajeros de los servicios de transporte de larga distancia (autobuses y aviones). Actualmente pasan por los aeropuertos de nueva york, más de 80 mil perosnas por mes. Esto permitiría captar una zona del mercado lo suficientemente grande y que aún no posee la competencia y la sobreoferta presente en el servicio actual de taxis convencionales.

## Perfil diferenciador del negocio
Hemos hecho incapié en ser ecologicamente activos a la hora de pensar el nuevo servicio de taxis. Por esto, creemos que nuestro diferencial respecto a otros servicios de transporte que captan clientes en los aeropuertos tiene que provenir desde esta búsqueda, tanto para los usuarios como para la empresa de taxis.  

## Propuesta General

Crear una app que asocie a los pasajeros que hacen caminos similares o van a destinos en las mismas zonas de NY, para recomendarles viajes compartidos en taxis eléctricos que permitan un servicio cómodo, de menor costo y más comprometido ecológicamente, ya que permite ayudar a reducir congestiones de tráfico, ruido ambiente y, sobre todo, la huella de carbono. :muscle:

<p align="center">
<img src="https://github.com/AgustinNiederle/ProyectoFinalPrueba/blob/main/gr%C3%A1ficos/primera%20arquitectura%20de%20proyecto.jpg"  height=500>
</p>


## **Propuesta de trabajo**

**`Transformaciones`**:  Para este MVP no necesitas perfección, ¡necesitas rapidez! ⏩ Vas a hacer estas, ***y solo estas***, transformaciones a los datos:


+ a

+ b
  
+ c

+ d

<br/>


  
<br/>



##### Racconto de observaciones mías: 
Segun lo que voy viendo: Van a servir los datos de disponibilidad de estaciones de servicio por zonas (dataset1: Alternative_Fuel_Vehicles_US) y por
tipo de energia (con dataset2: Electric and Alternative Fuel Charging Stations), 
por eficiencia de cada modelo (dataset 3: ElectricCarData_Clean),
el modelo y el precio en euros, versus eficiencia y cantidad de asientos (dataset4:ElectricCarData_Norm), 
Rapid Charge es un atributo que puede ser útil. 
El Dataset5 (Light Duty Vehicles) tiene los ID de los vehiculos, sus fabricantes y los còdigos de combustibles nomenclados. 
Por otro lado, tiene "electric Only Range", que nos dice solo para los que son sólo eléctricos.
