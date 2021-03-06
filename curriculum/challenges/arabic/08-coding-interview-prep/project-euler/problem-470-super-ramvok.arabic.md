---
id: 5900f5431000cf542c510055
challengeType: 5
title: 'Problem 470: Super Ramvok'
videoUrl: ''
localeTitle: 'المشكلة 470: سوبر رامفوك'
---

## Description
<section id="description"> تأمل لعبة واحدة من Ramvok: <p style=";text-align:right;direction:rtl"> دع t تمثل الحد الأقصى لعدد مرات تشغيل اللعبة. إذا كانت t = 0 ، تنتهي اللعبة على الفور. خلاف ذلك ، في كل دور أنا ، لاعب يلف يموت. بعد التدحرج ، إذا كان بإمكان اللاعب إيقاف اللعبة وتلقي جائزة تساوي قيمة اللفة الحالية ، أو تجاهل اللفة وحاول مرة أخرى الدور التالي. إذا كانت t = t ، فلا يمكن تجاهل اللفة ويجب قبول الجائزة. قبل أن تبدأ اللعبة ، يتم اختيار t من قبل اللاعب ، الذي يجب أن يدفع بعد ذلك التكلفة المبدئية مقابل بعض ثابت c. بالنسبة إلى c = 0 ، يمكن اختيار t ليكون غير محدود (بتكلفة أولية من 0). لندع R (d، c) هو الربح المتوقع (أي الربح الصافي) الذي يستلمه اللاعب من لعبة واحدة لعبها Ramvok على النحو الأمثل ، بالنظر إلى وجود نقيض عدل من جانب الجانب وثابت التكلفة c. على سبيل المثال ، R (4، 0.2) = 2.65. نفترض أن اللاعب لديه أموال كافية لدفع أي / جميع التكاليف المسبقة. </p><p style=";text-align:right;direction:rtl"> الآن فكر في لعبة سوبر رامفوك: </p><p style=";text-align:right;direction:rtl"> في سوبر رامفوك ، لعبت لعبة رامفوك مرارا وتكرارا ، ولكن مع تعديل طفيف. بعد كل لعبة ، يتم تغيير القالب. عملية التحويل هي كما يلي: يتم لف القالب مرة واحدة ، وإذا كان الوجه الناتج مرئيًا بنقاطه ، فسيتم تغيير هذا الوجه ليكون فارغًا بدلاً من ذلك. إذا كان الوجه فارغًا بالفعل ، فسيتم تغييره إلى قيمته الأصلية. بعد إجراء التغيير ، يمكن أن تبدأ لعبة أخرى من Ramvok (وأثناء هذه اللعبة ، في كل دور ، يتم لف القالب حتى يظهر وجه له قيمة عليه). يعرف اللاعب الوجوه الفارغة وغير الموجودة في جميع الأوقات. تنتهي لعبة Super Ramvok عندما تكون جميع وجوه الموت فارغة. </p><p style=";text-align:right;direction:rtl"> دع S (d، c) هو الربح المتوقع الذي يتلقاها اللاعب من لعبة Super Ramvok التي تم لعبها على النحو الأمثل ، وذلك نظرًا لأن القالب عدل من جانب d-sided للبدء (مع رؤية جميع الأطراف) ، والتكلفة الثابتة c. على سبيل المثال ، S (6 ، 1) = 208.3. </p><p style=";text-align:right;direction:rtl"> Let F (n) = ∑4≤d≤n ∑0≤c≤n S (d، c). </p><p style=";text-align:right;direction:rtl"> حساب F (20) ، مقربة إلى أقرب عدد صحيح. </p></section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: يجب أن يقوم <code>euler470()</code> بإرجاع 147668794.
    testString: 'assert.strictEqual(euler470(), 147668794, "<code>euler470()</code> should return 147668794.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler470() {
  // Good luck!
  return true;
}

euler470();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
