<div dir=rtl>

# كلمة الـ override :
  تعريف الدالة التي ورثها من الـ الفئة الأب من جديد, هذه الدالة الجديدة تكون مشابهة للدالة الموروثة من حيث الشكل فقط, أي لها نفس الإسم و النوع و عدد الباراميترات, لكن محتواها مختلف


 ## مثال: 
 
<div dir=ltr>

```
abstract class Shape
{
    public abstract int GetArea();
}

class Square : Shape
{
    int side;

    public Square(int n) => side = n;

    // GetArea method is required to avoid a compile-time error.
    public override int GetArea() => side * side;

    static void Main()
    {
        var sq = new Square(12);
        Console.WriteLine($"Area of the square = {sq.GetArea()}");
    }
}
```
</div>

</div>
