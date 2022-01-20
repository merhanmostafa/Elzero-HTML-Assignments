## **Assignment 1**

- ما هو العنصر المناسب لوضعه داخل النموذج لإرسال البيانات عند الضغط عليه ؟
  - `<button type="submit">send</button>`  

---

- ما هو العنصر المناسب ليكون عنوان للصفحة كاملة؟
  - `<h1></h1>`

---

- ما هو العنصر المناسب ليكون عنوان لقسم داخل الصفحة؟
  - `<h2></h2>`

---

- ما هو العنصر المناسب ليحتوي على فقرة نصية؟
  - `<p></p>`

---

- كيف تحدد لغة المحتوى الخاص بصفحتك. يمكنك كتابة العنصر الكامل مع ال Attributes الخاصة بتحديد اللغة

```code
<!DOCTYPE html>
 <html lang="en">
   <body>
   
     ...

   </body>
 </html>
```

---

- في عالم ال Accessibility هل الأفضل أن أكتب
  - 10 – 20
  - 10 To 20 :white_check_mark:

---

- إذا كان لديك عنصر Div وتريد الوصول إليه عن الطريق الضغط على ال Tab Button ماذا سوف تفعل في العنصر ؟
  - سوف اضف ال Aria attributes and role

```code
 <div role="checkbox" aria-checked="true" tabindex="0" aria-labelledby="plan1">Plan One</div>
    <label id="plan1">Plan One Label</label>
    <div tabindex="0">Plan Two</div>
    <div tabindex="0">Plan Three</div>
```

---

- ماذا تعني كلمة ARIA
  - It stands for 'Accessible Rich Internet Applications'

---  

## **Assignment 2**

قم بإضافة المعلومات اللازمة على العناصر التالية لتسهيل الوصول للمحتوى بواسطة قاريء الشاشة ( Screen Reader ) مع العلم أن هذه العناصر هي المهارات الخاصة بالشخص وسوف يتم الإختيار من بينها.

```code
<div class="choose-skill">
  <div class="skill">Python</div>
  <label>Skill One</label>
  <div class="skill">PHP</div>
  <label>Skill Two</label>
  <div class="skill">JavaScript</div>
  <label>Skill Three</label>
</div>
```
