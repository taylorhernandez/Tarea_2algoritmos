using System;

public class conversiones
{
    public static void Main()
    {
        float primerNumero, segundoNumero, tercerNumero, cuartoNumero;
        float val = (float)10;
        float vall = (float)1598.922;
        float operacion1, operacion2, operacion;

        Console.WriteLine("Ingrese la cantidad de distancia");
        primerNumero = Convert.ToSingle(Console.ReadLine());
        
        Console.WriteLine("Ingrese la cantidad en horas");
        segundoNumero = Convert.ToSingle(Console.ReadLine());

        Console.WriteLine("Ingrese la cantidad de minutos");
       tercerNumero = Convert.ToSingle(Console.ReadLine());

        Console.WriteLine("Ingrese la cantidad de segundos");
        cuartoNumero = Convert.ToSingle(Console.ReadLine());


        operacion1 = primerNumero / (cuartoNumero / val);
        Console.WriteLine("Su velocidad en metros de {0} {1} es {2}  ", primerNumero, cuartoNumero, operacion1);

        operacion2 = primerNumero / (segundoNumero*vall);
        Console.WriteLine("Su velocidad en metros de {0} {1} es {2}",  primerNumero, segundoNumero, operacion2);
          

          operacion = primerNumero / (tercerNumero * val); 
          Console.WriteLine("Su velocidad en metros de {0} {1} es {2}",  primerNumero, tercerNumero, operacion);
          Console.ReadLine();

    }
}

