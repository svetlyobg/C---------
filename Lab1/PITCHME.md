<!-- $theme: gaia -->

# Лабораторно упражение 1
## Задача за изпълнение 1

Напишете програма, която чете едно число от конзолата и определя дали то е четно или нечетно.

---

## Задача за изпълнение 2
Напишете програма, която чете от конзолата радиуса "r" на кръг и отпечатва неговия периметър и обиколка.

```csharp
﻿using System;


namespace lab1_2
{
    class Program
    {
        static void Main()
        {
            Console.WriteLine("Enter radius: ");
            double r = double.Parse(Console.ReadLine());
            double S = (Math.PI * Math.Pow(r, 2));
            Console.WriteLine($"The area of the circle is: {S}");
            double P = (2 * Math.PI * r);
            Console.WriteLine($"The lenght of the circle is: {P}");
        }
    }
}
```

---

## Задача за изпълнение 3
Напишете програма, която чете 10 числа от конзолата и отпечатва най-голямото от тях.