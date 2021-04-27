<div dir=rtl>

# كلمة الـ Continue :

يسمح لنا بتخطي جزء من حلقة التكرار عند حدوث عامل خارجي، لكن إكمال بقية الحلقة إلى نهايتها. بعبارةٍ أخرى: سينتقل تنفيذ البرنامج إلى أوّل حلقة التكرار عند تنفيذ التعبير continue.

 ## مثال: 
 
<div dir=ltr>

```

number = 0

for number in range(10):
   number = number + 1

   if number == 5:
      continue    # continue here

   print('Number is ' + str(number))

print('Out of loop')

```
</div>

</div>
