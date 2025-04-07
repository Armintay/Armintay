using System;

namespace primeiro;

public class Media
{
    public static void Main(string[] args)
    {
        float soma, media;
        int a = 5;
        int b = 8;
        int c = 9;
        
        soma = a + b + c; 
        
        // Agora imprime a soma corretamente
        Console.WriteLine(soma); 
        
        // Calcular a média
        media = soma / 3; 
        
        // Imprimir a média
        Console.WriteLine(media);
    }
}
