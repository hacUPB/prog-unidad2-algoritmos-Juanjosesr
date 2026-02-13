Datos de entrada: 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| ID | Identificador del empleado (numérico) | 

| S1, S2, S3, S4, S5, S6 | Sueldo de los 6 meses (numérico) | 

Datos de salida: 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| Prom | Promedio mensual | 

| Total | Ingreso total | 

| ID |      | 

Datos intermedios  

| Nombre | Descripción | 
| ---------- | ---------------- | 

|           | |                | 

Procedimientos: 
Total = S1 + S2 + S3 + S4 + S5 + S6 

Prom = total / 6 

 

 

Pseudocódigo: 
Inicio 

Leer ID, S1, S2, S3, S4, S5, S6 

Total = S1 + S2 + S3 + S4 + S5 + S6 

Prom = total / 6 

Mostrar ID, Total, Prom 

Fin 

 

A = 15 

B = 2 

A >B Verdadero 

A = B Falso 

 

A >= 0 Verdadero 

 

 

 

 

Ejercicio 1:  

Un acuario ( tienda de peces ) Necesita determinar cuántos litros o galones de agua caben en un acuario, pero solo dispone de una cinta métrica. Diseña un algoritmo para solucionar el problema 

 

Datos de entrada: 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| Largo | Largo del tanque en cm | 

| Ancho | Ancho del tanque en cm | 

| Alto | Alto del tanque en cm | 

| Unidad | Unidad de medida (litro o galón) del volumen total | 

Datos de salida: 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| Volumen_lt | Volumen total del tanque en litros | 

| Volumen_gl | Volumen total del tanque en galones | 

Pseudocódigo: 

Inicio 

Mostrar “Por favor ingrese las medidas del tanque” 

Leer Largo, Ancho, Alto 

Mostrar “Ingrese L para litros y G para galones” 

Leer unidad 
 

Volumen = largo * Ancho * Alto //Volumen en cm3 equivalente a mL  

Volumen_lt = Volumen / 1000 //en Litros  

Si Unidad = “G” 
                         Volumen_gl = Volumen_LT * 0.26 
                         Mostrar Volumen_gl 

Si no 
           Mostrar Volumen_lt 

Fin Si 

Fin 

 

 

 

 

 

 

 

 

 

 

 

Realice un algoritmo para determinar cuánto se debe pagar por equis cantidad de lápices considerando que si son 1000 o más el costo es de $85 cada uno; de lo contrario, el precio es de $90. Represéntelo con el pseudocódigo y el diagrama de flujo. 

 

Datos de entrada: 

| Nombre | Descripción | 
| ---------- | ---------------- | 

|      X     | Cantidad de lápices | 

 

Datos de salida: 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| Total | Precio a pagar por el total de lápices | 

 

Pseudocódigo: 

Inicio 

Mostrar “Ingrese el número de lápices a comprar” 

Leer X 

 
Si X ≥ 1000 
            Precio = 85 
Si no 
      Precio = 90 
 

Total = X * Precio 

Mostrar Total 

Fin si 

Fin 

 

Un almacén de ropa tiene una promoción: por compras superiores a $250 000 se les aplicará un descuento de 15%, de caso contrario, sólo se aplicará un 8% de descuento. Realice un algoritmo para determinar el precio final que debe pagar una persona por comprar en dicho almacén y de cuánto es el descuento que obtendrá. Represéntelo mediante el pseudocódigo y el diagrama de flujo. 

 

Datos de entrada 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| Total_neto | Precio total a pagar sin descuento aplicado | 

 

Datos de salida 

| Nombre | Descripción | 
| ---------- | ---------------- | 

| Precio_final | Precio final a pagar |  

| Descuento | Descuento que obtendrá | 

 

 