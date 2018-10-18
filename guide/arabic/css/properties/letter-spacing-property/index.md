---
title: Letter Spacing Property
localeTitle: خاصية تباعد الأحرف
---
## خاصية تباعد الأحرف

تقوم خاصية تباعد الحروف بتعديل المسافة بين كل الحروف في كتلة النص. ويشار إليه أيضًا باسم "التعقب" في شروط الطباعة وفي البرامج ذات خيارات إعداد النوع المتقدمة. يقبل الموقع قيم طول `px` و `em` ، بما في ذلك القيم السالبة.

 `.first-example { 
  letter-spacing: 3px; 
 } 
 .second-example { 
  letter-spacing: -1px; 
 } 
 .third-example { 
  letter-spacing: 0.5em; 
 } 
` 

![نتيجة CSS](https://github.com/kaithrendyle/guide-photos/blob/master/letter-spacing.png)

بشكل عام ، من الجيد استخدام الوحدات النسبية ( `em` ) نظرًا لأن التباعد سيكون دائمًا بالنسبة لحجم الخط الذي أعلنته.

من المهم مراعاة الوضوح عند ضبط تباعد الأحرف. إذا كانت الحروف متقاربة جدًا مع بعضها ، فيمكن أن تبدو مكتظة أو صعبة القراءة. من ناحية أخرى ، إذا كانت الحروف متباعدة جدًا ، فقد لا تقرأ ككلمة ، بل كحرف فردي. قد يؤثر هذا أيضًا في كيفية قراءة قارئي الشاشة للنص بصوت مرتفع للأشخاص الذين يعانون من ضعف في الرؤية.

بشكل عام ، لا تحتاج الأحرف الصغيرة عادةً إلى ضبط المسافات بين الحروف. قد تجد حاجة إلى إجراء تعديلات عند استخدام أقسام من الأحرف الكبيرة إذا كانت المسافات تبدو ضيقة للغاية.

#### معلومات اكثر: