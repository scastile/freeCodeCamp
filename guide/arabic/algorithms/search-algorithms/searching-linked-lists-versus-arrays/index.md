---
title: Searching Linked Lists Versus Arrays
localeTitle: البحث عن القوائم المرتبطة مقابل الصفائف
---
## البحث عن القوائم المرتبطة مقابل الصفائف

افترض أن عليك البحث عن عنصر في قائمة و صف _مصفوف_ غير _مرتب_ . في هذه الحالة ، تحتاج إلى إجراء بحث خطي (تذكر ، لم يتم فرزها). سيكون إجراء بحث خطي لعنصر في بنية البيانات إما عملية O (n).

الآن إذا كان لديك قائمة مرتبطة _فرزها_ وطائفة، لا يزال بإمكانك البحث في كل من هياكل البيانات في O (سجل ن) وقت باستخدام ثنائي البحث. على الرغم من ذلك ، سيكون مملاً قليلاً إلى رمز أثناء استخدام القوائم المرتبطة.

عادةً ما يتم تفضيل القوائم المرتبطة على المصفوفات حيث يكون الإدراج عملية متكررة. من الأسهل إدراجها في القوائم المرتبطة حيث يتغير مؤشر فقط. ولكن لإدراجها في صفيف (الوسط أو البداية) ، تحتاج إلى نقل جميع العناصر بعد المصفوفة التي قمت بإدخالها. مكان آخر حيث يجب عليك استخدام قوائم مرتبطة هو حيث حجم غير مؤكد (لا تعرف الحجم عند البدء) ، لأن الصفائف لها حجم ثابت.

توفر الصفائف مزايا قليلة على القوائم المرتبطة:

1.  دخول عشوائي
2.  ذاكرة أقل مقارنة بالقوائم المرتبطة
3.  تحتوي المصفوفة على موقع محلي أفضل لذا توفر أداءً أفضل

يعتمد بشكل كامل على حالة الاستخدام سواء كانت المصفوفات أو القوائم المرتبطة أفضل.

### معلومات اكثر:

*   نهج المبرمج من النظر في قائمة مرتبطة مقابل صفيف: [المهوسون المهوسون](http://www.geeksforgeeks.org/programmers-approach-looking-array-vs-linked-list/)