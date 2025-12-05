# Taller-ultima-generacion
#ejercicio1---------------------------
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine ("Porfavor, digite el nombre completo porfavor");
        string nombre = Console.ReadLine();
        Console.Write ("Hola! ");
        Console.ForegroundColor = ConsoleColor.Red;
        Console.Write (nombre);
        Console.ResetColor();
        Console.Write (" <3");
    }
}



#ejercicio2--------------------------------

using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        string nombre = "Fermain";
        int edad = 19;
        Console.WriteLine (String.Format ("Nombre: {0} Edad: {1} ", nombre, edad));
    }
}



#ejercicio3------------------------------

using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        string nombre = "Fermain";
        int edad = 19;
        Console.WriteLine ("Nombre: " + nombre + " , Edad: " + edad);
    }
}
#ejercicio4--------------------------------
using System;

public class HelloWorld
{
    public static void Main(string[] args)
    {
        Console.WriteLine ("Porfavor, digite el nombre completo porfavor");
        string nombre = Console.ReadLine();
        Console.Write ("Hola! ");
    }
}




-------------------------ejercicio 5---------------------------------

using System;

public class HelloWorld
{
public static void Main(string[] args)
{
Console.WriteLine("Porfavor, digite un numero");
int numero = int.Parse(Console.ReadLine());

    switch (numero)
    {
        case 1:
            Console.WriteLine("Monday");
            break;
        case 2:
            Console.WriteLine("Tuesday");
            break;
        case 3:
            Console.WriteLine("Wednesday");
            break;
        case 4:
            Console.WriteLine("Thursday");
            break;
        case 5:
            Console.WriteLine("Friday");
            break;
        case 6:
            Console.WriteLine("Saturday");
            break;
        case 7:
            Console.WriteLine("Sunday");
            break;
    }
}
}

---------------------------Ejercicio 6--------------------------------
using System;

public class HelloWorld
{
public static void Main(string[] args)
{
int day = 4;
switch (day)
{
case 6:
Console.WriteLine("Saturday");
break;
case 7:
Console.WriteLine("Sunday");
break;
default:
Console.WriteLine("Looking forward to the weekend");
break;
}
}
}

escanear con un botón conectividad con un scanner


--------------------------------------------------------

// Online C# Editor for free
// Write, Edit and Run your C# code using C# Online Compiler

using System;

class Person
{
    private string name;
    public string Name
    {
        get {return name; }
        set { name = value; }
    }
    
    public static void Main(string[] args)
    {
       Person myObj = new Person();
       myObj.Name = "liam";
       Console.WriteLine(myObj.Name);
    }
}
-----------------------------------------------------
using System;
class Car
{
    public string model = "Mustang";
}
class Program
{
        static void Main(string[] args)
        {
            Car myObj = new Car();
            Console.WriteLine(myObj.model);
        }
}

--------------------------------------------------------
using System;
class Car
{
    private string model = "Mustang";
        static void Main(string[] args)
        {
            Car myObj = new Car();
            Console.WriteLine(myObj.model);
        }
}
