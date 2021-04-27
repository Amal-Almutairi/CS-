<div dir=rtl>

# كلمة الـ ref :

تُستخدم الكلمة الرئيسية ref في C # لتمرير أو إرجاع مراجع القيم من وإلى الدوال, بمعنى اي تعديل على قيمة المتغير المرجعي داخل الدالة يتم التعديل عليه خارج الدالة لانه يشير الى موقعه اي بمعني لا يقوم بنسخ نسخة جديدة ويبقي الاصلي كما هو ويعدل على النسخة الجديدة
 ## مثال: 
 
<div dir=ltr>

```

using System;

namespace CalculatorApplication

   {

     class NumberManipulator

     {

     public void swap(ref int x, ref int y)

      {

        int temp;


         temp = x; /* save the value of x */

         x = y; /* put y into x */

        y = temp; /* put temp into y */

      }


   static void Main(string[] args)

    {

        NumberManipulator n = new NumberManipulator();

        /* المتغيرات  */

        int a = 100;

        int b = 200;


       Console.WriteLine("Before swap, value of a : {0}", a);

       Console.WriteLine("Before swap, value of b : {0}", b);


       /*استدعاء الدالة */

       n.swap(ref a, ref b);


       Console.WriteLine("After swap, value of a : {0}", a);

       Console.WriteLine("After swap, value of b : {0}", b);


       Console.ReadLine();


     }

  }

}

```
</div>

</div>
