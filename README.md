using System;

internal class Program
{
    private static void Main()
    {
        // Declarar um array de 6 inteiros
        int[] numeros = new int[6];
        int soma = 0;

        // Solicitar que o usuário insira 6 números
        for (int i = 0; i < 6; i++)
        {
            Console.WriteLine($"Digite o {i + 1}º número:");
            numeros[i] = int.Parse(Console.ReadLine());
        }

        // Calcular a soma de todos os números
        for (int i = 0; i < 6; i++)
        {
            soma += numeros[i];
        }

        // Exibir o resultado da soma
        Console.WriteLine($"A soma dos números inseridos é: {soma}");
    }
}
