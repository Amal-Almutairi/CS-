<div dir=rtl>

# كلمة الـ Abstract :

هو أسلوب يستخدم لإخفاء تفاصيل تنفيذ البرنامج. و كلمة Abstract تستخدم في class & method.

## Abstract class
-  الكلاس لا يمكن إنشاء كائنات منه (للإستفادة من هذا الكلاس, يجب وراثته)

## Abstract Method
 - يمكن ان تستخدم فقط في Abstract class.
 -  لا تملك أقواس بداية و نهاية { } ويوضع علامة ; بدل الأقواس 


 ## مثال: 
 
<div dir=ltr>

```
 abstract class Animal 
{
  public abstract void animalSound();
  public void sleep() 
  {
    Console.WriteLine("Zzz");
  }
}
```
</div>

</div>
