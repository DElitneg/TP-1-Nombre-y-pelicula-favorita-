# TP-1-Nombre-y-pelicula-favorita-




using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;



namespace ConsoleApplication2
{
    class Program
    {
        static void Main(string[] args)
        {

        
            Console.WriteLine("Greetings traveller, what's your name? ");
            String nombre = Console.ReadLine();


            Console.WriteLine("Hello " + nombre);
            Console.Write("What's your favourite movie? ");

            String pelicula = Console.ReadLine();

            Console.WriteLine(nombre + " your movie " + pelicula + " is very bad");
            
        }
    }
} 
