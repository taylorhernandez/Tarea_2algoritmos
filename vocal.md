using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

class ejercicio9
{
    static void Main(string[]args)
    {

        string letra;
        
        Console.WriteLine("INGRESE UNA LITERAL:");
        letra = Console.ReadLine();
        char c = (char)Console.Read();
        if (letra == "a" || letra == "e" || letra == "i" || letra == "o" || letra == "u" || char.IsLetter (c) || (char.IsLower (c)))
                    
        {
            Console.WriteLine ("es vocal");
            Console.WriteLine("la letra es minuscula");
        } 
        else 
        {

            Console.WriteLine ("!no es vocal!");
            Console.WriteLine("la letra es mayuscula");
            Console.ReadLine();


        }
           Console.ReadKey();
    }
  }


