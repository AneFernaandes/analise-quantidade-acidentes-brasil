# Projeto de Análise de Acidentes em Rodovias Federais no Brasil 
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40" height="40" /> <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original-wordmark.svg" width="40" height="40"/>
          
Este projeto, desenvolvido em equipe por Bruna Dias, Camylla Oliveira, Eliane Patrício, Nayla Andrade e Rodrigo Freitas, utiliza a poderosa biblioteca Pandas em Python para realizar análise de dados e estatística computacional sobre acidentes em rodovias federais no Brasil. O conjunto de dados abrange o período de 2007 a 2022, fornecendo informações detalhadas sobre diversos aspectos dos acidentes.

# Sobre o Projeto
### Objetivo
O objetivo principal desta análise é entender a dinâmica dos acidentes de trânsito em rodovias federais brasileiras, explorando padrões, tendências e fatores influenciadores. Com base nessas análises, esperamos contribuir para discussões relevantes sobre segurança viária e apoiar iniciativas que visam a redução de acidentes.

## O conjunto de dados contém as seguintes informações:

* data_inversa: Data em que o acidente ocorreu.
* dia_semana: Dia da semana em que o acidente ocorreu.
* horario: Horário do dia em que o acidente ocorreu.
* uf: Estado em que o acidente aconteceu.
* br: Número da rodovia.
* km: Quilômetro da rodovia onde ocorreu o acidente.
* municipio: Município onde o acidente ocorreu.
* causa_acidente: Causas relacionadas ao desrespeito das leis de trânsito.
* tipo_acidente: Classificação por tipo de colisão.
* classificacao_acidente: Indicação se houve vítimas e tipo de vítima.
* fase_dia: Período do dia em que o acidente aconteceu (manhã, tarde, noite).
* sentido_via: Sentido da via no momento do acidente (crescente, decrescente).
* condicao_metereologica: Situação do clima no momento do acidente.
* tipo_pista: Informação se a pista é simples, dupla ou múltipla.
* tracado_via: Descrição se o acidente ocorreu em curva, reta, ponte, túnel, etc.
* uso_solo: Tipo de solo onde ocorreu o acidente (rural ou urbano).
* ano: Ano em que o acidente ocorreu.
* pessoas: Quantidade de pessoas envolvidas no acidente.
* mortos: Quantidade de óbitos decorrentes do acidente.
* feridos_leves: Quantidade de feridos leves.
* feridos_graves: Quantidade de feridos graves.
* ilesos: Quantidade de pessoas ilesas.
* ignorados: Quantidade de envolvidos cujo estado não foi registrado.
* feridos: Total de feridos (leves + graves).
* veiculos: Quantidade de veículos envolvidos no acidente.
* latitude: Coordenada de latitude onde o acidente ocorreu.
* longitude: Coordenada de longitude onde o acidente ocorreu.
* regional: Informação sobre a regional associada ao acidente.
* delegacia: Delegacia responsável pelo registro do acidente. <br>

## Perguntas de interesse
Durante a análise, buscamos responder a uma série de perguntas fundamentais para compreender a dinâmica dos acidentes:

1. Em qual Estado ocorre o maior número de acidentes?
2. Como é a distribuição de mortos em acidentes por Estado?
3. Quais são as principais causas de acidentes em rodovias federais?
4. Como a condição meteorológica influencia os tipos de acidentes?
5. Existe uma relação entre o dia da semana e a gravidade dos acidentes?
6. Qual a evolução temporal dos acidentes ao longo dos anos?

### Fonte de Dados
Os dados utilizados neste projeto foram obtidos no Kaggle, através do conjunto disponibilizado por Rafael Borges Graunke. Você pode acessar a fonte dos dados aqui.

### Uso da Biblioteca Pandas
O projeto utiliza extensivamente a biblioteca Pandas para realizar a limpeza, manipulação e análise exploratória dos dados. O código em Python está organizado de forma a permitir uma fácil compreensão e replicação do processo.

### Programa de Bolsas em Análise de Dados - IFOOD
