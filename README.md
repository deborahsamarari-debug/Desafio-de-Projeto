# Desafio-de-projeto
Desafio elaborado para o bootcamp de excel e IA
# Simulador de Investimentos em Fundos Imobiliários

## Sobre o Projeto

Este projeto consiste no desenvolvimento de uma ferramenta de simulação de investimentos em Fundos de Investimento Imobiliário (FIIs), construída no Microsoft Excel.

A ferramenta foi desenvolvida com o objetivo de auxiliar o usuário no planejamento de seus investimentos, permitindo visualizar a evolução do patrimônio ao longo do tempo e estimar os rendimentos mensais a partir dos valores investidos.

O simulador utiliza fórmulas financeiras, tabelas de referência e intervalos nomeados para automatizar os cálculos e facilitar a utilização da planilha.

## Funcionalidades

A ferramenta permite responder às seguintes perguntas:

- Quanto investir mensalmente?
- Por quantos anos investir?
- Qual será a taxa de rendimento mensal da carteira?
- Quanto patrimônio será acumulado ao final do período?
- Quanto será recebido mensalmente em dividendos estimados?

Além disso, o simulador apresenta projeções de patrimônio para diferentes horizontes de investimento, permitindo comparar os resultados de acordo com o prazo escolhido.

A ferramenta também realiza a distribuição do aporte mensal entre seis categorias de fundos imobiliários, de acordo com o perfil de investidor selecionado.

## Como a Ferramenta Funciona

### Cálculo do Patrimônio — VF

A função VF (Valor Futuro) é utilizada para calcular o patrimônio acumulado ao longo do período de investimento.

O cálculo considera o aporte periódico, a taxa de rendimento mensal e o número de períodos de investimento.

Para a simulação, o prazo em anos é convertido em meses, permitindo que a função considere a periodicidade mensal dos aportes e dos rendimentos.

A partir do patrimônio acumulado, a ferramenta estima os dividendos mensais utilizando a taxa de rendimento informada.

### Projeções de Patrimônio

O simulador apresenta projeções para diferentes períodos de investimento, incluindo:

- 2 anos;
- 5 anos;
- 10 anos;
- 20 anos;
- 30 anos.

Essas projeções permitem observar como o tempo e a regularidade dos aportes influenciam o crescimento do patrimônio.

### Distribuição por Perfil de Investidor — PROCV

A ferramenta utiliza a função PROCV para buscar os percentuais de distribuição dos investimentos de acordo com o perfil selecionado.

Para isso, foi utilizada uma tabela auxiliar que relaciona os perfis de investidor às categorias de fundos imobiliários.

A busca utiliza uma chave composta, formada pela combinação do perfil de investidor e do tipo de fundo. Essa estrutura permite identificar o percentual correspondente a cada categoria dentro de determinado perfil.

Dessa forma, ao selecionar um perfil, a ferramenta atualiza automaticamente a distribuição do aporte mensal.

## Intervalos Nomeados

Foram utilizados intervalos nomeados para facilitar a identificação dos parâmetros e tornar as fórmulas mais organizadas.

Os intervalos utilizados são:

- `aporte`: [descrever o intervalo correspondente ao aporte mensal];
- `taxa_mensal`: [descrever o intervalo correspondente à taxa mensal];
- [Adicionar outros intervalos nomeados utilizados na planilha].

A utilização de intervalos nomeados contribui para a legibilidade das fórmulas e facilita a manutenção da ferramenta.

## Distribuição dos Perfis

A ferramenta apresenta diferentes perfis de investidor, cada um com uma distribuição específica entre as categorias de fundos imobiliários.

Os percentuais utilizados foram definidos com base em [indicar a fonte dos percentuais: exemplos apresentados pelo Expert, adaptações próprias ou outra referência].

A distribuição de cada perfil totaliza 100% do aporte mensal.

Os percentuais possuem finalidade exclusivamente ilustrativa e educacional, não constituindo recomendação de investimento.

## Alterações em Relação à Ferramenta do Expert

Em relação à ferramenta apresentada pelo Expert Felipe Aguiar, foram realizadas as seguintes modificações:

- [Descrever alterações no layout e na organização da planilha];
- [Descrever alterações nos cálculos ou fórmulas];
- [Descrever alterações nos perfis ou percentuais];
- [Descrever funcionalidades adicionais implementadas].

As modificações tiveram como objetivo adaptar a ferramenta às escolhas realizadas durante o desenvolvimento, mantendo a proposta de simulação e planejamento financeiro.

## Tecnologias Utilizadas

- Microsoft Excel;
- Fórmulas financeiras;
- Função VF;
- Função PROCV;
- Validação de dados;
- Intervalos nomeados.

## Observação

Este simulador possui finalidade educacional e de planejamento. Os resultados são estimativas matemáticas baseadas nos parâmetros informados pelo usuário e não representam garantia de rentabilidade futura.

A ferramenta não constitui recomendação de compra ou venda de ativos financeiros.

Arquivo da Planilha

Acesse a planilha completa do simulador pelo link abaixo:
https://1drv.ms/x/c/729bf627733b555e/IQD-uaf4vPMBQK3amvW2o0tqAds3JI5_VYidvyJYPj6ElTU?e=ZfwDLh
