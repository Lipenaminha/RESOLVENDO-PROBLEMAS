class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("DIGITE A PRIMEIRA NOTA");
        int nota1 = int.Parse(Console.ReadLine());

        Console.WriteLine("DIGITE A SEGUNDA NOTA");
        int nota2 = int.Parse(Console.ReadLine());


        int NotaFinal = nota1 + nota2;

        Console.WriteLine("DIGITE A NOTA FINAL " + NotaFinal); 

        if(NotaFinal < 60){
            Console.WriteLine("REPROVADO!!!");
        } 
    }
}

