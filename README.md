using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        // تعریف آرایه با برخی عناصر تکراری
        int[] numbers = { 1, 2, 3, 4, 2, 3, 5, 1, 6 };

        // استفاده از HashSet برای ذخیره عناصر منحصر به فرد
        HashSet<int> uniqueNumbers = new HashSet<int>();

        // اضافه کردن عناصر آرایه به HashSet
        foreach (int number in numbers)
        {
            uniqueNumbers.Add(number);
        }

        // چاپ عناصر منحصر به فرد
        Console.WriteLine("عناصر منحصر به فرد:");
        foreach (int uniqueNumber in uniqueNumbers)
        {
            Console.WriteLine(uniqueNumber);
        }
    }
}

