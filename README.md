# homework2
namespace homework2
{
    internal class Program
    {
        static void Main(string[] args)
        {

            Console.WriteLine(" welcome  to calkulator ! ");
            Console.WriteLine(" son kiriting  ");
            Console.WriteLine();
            int number = int.Parse(Console.ReadLine());
            Console.WriteLine(" amal kiriting   [ * ] [ / ] [ - ] [+]  ");
            Console.WriteLine();
            char asd = char.Parse(Console.ReadLine());

            Console.WriteLine(" son kiriting ");
            Console.WriteLine();
            int number2 = int.Parse(Console.ReadLine());

            if (asd == '*')
            {
                Console.WriteLine($" sonlar kopaytiruvi {number} * {number2} = {number * number2}    ");

            }
            if (asd == '/')
            {
                Console.WriteLine($"  sonlar boluvi {number} % {number2} = {number / number2}");
            }

            if (asd == '-')
            {
                Console.WriteLine($" sonlar ayruvi {number} - {number2} = {number - number2}");
            }

            if (asd == '+')
            {
                Console.WriteLine($" sonlarni qoshish {number} + {number2} = {number + number2}");
            }


            Main(args);

        }
    }
}
