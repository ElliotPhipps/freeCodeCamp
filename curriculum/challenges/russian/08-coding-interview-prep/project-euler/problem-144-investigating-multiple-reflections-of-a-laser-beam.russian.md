---
id: 5900f3fc1000cf542c50ff0f
challengeType: 5
title: 'Problem 144: Investigating multiple reflections of a laser beam'
forumTopicId: 301773
localeTitle: 'Задача 144: Исследование множественных отражений лазерного луча'
---

## Description
<section id='description'>
В лазерной физике «белая ячейка» представляет собой зеркальную систему, которая действует как линия задержки для лазерного луча. Луч входит в камеру, отскакивает вокруг зеркал и, в конце концов, возвращается обратно. Конкретная белая ячейка, которую мы будем рассматривать, представляет собой эллипс с уравнением 4x2 + y2 = 100. Раздел, соответствующий началу -0.01 ≤ x ≤ +0.01 наверху, отсутствует, позволяя свету проникать внутрь и выходить через отверстие. <p> Световой пучок в этой задаче начинается в точке (0,0,10,1) непосредственно за белой ячейкой, а луч сначала воздействует на зеркало (1.4, -9.6). Каждый раз, когда лазерный луч попадает на поверхность эллипса, он следует обычному закону отражения «угол падения равен углу отражения». То есть, как падающий, так и отраженный пучки образуют одинаковый угол с нормальной линией в точке падения. На рисунке слева красная линия показывает первые две точки контакта между лазерным лучом и стенкой белой ячейки; синяя линия показывает линию, касательную к эллипсу в точке падения первого отскока. Наклон m касательной линии в любой точке (x, y) данного эллипса равен: m = -4x / y. Обычная линия равна перпендикулярной этой касательной линии в точке падения. Анимация справа показывает первые 10 отражений луча. </p><p> Сколько раз луч попадает на внутреннюю поверхность белой ячейки перед выходом? </p>
</section>

## Instructions
<section id='instructions'>

</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>euler144()</code> should return 354.
    testString: assert.strictEqual(euler144(), 354);

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler144() {
  // Good luck!
  return true;
}

euler144();

```

</div>

</section>

## Solution
<section id='solution'>

```js
// solution required
```

</section>
