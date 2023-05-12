Historia de usuario n.º 1: mi calculadora debe contener un elemento en el que se pueda hacer clic que contenga un = (signo igual) con un id correspondiente="igual".

Historia de usuario n.º 2: mi calculadora debe contener 10 elementos en los que se pueda hacer clic que contengan un número cada uno del 0 al 9, con los siguientes ID correspondientes: id="cero", id="uno", id="dos", id="tres" , id="cuatro", id="cinco", id="seis", id="siete", id="ocho" e id="nueve".

Historia de usuario n.º 3: mi calculadora debe contener 4 elementos en los que se pueda hacer clic, cada uno de los cuales contiene uno de los 4 operadores matemáticos principales con los siguientes ID correspondientes: id="agregar", id="restar", id="multiplicar", id="dividir" .

Historia de usuario n.º 4: mi calculadora debe contener un elemento en el que se pueda hacer clic que contenga un archivo . (punto decimal) símbolo con un correspondiente id="decimal".

Historia de usuario n.º 5: mi calculadora debe contener un elemento en el que se pueda hacer clic con un id="clear".

Historia de usuario n.º 6: mi calculadora debe contener un elemento para mostrar valores con un id="display" correspondiente.

Historia de usuario n.° 7: en cualquier momento, al presionar el botón Borrar se borran los valores de entrada y salida, y la calculadora regresa a su estado inicial; 0 debe mostrarse en el elemento con el id de visualización.

Historia de usuario n.° 8: A medida que ingreso números, debería poder ver mi entrada en el elemento con la identificación de visualización.

Historia de usuario n.° 9: en cualquier orden, debería poder sumar, restar, multiplicar y dividir una cadena de números de cualquier longitud, y cuando presiono =, el resultado correcto debería mostrarse en el elemento con la identificación de visualización.

Historia de usuario n.° 10: Al ingresar números, mi calculadora no debería permitir que un número comience con varios ceros.

Historia de usuario n.º 11: cuando se hace clic en el elemento decimal, aparece un archivo . debe agregarse al valor que se muestra actualmente; dos . en un número no debe ser aceptado.

Historia de usuario n.º 12: Debería poder realizar cualquier operación (+, -, *, /) en números que contengan puntos decimales.

Historia de usuario n.° 13: si se ingresan 2 o más operadores de manera consecutiva, la operación realizada debe ser el último operador ingresado (excluyendo el signo negativo (-)). Por ejemplo, si se ingresa 5 + * 7 =, el resultado debe ser 35 (es decir, 5 * 7); si se ingresa 5 * - 5 =, el resultado debe ser -25 (es decir, 5 * (-5)).

Historia de usuario n.° 14: Presionar un operador inmediatamente después de = debería iniciar un nuevo cálculo que opera sobre el resultado de la evaluación anterior.

Historia de usuario n.º 15: mi calculadora debe tener varios lugares decimales de precisión cuando se trata de redondear (tenga en cuenta que no existe un estándar exacto, pero debería poder manejar cálculos como 2/7 con una precisión razonable de al menos 4 lugares decimales) .

Nota sobre la lógica de la calculadora: se debe tener en cuenta que existen dos escuelas principales de pensamiento sobre la lógica de entrada de la calculadora: la lógica de ejecución inmediata y la lógica de fórmula. Nuestro ejemplo utiliza lógica de fórmula y observa el orden de precedencia de la operación, la ejecución inmediata no. Cualquiera de los dos es aceptable, pero tenga en cuenta que dependiendo de cuál elija, su calculadora puede arrojar resultados diferentes a los nuestros para ciertas ecuaciones (vea el ejemplo a continuación). Siempre que su matemática pueda ser verificada por otra calculadora de producción, no considere esto como un error.

EJEMPLO: 3 + 5 x 6 - 2 / 4 =

Lógica de ejecución inmediata: 11.5
Lógica de fórmula/expresión: 32,5