Manejo de las finanzas de Baigorria

Baigorria  trabaja en un delivery de empanadas. Se sabe que cobra un sueldo de 15000. Y se quiere modelar su comportamiento de manera de manejar sus gastos, el dinero que tiene, y su deuda. Cuando Baigorria gasta, se descuenta de su dinero, si no le alcanza aumenta la deuda. Cuando cobra un sueldo, Baigorria paga sus deudas. Si sobra algo, se suma al dinero que tiene. Agregar a Baigorria la capacidad de entender los mensajes: gastar(cuanto), totalDeuda(), totalDinero().
Tener en cuenta este escenario
1.	Baigorria arranca con 15000 de sueldo, deuda en 0, dinero en 0.
2.	Baigorria gasta 4000, totalDeuda() debe ser 4000, totalDinero() debe ser 0.
3.	Baigorria gasta otros 8000, totalDeuda() pasa a 12000, totalDinero() sigue en 0.
4.	Baigorria cobra, con los 15000 que recibe paga toda su deuda y le sobran 3000 pesos. Por lo tanto, totalDeuda() debe ser 0, y totalDinero() debe ser 3000.
5.	Baigorria gasta 25000, cubre 3000 con el dinero que tiene, el resto es deuda. totalDeuda() queda en 22000, totalDinero() en 0.
6.	Baigorria cobra, tiene que dedicar los 15000 a pagar deudas, y no le alcanza. Ahora, totalDeuda() pasa a 7000, y totalDinero() a 0.

