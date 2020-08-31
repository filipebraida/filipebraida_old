---
layout: page
title: Texto científico
subtitle: Dicas sobre a escrita científica para a monografia
---

No trabalho de PÁVIA [[1]](#1), a pesquisa científica é definida como:
> Tomada num sentido amplo, pesquisa é toda atividade voltada para a solução de problemas; como atividade de busca, indagação, inquirição da realidade, é a atividade que vai nos permitir, no âmbito da ciência, elaborar um conhecimento, ou um conjunto de conhecimentos, que nos auxilie na compreensão desta realidade e nos oriente em nossas ações.

Assim, 
uma etapa fundamental da pesquisa científica é a construção de relatórios para registrar e documentar o processo e as suas descobertas para a comunidade.
Esses textos possuem diversas características em comum como sua forma e o padrão de escrita.
Desta forma, é chamado de __texto científico__ para esse tipo de texto que é utilizado no meio científico.

O texto científico possui um escopo específico.
O conteúdo é direcionado para abordar fatos científicos, 
como resultados de um estudo, pesquisa ou trabalho que tenha a ver com conhecimento científico. 
O texto pode falar sobre ideias, procedimentos, resultados ou descobertas.

Uma monografia é um texto científico, ou seja, é um relatório técnico que irá explicar os procedimentos e resultados do projeto final.
O leitor precisa entender o conteúdo desse texto sem precisar tentar adivinhar ou supor alguma informação.
Desta maneira, a escrita precisa ser direta e não pode ser ambígua. 
O importante do texto é mostrar com precisão o relato científico ao leitor.

ACHISMO

Um aspecto fundamental é sobre a construção das frases.
Somos acostumados a achar frases longas mais elegantes,
e somos influenciados a achar que essa característica pode deixar o texto mais rico.
Dependendo do tamanho das frases, mais complexas ela se tornam para manter a coerência e a coesão.
Dependendo da situação, 
é válido quebrar as frases para tornar o texto mais simples e direto, evitando assim ambiguidade.

Outra dica é quebrar as frases no LaTeX.
O compilador do LaTeX só considera uma frase quando existe uma linha vazia. 
Desta forma,
é muito útil quebrar as frases do parágrafo, 
facilitando tanto a construção do texto quanto sua revisão.
Fica mais fácil de ver as conexões das frases desta maneira e, assim,
naturalmente o texto vai ficando mais coeso.
Segue abaixo um exemplo prático.

>
      Lorem ipsum dolor sit amet, 
      consectetur adipiscing elit. 
      Nulla ut est velit. 
      Cras vehicula at augue a pharetra. 
      Aenean consectetur elit sed ipsum euismod aliquet. 
      Vivamus sollicitudin ullamcorper ullamcorper,
      phasellus ut augue nec tellus rhoncus facilisis. 


Dependendo do trabalho, o texto final pode conter inúmeras páginas e pode se tornar uma leitura tediosa.
Contudo, um texto científico deve ser de fácil acesso e possuir uma leitura fluida.
Com o objetivo de amenizar esse problema,
a construção dos parágrafos precisa ser uniforme, ou seja, 
o tamanho do parágrafo precisa manter um padrão.
Desta maneira, a leitura se torna ritmada, facilitando o leitor nessa tarefa.
É claro que existem alguns momentos de exceção, mas pode-se tentar uma média de cinco linhas por parágrafo.
A Imagem 1 demonstra um exemplo de uma construção ruim (a) e uma construção boa (b).

{% include image.html url="/img/exemplo-paragrafo.png" description="Exemplo de uma construção de parágrafos irregulares (a) e uma regulares (b)." number="1" width="450px" %}

Outro aspecto que afeta diretamente a leitura é a falta de padronização da escrita.
É possível utilizar mecanismo de estilização do texto para criar certos padrões para facilitar a leirura.
Como exemplo, é possível definir que toda palavra em itálico é uma palavra estrangeira,
quando o leitor observar esse estilo, automaticamente ele irá prever que essa palavra é estrangeira, antes mesmo de entender o seu significado, facilitando a sua leitura.
Quando não existe um padrão ou esse padrão é inconsistente, a leitura se torna mais tediosa pois o cerébro terá que racicionar mais para processar o texto.

Algumas abreviaturas são utilizadas na construção de um texto científico.
A abreviatura “e.g.” representa a expressão latina _exempli gratia_, que significa “por exemplo” ou “para fins de exemplo”. 
Já “i.e.” representa a expressão latina _id est_, que significa “isto é”, “ou seja” ou “em outras palavras”. 
Essas abreviaturas são utilizadas para deixar o texto mais direto. 
Caso contrário, dependendo da situação, o texto pode ficar um pouco repetitivo, pois é comum utilizar exemplos de um certo ponto (_e.g._) ou explicar um conceito de forma diferente (_i.e._) para deixar mais claro e exemplificado para o leitor.
Foram extraídos exemplos para cada uma das abreviações do trabalho de DO CARMO [[2]](#2):

_exempli gratia_ (_e.g._)
>
   O objetivo é utilizá-las em conjunto com um modelo, _e.g._ rede neural, e assim gerarmos um classificador robusto para a filtragem colaborativa.

_id est_ (_i.e._)
>
   Situações de aprendizado nos quais o ruído pode ocorrer são denominadas aprendizado supervisionado imperfeito (_imperfectly supervised_), _i.e._ reconhecimento de padrão em que a corretude do rótulo não é válida para todos os elementos do conjunto de treinamento.

## Referências {#referencias}

<a id="1">[1]</a> PÁDUA, E. M. M. de. Metodologia da pesquisa:abordagem teórico-prática. Campinas : Papirus, 1996. 94p. 

<a id="2">[2]</a> DO CARMO, Filipe Braida. Considerando o Ruído do Aprendizado de Modelos Preditivos Robustos para a Filtragem Colaborativa. 2018. Tese de Doutorado. Universidade Federal do Rio de Janeiro.