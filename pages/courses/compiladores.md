---
layout: page
title: Compiladores
subtitle: Informações e materiais do curso
---

## Informações
Pré-requisito:  Linguagens de Programação e Linguagens Formais e Autômatos

## Ementa
Estrutura de um compilador; Análise léxica; Análise sintática; Análise semântica; Recuperação de erros; Geração de código intermediário.

## Objetivos

Ao final da disciplina o aluno deve:
- Compreender a teoria e as técnicas usadas na construção de compiladores;
- Projetar e testar um compilador completo para uma linguagem algorítmica.

## Conteúdo Programático

### Sumário

1. [Visão Geral de um Compilador](#compilador)
2. [Análise Léxica](#lexico)
3. [Autômatos Finitos](#automato)
4. [Flex/Lex](#lex)
5. [Scanners](#scanners)
6. [Análise Sintática](#sintatico)
7. [Yacc/Bison](#yacc)
8. [Código Intermedíario](#codigo)
9. [Analisador Sintático Descendente](#descendente)
10. [Analisador Sintático Ascendente](#ascendente)
10. [Construção de um Compilador](#construcao)

### Tópicos de Aula

#### 01. Visão Geral de Um Compilador {#compilador}

##### Conteúdo

- Estrutura de um compilador
- Processadores de linguagens
- Evolução das LPs
- Fundamentos da LP

##### Materiais

- {% include youtube.html id='u8Fw4_Ty2Es' name='Visão Geral de um Compilador (video)' %}

#### 02. Análise Léxica {#lexico}

##### Conteúdo

- Arquitetura da análise léxica
- Especificações de tokens
- Erros léxicos
- Operações sobre linguagens
- Expressões Regulares
- Definições Regulares
- Extensões de ERs

##### Materiais

- {% include youtube.html id='Hx4vrxeLU90' name='Análise Léxica (video)' %}

#### 03. Autômatos Finitos {#automato}

##### Conteúdo

- Definição de Autômatos
- Representação Gráfica
- Representação Matricial
- AFD e AFND
- Aceitação de uma cadeia
- Simulando um AFD e um AFND
- Algoritmo de Thompson
- ER para Autômato
- Construção de Subconjunto
- Minimização de Estados

##### Materiais

- {% include youtube.html id='NCSumaS-g-w' name='Autômatos Finitos (video)' %}

#### 04. Flex/Lex {#lex}

##### Conteúdo

- Gerador de Scanner
- Usando o flex
- Especificações da entrada
- Definições, Regras e Padrões
- Regras de Matching

##### Materiais

- {% include youtube.html id='c9WLbVZ5T3w' name='Flex (e Lex) (video)' %}

#### 05. Scanners {#scanners}

##### Conteúdo

- Arquitetura de um Scanner
- Scanner feito à mão
- Scanner utilizando AFD e AFND
- Eficiência
- Projeto de um analisador de cadeia
- Pares de Buffers
- Casamento de Padrão

#### 06. Análise Sintática {#sintatico}

##### Conteúdo

- Arquitetura
- Hierarquia de Chomsky
- Gramática Livre de Contexto
- Derivações
- Formas de Derivações
- Árvore de Derivação
- Ambiguidade
- Análise Léxica vs Sintática

##### Materiais

- {% include youtube.html id='h5RsbIGCzFg' name='Análise Sintática (video)' %}

#### 07. YACC/Bison {#yacc}

##### Conteúdo

- Arquitetura
- Fluxo de Controle
- Especificações
- Declarações
- Regras de Produção

##### Materiais

- {% include youtube.html id='ATW-mq0ahaA' name='Bison (e YACC) (video)' %}

#### 08. Código Intermedíario {#codigo}

##### Conteúdo

- Processo de compilação
- Linguagem de três endereços
- Especificações
- Comandos

##### Materiais

- {% include youtube.html id='xLqb5RqXANQ' name='Geração de Código Intermediário (video)' %}

#### 09. Analisador Sintático Descendente {#descendente}

##### Conteúdo

- Ambiguidade
- Análise Top-Down
- Recursão à Esquerda
- Lookhead
- Parses Preditivos
- First e Follow
- Gramáticas LL(k) e LR(k)
- Analisador de Descida Recursiva
- Analisador Preditivo sem Recursão

#### 10. Analisador Sintático Ascendente {#ascendente}

##### Conteúdo

- Handle
- Parsers Shift-Reduce
- Parsers LR(1)
- Itens Canônicos
- Autômato LR(0)
- Tabela de Análise SLR

#### 11. Construção de um Compilador {#construcao}

##### Conteúdo

- Declaração
- Tipo de dados primitivos
- String
- Matrizes
- Expressões
- Operadores
- Comandos 
- Escopo
- Blocos
- Mecanismos de Controle de Laços
- Detecção de Erros
- Subprograma

##### Materiais

- {% include youtube.html id='FmR3p1-tzoc' name='Construindo o Primeiro Compilador (video)' %}
- {% include youtube.html id='mJM5KavdynM' name='Etapas do Trabalho de Compiladores (video)' %}

## Referência Bibliográfica

### Principal

- SETHI, Ravi; ULLMAN, Jeffrey D.; MONICA S. LAM. Compiladores: princípios, técnicas e ferramentas. Pearson Addison Wesley, 2008.

### Complementar

- RICARTE, Ivan. Introdução à compilação. Elsevier Brasil, 2012.
