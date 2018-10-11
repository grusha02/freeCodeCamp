---
id: bad87fee1348bd9aedf08816
title: Link to External Pages with Anchor Elements
challengeType: 0
videoUrl: ''
localeTitle: Link para páginas externas com elementos âncora
---

## Description
<section id="description"> Você pode usar elementos de <code>anchor</code> para vincular a conteúdo fora da sua página da web. <code>anchor</code> elementos <code>anchor</code> precisam de um endereço da Web de destino chamado atributo <code>href</code> . Eles também precisam de texto âncora. Aqui está um exemplo: <code>&lt;a href=&quot;https://freecodecamp.org&quot;&gt;this links to freecodecamp.org&lt;/a&gt;</code> Então o seu navegador irá exibir o texto <strong>&quot;este links para freecodecamp.org&quot;</strong> como um link que você pode clicar. E esse link levará você ao endereço da Web <strong>https://www.freecodecamp.org</strong> . </section>

## Instructions
<section id="instructions"> Crie <code>a</code> elemento que vincule a <code>http://freecatphotoapp.com</code> e tenha &quot;cat photos&quot; como <code>anchor text</code> . </section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Sua <code>a</code> elemento deve ter o <code>anchor text</code> de &quot;fotos do gato&quot;.
    testString: 'assert((/cat photos/gi).test($("a").text()), "Your <code>a</code> element should have the <code>anchor text</code> of "cat photos".");'
  - text: 'Você precisa de <code>a</code> elemento que <code>http://freecatphotoapp .com</code> para <code>http://freecatphotoapp .com</code>'
    testString: 'assert(/http:\/\/(www\.)?freecatphotoapp\.com/gi.test($("a").attr("href")), "You need an <code>a</code> element that links to <code>http&#58;//freecatphotoapp<wbr>.com</code>");'
  - text: Verifique se o seu <code>a</code> elemento tem uma marca de fechamento.
    testString: 'assert(code.match(/<\/a>/g) && code.match(/<\/a>/g).length === code.match(/<a/g).length, "Make sure your <code>a</code> element has a closing tag.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<h2>CatPhotoApp</h2>
<main>



  <img src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back.">

  <p>Kitty ipsum dolor sit amet, shed everywhere shed everywhere stretching attack your ankles chase the red dot, hairball run catnip eat the grass sniff.</p>
  <p>Purr jump eat the grass rip the couch scratched sunbathe, shed everywhere rip the couch sleep in the sink fluffy fur catnip scratched.</p>
</main>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>