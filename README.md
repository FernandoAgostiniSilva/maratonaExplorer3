<h1 align="center">
 Projeto RocketCoffee
</h1>

<br>

![ProjetoFinal](https://github.com/FernandoAgostiniSilva/maratonaExplorer3/blob/main/assets/projetoRocketCoffee.png)

HTML
## O que é HTML?

- Estruturar textos, criar links, imagens, vídeo, etc ...

- Hypertext Markup Language

  Linguagem de marcação de texto

---

## Hypertext

- Hiper texto

- Texto que contém links

---

## Markup

- Marcação do texto

- Elemento HTML ou tag

  Existem inúmeras tags e cada uma deles irá servir para um determinado propósito. Ex.: imagem, texto grande, link, parágrafo, etc...

---

## Sintaxe de uma tag

sinal de menor, nome da tag, sinal de maior, conteúdo, sinal de menor, barra, nome da tag, sinal de maior

```html
<p>conteúdo</p>
```

---

## Atributos

- Adicionam informações e configurações à uma tag

- Sintaxe

  nome do atributo, sinal de igual, aspas duplas (abre), valor, aspas duplas (fecha)

```html
<a href="#">link</a>
```

---

## Comentários

- Ignorar linhas de código

- Adicionar informação

- Somente acessível por quem coda

```html
<!-- Aqui vem um comentário -->
<!--
Várias linhas de código 
poderão ser ignoradas 
ao utilizar comentário
-->
```

CSS
## O que é CSS?

- Apresentação visual para o cliente

- Estilos para o HTML

- Cascading Style Sheets

Folha de Estilo em Cascata

---

## Declaration

- Declaração

  Pedaço de código que irá ditar as propriedades e valores a serem 
aplicadas a um elemento HTML

- Sintaxe

  Seletor, chave (abre), propriedade, dois pontos, valor, ponto vírgula, 
chave (fecha)

```css
body {
  background: red;
}
```

---

## Comentários

- Ignorar parte do código

- Adicionar informações que serão visíveis somente pra quem coda

```css
/* Essa linha será ignorada */

/*
Poderemos ignorar várias 
linhas de código
dessa forma
*/
```

---

## Cascading

- Cascata

  Quando há 2 (ou mais) declarações a última será mais relevante

```css
body {
  background: red;
}

body {
  background: blue;
}
```

---

## Specificity

Especificidade: Cada seletor tem um peso e a soma dos pesos, será levada 
em conta para que determinada declaração seja mais específica


```css
#id {
  /* peso 100 */
}

.class {
  /* peso 10 */
}

element {
  /* peso 1 */
}
```

> A cascata perde prioridade e é priorizada a especificidade da declaração

---

## Box Model

- Tudo são caixas

  Todos os elementos HTML serão considerados uma caixa, assim como uma 
caixa de papelão

- Caixas possuem determinadas propriedades, veja

  Conteúdo, Largura, Altura, Borda, Preenchimento (espaço interno), 
Espaçamento (espaço externo)

---

## Box Model

![Box Model](http://espezua.github.io/blog/imgs/boxmodel.png)
