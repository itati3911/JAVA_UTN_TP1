TP 1 - Console Exercises

IMPORTANT:
To solve these exercises, you must create a Java console project with the following name: TP1_GRUPO_X.
Create two packages: one named Ejercicio1 and another named Ejercicio2.

EXERCISE 1:
All the classes related to this exercise must be created inside the package named Ejercicio1.

Create a class called Empleado with the following properties:

int id

String nombre

int edad

Apply the concept of encapsulation within the Empleado class.

The Empleado ID must be generated automatically by the class. The first ID should be number 1000 and should increase by 1 for each new employee added. The ID must be generated within the class constructor. Once an ID is assigned to an employee, it cannot be modified; therefore, the ID must be a constant variable (use final to create the constant).

The class will have two constructors:
✓ The first constructor will be empty and will assign the default values: "sin nombre" (no name) to the nombre variable and "99" to the edad variable.
✓ The second constructor will receive the name and age as parameters to be assigned.

Create a static method that returns the next ID to be generated:
int devuelveProximoID().
For example, if the last ID was number 1444, the method will return the following message:
"The next ID will be 1445"

Implement the toString() method within the Empleado class.

Create a class called Principal, and inside it, create the main method.
In main, you must create 5 employees and display their corresponding information using the toString() method.
Some employees should be created using the empty constructor and others with the constructor that takes parameters.
You should also display the message returned by the devuelveProximoID() method.

************************************************************************************************************************************************************************************
************************************************************************************************************************************************************************************

UNIVERSIDAD TECNOLOGICA NACIONAL
FACULTAD REGIONAL GENERAL PACHECO
TÉCNICO SUPERIOR EN PROGRAMACIÓN
LABORATORIO DE COMPUTACIÓN IV
TP 1
Ejercicios de consola
IMPORTANTE:
Para resolver estos ejercicios deberá crear un proyecto de consola JAVA con
el siguiente nombre: TP1_GRUPO_X. Crear dos paquetes uno llamado
Ejercicio1 y otro llamado Ejercicio2.
EJERCICIO 1:
1. Todas las clases pertenecientes a este ejercicio se crearán dentro del
paquete llamado Ejercicio1
2. Crear una clase Empleado con las siguientes propiedades:
int id;
String nombre;
int edad;
3. Aplicar el concepto de encapsulación dentro de la clase Empleado
4. El Id del Empleado debe ser generado automáticamente a partir de la clase,
el primer ID será el número 1000 e irá incrementando en 1 por cada nuevo
empleado agregado. El ID del empleado deberá ser generado en el
constructor de la clase. Una vez que se le asigne un ID del Empleado, este no
podrá ser modificado, por lo que el ID debe ser una variable constante (usar
final para crear la constante)
Ejemplo: A continuación, creamos un empleado y como verán no asignamos
su ID, este ID se deberá crear de manera interna a través del constructor.
Empleado x = new Empleado();
x.setNombre(“Jose”);
x.setEdad(30);
System.out.println(x.toString());
//Se mostrará por consola: “Empleado Jose, edad:30, legajo:1000”;
5. La clase tendrá dos constructores.
✓
El primer constructor será vacío y cargará por defecto en la variable nombre:
“sin nombre” y en la variable edad: “99”.
✓
El segundo constructor recibirá como parámetros: el nombre y la edad, para
ser asignados.
6. Crear un método estático que devuelva el próximo ID a ser generado: “int
devuelveProximoID()”. Por ejemplo, si el último ID fue el número 1444, el
método devolverá el siguiente cartel “El próximo ID será el 1445”.
7. Realizar el método toString() dentro de la clase Empleado.
8. Crear una clase llamada principal y dentro de ésta crear el main:
En el main se deberán crear 5 empleados y mostrar su información
correspondiente utilizando el método toString(). Algunos empleados
crearlos con el constructor vacio y otros con el constructor con parámetros.
También deberán mostrar la información que devuelve el método
devuelveProximoId().
