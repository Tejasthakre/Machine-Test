# Machine-Test
My first repository on GitHub.

1st Program Answer:-  

 class Program
    {
        static void Main(string[] args)
        {
            int n, sum = 0, m;
            Console.WriteLine("Enter Your Number");
            n = int.Parse(Console.ReadLine());
            if(n>0)
            {
                m = n % 10;
                sum = sum + m;
                n = n / 10;
            }
            Console.Write("Sum is" + sum);
        }
    }
