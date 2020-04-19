        /* int[,] a= new int[3,3] {  {80,70,65} , {50,40,55},{90,80,100} };

            Console.WriteLine(a[0,0].ToString());
            Console.WriteLine(a[0,1].ToString());
            Console.WriteLine(a[0,2].ToString());
            Console.WriteLine(a[1,0].ToString());
            Console.WriteLine(a[1,1].ToString());
            Console.WriteLine(a[1,2].ToString());
            Console.WriteLine(a[2,0].ToString());
            Console.WriteLine(a[2,1].ToString());
            Console.WriteLine(a[2,2].ToString());*/
            
           
           /*if numero % 2 == 0
           
           Console.WriteLine(string.Format("Felipe tem {0} anos de idade e o {0} tem {2}", 34, "Fabricio", 0));


            int [] numero = new int[3];

            Console.WriteLine("digite os valores:");
            numero[0] = Convert.ToInt32(Consol,
            
            e.ReadLine() );
            numero[1] = Convert.ToInt32(Console.ReadLine() );
            numero[2] = Convert.ToInt32(Console.ReadLine() );

            for (int i = 0; i < numero.Length; i++)
            {
                 Console.WriteLine();
                if( numero[i] % 2 == 0)
                {
                    Console.WriteLine(String.Format("este numero {0} é par", numero[i]));
                }
                 else
                 {
                    Console.WriteLine(String.Format("este numero {0} é Impar", numero[i]));
                 }
            
            }*/


            int [] numero = new int[5];
            int soma=0;
            int soma2=0;
            
            Console.WriteLine("digite os valores:");
            for (int i = 0; i < numero.Length; i++)
            {
                numero[i]= Convert.ToInt32(Console.ReadLine());
            }


            for (int i = 0; i < numero.Length; i++)
            {
                if(numero[i] % 2 ==0)
                {
                    soma = soma + numero[i];
                }
                else
                {
                    soma2 = soma2 + numero[i];
                }
                
            }
                Console.WriteLine("as somas dos numeros pares sao " + soma);
                Console.WriteLine("e as somas dos numeros impares sao " + soma2);

            
            Console.WriteLine("os numeros digitados pelo usuario foram:");
            for (int i = 0; i < numero.Length; i++)
            {
                Console.WriteLine( numero[i]);
            }

            

        Console.Read();       
        }

    }
}
