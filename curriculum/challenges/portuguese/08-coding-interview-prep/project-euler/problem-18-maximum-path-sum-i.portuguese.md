---
id: 5900f37e1000cf542c50fe91
challengeType: 5
title: 'Problem 18: Maximum path sum I'
videoUrl: ''
localeTitle: 'Problema 18: soma do caminho máximo I'
---

## Description
<section id="description"> Começando no topo do triângulo abaixo e movendo-se para números adjacentes na linha abaixo, o total máximo de cima para baixo é 23 <span style="display: block; text-align: center;"><b style="color: red;">.</b> <br> <b style="color: red;">7</b> 4 <br> 2 <b style="color: red;">4</b> 6 <br> 8 5 <b style="color: red;">9</b> 3</span> Ou seja, 3 + 7 + 4 + 9 = 23. Encontre o total máximo de cima para baixo do triângulo abaixo: <span style="display: block; text-align: center;">75 <br> 95 64 <br> 17 47 82 <br> 18 35 87 10 <br> 20 04 82 47 65 <br> 19 01 23 75 03 34 <br> 88 02 77 73 07 63 67 <br> 99 65 04 28 06 16 70 92 <br> 41 41 26 56 83 40 80 70 33 <br> 41 48 72 33 47 32 37 16 94 29 <br> 53 71 44 65 25 43 91 52 97 51 14 <br> 70 11 33 28 77 73 17 78 39 68 17 57 <br> 91 71 52 38 17 14 91 43 58 50 27 29 48 <br> 63 66 04 68 89 53 67 30 73 16 69 87 40 31 <br> 04 62 98 27 23 09 70 98 73 93 38 53 60 04 23</span> <b>NOTA:</b> Como existem apenas 16384 rotas, é possível resolver este problema tentando todas as rotas. No entanto, o Problema 67 é o mesmo desafio com um triângulo contendo cem linhas; não pode ser resolvido pela força bruta, e requer um método inteligente! o) </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>maximumPathSumI(testTriangle)</code> deve retornar 23.
    testString: 'assert.strictEqual(maximumPathSumI(testTriangle), 23, "<code>maximumPathSumI(testTriangle)</code> should return 23.");'
  - text: <code>maximumPathSumI(numTriangle)</code> deve retornar 1074.
    testString: 'assert.strictEqual(maximumPathSumI(numTriangle), 1074, "<code>maximumPathSumI(numTriangle)</code> should return 1074.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function maximumPathSumI(triangle) {
  // Good luck!
  return true;
}

const testTriangle = [[3, 0, 0, 0],
                      [7, 4, 0, 0],
                      [2, 4, 6, 0],
                      [8, 5, 9, 3]];

maximumPathSumI(testTriangle);

```

</div>

### Before Test
<div id='js-setup'>

```js
const numTriangle = [[75, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [95, 64, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [17, 47, 82, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [18, 35, 87, 10, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [20, 4, 82, 47, 65, 0, 0, 0, 0, 0, 0, 0, 0, 0, 0], [19, 1, 23, 75, 3, 34, 0, 0, 0, 0, 0, 0, 0, 0, 0], [88, 2, 77, 73, 7, 63, 67, 0, 0, 0, 0, 0, 0, 0, 0], [99, 65, 4, 28, 6, 16, 70, 92, 0, 0, 0, 0, 0, 0, 0], [41, 41, 26, 56, 83, 40, 80, 70, 33, 0, 0, 0, 0, 0, 0], [41, 48, 72, 33, 47, 32, 37, 16, 94, 29, 0, 0, 0, 0, 0], [53, 71, 44, 65, 25, 43, 91, 52, 97, 51, 14, 0, 0, 0, 0], [70, 11, 33, 28, 77, 73, 17, 78, 39, 68, 17, 57, 0, 0, 0], [91, 71, 52, 38, 17, 14, 91, 43, 58, 50, 27, 29, 48, 0, 0], [63, 66, 4, 68, 89, 53, 67, 30, 73, 16, 69, 87, 40, 31, 0], [4, 62, 98, 27, 23, 9, 70, 98, 73, 93, 38, 53, 60, 4, 23]];

```

</div>


</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
