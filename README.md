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
