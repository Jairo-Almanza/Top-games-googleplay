En esta ocasión vamos a análizar un dataset del top 100 de videojuegos disponibles en Google Play Store.

Fuente de datos: android-games.csv

Dataset original: Top Games on Google Play Store

Información del dataset

Este dataset contiene el top 100 de videojuegos por cada categoría en Google Play Store, con información de las calificaciones y otros datos como precio y numero de instalaciones.

Columnas

*Rank: Posición del videojueo en una categoria en particular.
*Title: Nombre del videojuego.
*Total ratings: Número total de calificaciones.
*Installs: Número de instalaciones apróximado.
*Average rating: Calificación promedio hasta 5.
*Growth (30 days): Crecimiento porcentual en 30 días.
*Growth (60 days): Crecimiento porcentual en 60 días.
*Price: Precio en dolares.

Category: Categoría del videojuego.
*5 star ratings: Número de calificaciones de 5 estrellas.
*4 star ratings: Número de calificaciones de 4 estrellas.
*3 star ratings: Número de calificaciones de 3 estrellas.
*2 star ratings: Número de calificaciones de 2 estrellas.
*1 star ratings: Número de calificaciones de 1 estrella.
*Paid: Es un videojuego pago (True) o gratis (False).

Aclaraciones

El crecimiento porcentual se caulcula teniendo en cuenta la cantidad total de instalaciones y la cantidad total de calificaciones, con ello encontrar el porcentaje de crecimiento promedio.
Cada puesto en el top 100 fue registrado en una día del año, en total 100 días: * 01/01/2020: Registro puesto 1 * 02/01/2020: Registro puesto 2