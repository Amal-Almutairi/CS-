<div dir=rtl>

# كلمة الـ params :

يتم استخدام الParams عندما لا نعلم كم عدد الparameteres التي سيتم تمرريرها بواسطه المستخدم.وعندما نستخدم object يتم قبول اي نوع من البيانات

- لا تشترط تحديد عدد البراميترز


 ## مثال: 
 
<div dir=ltr>

```
// function containing params parameters
    public static int Add(params int[] ListNumbers)
    {
        int total = 0;
          
        // foreach loop
        foreach(int i in ListNumbers) 
        {
            total += i;
        }
        return total;
    }
          
    static void Main(string[] args)
{
      
    // Calling function by passing 5
    // arguments as follows
    int y = Add(12,13,10,15,56);
      
    // Displaying result
    Console.WriteLine(y);
}      
```
</div>

</div>
