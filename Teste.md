# Testando a linguagem Markdown



## Para criarmos títulos -  Usamos o # que dever ser colocado antes daquilo que seria o seu título.


# Título de nível 1; <pre> use 1 # - exemplo: # Título de nível 1</pre>
## Título de nível 2; <pre> use 2 ## - exemplo: ## Título de nível 2</pre>
### Título de nível 3; <pre> use 3 ### - exemplo: ### Título de nível 3</pre>
#### Título de nível 4; <pre> use 4 #### - exemplo: #### Título de nível 4</pre>
##### Título de nível 5; <pre> use 5 ##### - exemplo: ##### Título de nível 5</pre>


Dá pra fazer assim também;

Título de nível 1
==================

<pre>
Título de nível 1
==================
</pre>

Título de nível 2
------------------

<pre> 
Título de nível 2
------------------
</pre>


***


## Para ênfase -  Usamos o * ou _

*Ênfase* 
<pre> *Ênfase* </pre> 
ou
_Ênfase_ 
<pre> _Ênfase_ </pre>

## Para forte ênfase -  Usamos o ** ou __

**Forte Ênfase** 
<pre> **Ênfase** </pre> 
ou
__Forte Ênfase__ 
<pre> __Ênfase__ (dois _)</pre>


***


## Criando links 

[site do curso em video](https://www.cursoemvideo.com/)

<pre> Faça assim: [site do curso em vídeo](https://www.cursoemvideo.com/)</pre>

Se não for colocar um link em um texto, apenas colocar um link direto você pode colocá-lo diretamente dentro dos sinais de  < >
<https://www.cursoemvideo.com>

<pre> Faça assim: < https://www.cursoemvideo.com > </pre>

## Criando citações

> Aqui temos um exemplo de citação

<pre> Para citações fça assim: > sua citação </pre>


***


## Para gerar texto tachado

~~texto tachado~~

<pre> Faça assim: ~~texto tachado~~ </pre>

***

## Quer gerar uma linha horizontal para dividir partes do seu documento? Também é possível!

***

<pre>Faça assim: *** </pre>
ou
<pre>Faça assim: --- </pre>


***


## Para lista numerada

1. Item 1
914778. Item 2
102945454. Item 3
3. Item 4

Use um número positivo inteiro qualquer e um ponto (.)

<pre>Faça assim;

1. Item 1
914778. Item 2
102945454. Item 3
3. Item 4
</pre>


E para criar um subitem adicione 3 espaços na frente do número


1. Item 1
   1. subitem 
   2. subitem
2. Item 2


<pre>Faça assim;

1. Item 1
   1. subitem 
   2. subitem
2. Item 2
</pre>


***


## Para lista demarcada

Use 1 asterisco (*) antes

* Lista
* Lista
   * Lista
* Lista

<pre>Faça assim;

* Lista
* Lista
   * Lista
* Lista
</pre>



***


## Para lista de tarefas

Use 1 traço e abra e feche colchetes ([ ]) antes

- [ ] Tarefa 1
- [ ] Tarefa 2
- [ ] Tarefa 3

<pre>Faça assim;

- [ ] Tarefa 1
- [ ] Tarefa 2
- [ ] Tarefa 3
</pre>


- [x] Tarefa 1
- [x] Tarefa 2
- [x] Tarefa 3

<pre>Para "tickar" a caixinha faça assim;

- [x] Tarefa 1
- [x] Tarefa 2
- [x] Tarefa 3
</pre>


***


## Para adicionar trechos de códigos

~~~html
Linha de código HTML
~~~

```javascript
Linha de código JavaScript
```

~~~php
Linha de código PHP
~~~


<pre>Faça assim;

~~~html
Linha de código HTML
~~~

```javascript
Linha de código JavaScript
```

~~~php
Linha de código PHP
~~~
</pre>


***


## Criando tabela

Produto | Preço     | Qtde | Total
------- | --------- | ---- | ----------
Mouse   | R$ 100,00 | 3    | R$ 300,00
Teclado | R$ 200,00 | 5    | R$ 1000,00
Monitor | R$ 500,00 | 4    | R$ 2000,00

<pre>Faça assim;

Produto | Preço     | Qtde | Total
------- | --------- | ---- | ----------
Mouse   | R$ 100,00 | 3    | R$ 300,00
Teclado | R$ 200,00 | 5    | R$ 1000,00
Monitor | R$ 500,00 | 4    | R$ 2000,00
</pre>

Você pode especificar o tipo de alinhamento que deseja, basta utilizar : ao lado do campo horizontal de hífens ---, na segunda linha da sua tabela. Veja abaixo:

Alinhado a esquerda: usar **:** no lado esquerdo (alinhamento padrão);
Alinhado a direita: usar **:** no lado direito;
Centralizado: usar **:** dos dois lados.

Produto | Preço     | Qtde | Total
:------- | :---------: | :----: | ----------:
Mouse   | R$ 100,00 | 3    | R$ 300,00
Teclado | R$ 200,00 | 5    | R$ 1000,00
Monitor | R$ 500,00 | 4    | R$ 2000,00

<pre>Faça assim;

Produto | Preço     | Qtde | Total
:------- | :---------: | :----: | ----------:
Mouse   | R$ 100,00 | 3    | R$ 300,00
Teclado | R$ 200,00 | 5    | R$ 1000,00
Monitor | R$ 500,00 | 4    | R$ 2000,00
</pre>