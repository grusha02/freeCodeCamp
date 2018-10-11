---
id: 5900f54a1000cf542c51005c
challengeType: 5
title: 'Problem 477: Number Sequence Game'
videoUrl: ''
localeTitle: 'Проблема 477: Игра с порядковым номером'
---

## Description
<section id="description"> Игра с порядковым номером начинается с последовательности S из N чисел, написанных на линии. Два игрока чередуют обороты. В свою очередь игрок должен выбрать и удалить либо первый, либо последний номер, оставшийся в последовательности. Счет игрока - это сумма всех чисел, которые он сделал. Каждый игрок пытается максимизировать свою собственную сумму. Если N = 4 и S = ​​{1, 2, 10, 3}, то каждый игрок максимизирует свой результат следующим образом: Игрок 1: удаляет первое число (1) Игрок 2: удаляет последнее число из оставшейся последовательности (3) Игрок 1: удаляет последний номер из оставшейся последовательности (10) Игрок 2: удаляет оставшееся число (2). Счет 1 игрока равен 1 + 10 = 11. Пусть F (N) - счет игрока 1, если оба игрока следуют оптимальная стратегия для последовательности S = ​​{s1, s2, ..., sN}, определяемая как: s1 = 0 si + 1 = (si2 + 45) по модулю 1 000 000 007 Последовательность начинается с S = {0, 45, 2070 , 4284945, 753524550, 478107844, 894218625, ...}. Вам дается F (2) = 45, F (4) = 4284990, F (100) = 26365463243, F (104) = 2495838522951. Найдите F (108). </section>

## Instructions
undefined

## Tests
<section id='tests'>

```yml
tests:
  - text: ''
    testString: 'assert.strictEqual(euler477(), 25044905874565164, "<code>euler477()</code> should return 25044905874565164.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function euler477() {
  // Good luck!
  return true;
}

euler477();

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>