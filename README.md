using System;

//this program is a specialized calculator for the quadratic formula

//X = (-b + sqr(b^2 - 4ac)) / 2a

public class Quadratic_Calculator{

    static void Main(String[] args){

        Console.WriteLine("This is a standard quadratic equation formula calculator. The format should be Y = Ax^2 + Bx + C"); //introduction

        Console.WriteLine("What is your A value?"); 
        double A_Value = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("What is your B value?");
        double B_Value = Convert.ToDouble(Console.ReadLine());

        Console.WriteLine("What is your C value?");
        double C_Value = Convert.ToDouble(Console.ReadLine());

        double X1 = (-B_Value + Math.Sqrt(Math.Pow(B_Value, 2) - 4 * (A_Value * C_Value))) / 2;

        double X2 = (-B_Value - Math.Sqrt(Math.Pow(B_Value, 2) - 4 * (A_Value * C_Value))) / 2;

        Console.WriteLine(X1);
        Console.WriteLine(X2);


        //make the other x2 negative tomorrow

    }

}
