

# Variables

Las variables son ...

 ```java
 /*
antes de usar una variable en java, esta siempre tiene que ser declarada, tenemos que indicarle a java como se llama
nuestra variable y de que tipo es.
variable1, variable2, variable3 y variable4 unicamente podran albergar numeros enteros, ya que java es un lenguaje altamente tipado, por lo que es un lenguaje menos flexible, pero nos evita muchas fuentes de error ya que muestra los fallos en tiempo de compilacion y que no se produzcan los errores en tiempo de ejecucion.
las variables comienzan con in tipo desde el inicio y este no se puede cambiar, a los numeros 23 y 6 asignados se le llaman literales
 */
public class Variables {
    public static void main(String[] args) {
        int variable1;
        int variable2, variable3; //si tenemos variables del mismo tipo, podemos declararlas todas en una misma linea separando los nombres con ","
        //aunque esta declaracion multiple puede resultar comoda, no se recomienda, ya que empeora la legibilidad del codigo
        int variable4 = 23; //podemos asignar un valor a nuestra variable, en el momento de declararla

        variable1 = 6; //podemos declarar el valor a una variable anteriormente declarada, vemos que no ponemos el tipo de dato de la variable, ya que lo hemos indicado en su declaracion. este tipo no podra cambiar a lo largo del programa.

        System.out.println("variable 1 contiene el valor: " + variable1);

        variable2 = 2 * variable1;  //en este caso le asignamos el valor resultante de una operacion

        System.out.println("variable 2 contiene el valor: " + variable2);
    }
}
```

