<div dir=rtl>

# كلمة الـ out :

يعمل باتجاه واحد فقط سيتم ارسال المتغير فقط بدون البيانات وسيتم جلب البيانات من الدالة الفرعية. حتى وإن تم اسناد المتغير بقيمة أولية فهنا سيتم تجاهل القيمة الاولية لانه كما ذكرنا سابقا بأن اسناد القيمة الجديدة ستكون في الدالة الفرعي
 ## مثال: 
 
<div dir=ltr>

```

        static void Main(string[] args)
        {
            MethodOut(out int output);// inline out vars in c# 7.0
            WriteLine(output);
            
        }

        private static void MethodOut(out int x)
        {
            // out must be assigned to a value
            //x = x + 5;//compile time erorr: x must be assigned to a value
            x = 5;
            x += 4;
        }

```
</div>

</div>
