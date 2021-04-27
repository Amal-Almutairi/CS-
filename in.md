<div dir=rtl>

# كلمة الـ In :


تؤدي الكلمة الأساسية in إلى تمرير الوسائط بواسطة المرجع ولكنها تضمن عدم تعديل الوسيطة.  إنه يشبه الكلمات الأساسية ref أو out ، باستثناء أنه لا يمكن تعديل الوسيطات بالطريقة المطلوبة. في حين يمكن تعديل وسيطات المرجع ، يجب تعديل الوسيطات الخارجية بالطريقة التي تم استدعاؤها
 ## مثال: 
 
<div dir=ltr>

```
int readonlyArgument = 44;
InArgExample(readonlyArgument);
Console.WriteLine(readonlyArgument);     // value is still 44

void InArgExample(in int number)
{
    // Uncomment the following line to see error CS8331
    //number = 19;
}

```
</div>

</div>
