# Good evening, Tatiana.

// Задача 10: Напишите программу, которая принимает на вход трёхзначное число и на выходе показывает вторую цифру этого числа.

// 456 -> 5
// 782 -> 8
// 918 -> 1
/*
int number = ReadInt("Введите трехзначное число: ");
int amount = number.ToString().Length;
if (amount < 3 || amount > 3)
{
    Console.WriteLine("Вы ввели не трехзначное число");
}
else
{
    Console.WriteLine(InCenter(number));
}
int ReadInt(string message)
{
    Console.Write(message);
    return Convert.ToInt32(Console.ReadLine());
}
int InCenter(int a)
{    
    int result = ((a / 10) % 10);
    return result;
}
*/
/*
// Задача 13: Напишите программу, которая выводит третью цифру заданного числа или сообщает, что третьей цифры нет.
// 645 -> 5
// 78 -> третьей цифры нет
// 32679 -> 6

int numDigit;
int num;
Console.Write("Введите любое число: ");
    num = Convert.ToInt32(Console.ReadLine());
    string numStr = Convert.ToString(num);
    numDigit = numStr.Length;
    if (numDigit > 2) 
    Console.WriteLine($"Третья цифра введённого числа: {numStr[2]}");
    else Console.WriteLine("третьей цифры нет");
*/           
/*
// Задача 15: Напишите программу, которая принимает на вход цифру, обозначающую день недели, и проверяет, является ли этот день выходным.
// 6 -> да
// 7 -> да
// 1 -> нет

    int num;
    Console.Write("Введите число от 1 до 7:");
    num = Convert.ToInt32(Console.ReadLine());

    if (num >= 1 || num <= 7)
{
    if (num == 6 || num == 7) Console.WriteLine("Сегодня выходной");
    else 
    Console.WriteLine("Сегодня рабочий день");
}
    else 
    Console.WriteLine("Не верное число");
*/    
