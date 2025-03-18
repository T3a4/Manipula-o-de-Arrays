using System;

internal class Program
{
    private static void Main(string[] args)
    {
        int[] numeros = new int[6];

        // Inserir 6 números inteiros 
        Console.WriteLine("Digite 6 números == pressione Enter para cada número == ");
        Console.Write("Leia 6 números == pressione Enter para cada número == ");

        // Preencher e processar vetor de inteiros
        int[] vetor = new int[6];
        int soma = 0;

        // Calcular a soma
        foreach (int num in vetor)
        {
            soma = soma + num;
        }

        // Exibir resultado
        Console.WriteLine("\nSoma de todos os números: * + soma");
        {

        }
    }
}
