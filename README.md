# factura-algoritmo
factura simple con algoritmo
Algoritmo sin_titulo
	Definir PRECIO,CANTIDAD Como Entero
	Definir Nombre,Apellido,Direccion,fecha,Producto,compra como Caracter
	Escribir 'INGRESE EL NOMBRE DEL CLIENTE'
	Leer Nombre
	Escribir 'INGRESE EL APELLIDO DEL CLIENTE'
	Leer Apellido
	Escribir 'INGRESE LA DIRECCION DEL CLIENTE'
	Leer Direccion
	Escribir 'INGRESE LA FECHA'
	Leer fecha
	Escribir 'DATOS DEL CLIENTE'
	Escribir '                  Nombre ;',Nombre
	Escribir '                  Apellido ;',Apellido
	Escribir '                  Direccion ;',Direccion
	Escribir '                  Fecha ;',fecha
	Escribir "¿Deseas comprar algo?"
	Leer compra
	Borrar Pantalla
	Mientras compra= "si" Hacer
		Escribir "¿Qué deseas comprar?"
		Leer producto
		Escribir "¿Cuántas unidades deseas comprar?"
		Leer cantidad
		Escribir "Ingresa el precio , por favor"
		Leer precio
		total<- (cantidad*precio)
		Escribir "El monto total de la compra es:","  ",  total," de ",producto
		Escribir ""
		Escribir "¿Deseas comprar algo más?"
		Leer compra
		Borrar Pantalla
	FinMientras
FinAlgoritmo
