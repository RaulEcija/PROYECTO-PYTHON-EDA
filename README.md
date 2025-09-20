 # PROYECTO EDA CON PYTHON

 ## 1.	DESRIPCIÓN DEL PROYECTO

El proyecto realiza un Análisis Exploratorio de los Datos (EDA) sobre un conjunto de datos que para nosotros se compone de dos bases de datos (BBDD), estas son llamadas: *1) 'bank-additional.csv'* la cual va sobre campañas de marketing directo de una institución bancaria portuguesa, concretamente se rellena la BBDD mediante llamadas telefónicas con datos que engloban al cliente y su relación con si se suscribe el producto o no y de qué forma – tiempo. *2) 'customer-details.xlsx'* la cual contiene información sobre características demográficas y comportamientos de compra para cada cliente del banco.

 ## 2.	BBDD

Cada base de datos contiene una serie de columnas relevantes, estas se exponen a continuación:
### 1)	'bank-additional.csv': 
●	age: La edad del cliente.

●	job: La ocupación o profesión del cliente.

●	marital: El estado civil del cliente.

●	education: El nivel educativo del cliente.

●	default: Indica si el cliente tiene algún historial de incumplimiento de pagos (1: Sí, 0: No).

●	housing: Indica si el cliente tiene un préstamo hipotecario (1: Sí, 0: No).

●	loan: Indica si el cliente tiene algún otro tipo de préstamo (1: Sí, 0: No).

●	contact: El método de contacto utilizado para comunicarse con el cliente.

●	duration: La duración en segundos de la última interacción con el cliente.

●	campaign: El número de contactos realizados durante esta campaña para este cliente.

●	pdays: Número de días que han pasado desde la última vez que se contactó con el cliente durante esta campaña.

●	previous: Número de veces que se ha contactado con el cliente antes de esta campaña.

●	poutcome: Resultado de la campaña de marketing anterior.

●	emp.var.rate: La tasa de variación del empleo.

●	cons.price.idx: El índice de precios al consumidor.

●	cons.conf.idx: El índice de confianza del consumidor.

●	euribor3m: La tasa de interés de referencia a tres meses.

●	nr.employed: El número de empleados.

●	y: Indica si el cliente ha suscrito un producto o servicio (Sí/No).

●	date: La fecha en la que se realizó la interacción con el cliente.

●	contact_month: Mes en el que se realizó la interacción con el cliente durante la campaña de marketing.

●	contact_year: Año en el que se realizó la interacción con el cliente durante la campaña de marketing.

●	id_: Un identificador único para cada registro en el dataset.

### 2)	'customer-details.xlsx':

●	Income: Representa el ingreso anual del cliente en términos monetarios.

●	Kidhome: Indica el número de niños en el hogar del cliente.

●	Teenhome: Indica el número de adolescentes en el hogar del cliente.

●	Dt_Customer: Representa la fecha en que el cliente se convirtió en cliente de la empresa.

●	NumWebVisitsMonth: Indica la cantidad de visitas mensuales del cliente al sitio web de la empresa.

●	ID: Identificador único del cliente.

## 3.	REQUISITOS  - OBJETIVOS

Para la consecuón de los objetivos (que más adelante se exponen), es preciso definir una serie de requisitos:

##### 1)	Transformación y limpieza de los datos.
##### 2)	Análisis descriptivo de los datos.
##### 3)	Visualización de los datos.
##### 4)	Informe explicativo del análisis.


*Siendo el objetivo principal:*

#### 1. Conseguir un análisis bien definido y exploratorio de los datos para diferenciar las campañas de marketing que más funcionan, los clientes más rentables y si el producto corresponde a lo que se intenta vender.

4.	ESTRUCTURA

````bash
Archivospy
---
BBDD
--- bank-additional.csv
--- customer-details.xlsx
--- DataProject.word
Readme
--- Informe.word
README.md

````

## 5.	HERRAMIENTAS
#### -	Python
#### -	Pandas
#### -	Visual Studio Code
## 6.	INSTALACIÓN – EJECUCIÓN
### 1)	Clona el repositorio de GitHub.
### 2)	Instala las dependencias y extensiones.
### 3)	Abre Jupyter Notebook o Visual Studio Code (hecho desde aquí).

## 7.	RESULTADOS  - CONCLUSIONES
(opcionales)
#### -	[✓] Identificación de variables numéricas y categóricas
#### -	[✓] Detección de valores nulos
#### -	[✓] Mapas de calor de correlaciones
#### -	[✓] Visualizaciones clave (histogramas, boxplots, scatterplots)

## 8.	CONTRIBUCIONES
Este proyecto admite cualquier tipo de contribución, siendo cualquier voluntario en mejorarlo o aportar su grano de arena para impulsarlo. Para ello se puede abrir un pull request o una issue. Es un proyecto totalmente público.

## 9.	AUTOR

#### Autor: Raúl Écija Maeso

#### [@RaulEcija]

#### *Link GitHub:* https://github.com/RaulEcija/PROYECTO-PYTHON-EDA 

