# Tarea-3---Funciones-Arrays-JS
Ejercicio 1: Números pares
Dado el array numeros, usa filter para obtener solo los números pares. Un número es par si n % 2 === 0.

Ejercicio 2: Filtrar por propiedad de objeto
Filtra el array productos para obtener solo los que tienen stock > 0.

Ejercicio 3: Eliminar duplicados
Elimina los valores duplicados del array tags usando filter e indexOf. Pista: un elemento es único si su posición actual coincide con la primera vez que aparece.

Ejercicio 4: Precios con IVA
Dado el array precios, usa map para calcular el precio final con 21% de IVA. Redondea a 2 decimales con toFixed(2) y convierte a número con Number().

Ejercicio 5: Extraer propiedades con destructuring
Usa map con destructuring en el parámetro para extraer solo nombre y edad de cada usuario, creando objetos nuevos más simples.

Ejercicio 6: Formatear strings
Convierte el array de nombres a formato "APELLIDO, Nombre" usando map y el método split(" ") para separar nombre y apellido.

Ejercicio 7: Suma total
Calcula la suma total de los precios usando reduce. El acumulador empieza en 0.

Ejercicio 8: Agrupar por categoría
Agrupa el array gastos en un objeto donde cada clave es una categoría y su valor es la suma de esa categoría. El valor inicial es un objeto vacío {}.

Ejercicio 9: Contar ocurrencias
Cuenta cuántas veces aparece cada palabra en el array palabras. Resultado: un objeto { palabra: cantidad }.

Ejercicio 10: Buscar usuario por id
Usa find para buscar el usuario con id === 3. Si no existe, find devuelve undefined.

Ejercicio 11: findIndex y actualizar elemento
Usa findIndex para localizar la posición del producto "Kiwi" en el array. Luego actualiza su precio a 1.5 usando el índice encontrado.

Ejercicio 12: Ordenar números y strings
Ordena edades de menor a mayor, y frutas alfabéticamente. Recuerda: sin función comparadora, sort ordena como strings (¡bug clásico!).

Ejercicio 13: Ordenar objetos por propiedad
Ordena el array empleados por salario de mayor a menor. Para invertir el orden, resta al revés: b - a.

Ejercicio 14: Efectos secundarios y acumulación
Usa forEach para: (1) mostrar cada producto con su precio formateado, y (2) calcular el total acumulando en una variable externa.

Ejercicio 15: Verificar permisos
Cada usuario tiene un array de roles. Usa includes para verificar si puede acceder a una ruta protegida que requiere el rol "admin". Muestra un mensaje distinto según el resultado.

Ejercicio 16: Pipeline completo
A partir de pedidos: (1) filtra los entregados, (2) calcula el total con IVA de cada uno con map, (3) ordénalos de mayor a menor importe, (4) muestra el resultado con forEach.

