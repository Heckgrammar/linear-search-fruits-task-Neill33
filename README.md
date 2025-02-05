static void Main(string[] args)
{
    string[] fruits = { "banana", "apple", "orange", "pear", "grape", "pineapple" };
    Console.WriteLine("What word would you like to find?");
    string userword = Console.ReadLine();
    
    bool found = false;

    for (int i = 0; i < fruits.Length; i++)
    {
        if (fruits[i] == userword)
        {
            found = true;
            break;
        }
    }

    Console.WriteLine(found);

}
