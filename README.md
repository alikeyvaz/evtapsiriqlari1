# evtapsiriqlari1

#region 1. hem 3e ve 7e bolunsun

//{
//    if (i % 3 == 0 || i % 7 == 0)
//    {
//        Console.WriteLine("bolnur");
//    }

//    else
//    {
//        Console.WriteLine("bolunmur");
//    }
//}

#endregion

#region 2. 100 ve 200 arasinda tek ededlerin sayini tapib consola cixarin (for loop)

//for (int n = 100; n <= 200; n++)
//    if (n % 2 == 0)
//    {
//        Console.WriteLine(n);
//    }
#endregion

#region 3. Verilmish int arrayinin en boyuk reqemini tapin.

//int[] arr = { 4, 77, 12, 21, 8, 89, 121 };
//int enboyuk = arr[0];
//for (int i = 0; i < arr.Length; i++)
//{
//    if (arr[i] > enboyuk)
//        enboyuk = arr[i];
//}
//Console.WriteLine(enboyuk);

#endregion

#region 4. Verilmish int arrayinin en kichik reqemini tapin. int[] arr

int[] arr = { 4, 77, 12, 21, 8, 89, 121 };
int enkicik = arr[0];
for (int i = 0; i < arr.Length; i++)
{
    if (arr[i] < enkicik)
        en = arr[i];
}
Console.WriteLine(enkicik);

#endregion
