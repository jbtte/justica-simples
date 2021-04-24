# Justiça Simples
## Apresentação
O presente projeto é uma prova de conceito de uma funcionalidade que tem por objetivo simplificar a linguagem de processos, para que os cidadãos consigam acompanhá-los mesmo sem conhecimento jurídico.

**O banco de dados utilizado para desenvolvimento e teste não está conectado ao acervo de processo de nenhum Tribunal de Justiça.**

-> Para avaliar as funcionalidades deste aplicativo utilize as seguintes partes na busca da página inicial: Banco do Brasil, Tam Linhas Aéreas, Via Varejo, Lojas Renner, Sky ou Redecard.

**Live link: http://justicasimples.bt.enap.gov.br/**

## Recursos
Este aplicativo é mobile first e tem como funcionalidades:
* Pesquisar o processo por meio das partes ou pelo seu numero unificado
* Mostra os resultados da busca
* Mostrar as informações do processo como partes, vara em que está localizado e último andamento
* Mostrar, de forma resumida, os andamentos do processo destacando os principais andamentos e com linguagem mais acessível à pessoa leiga em direito
* Mostrar um organograma com as fases do processo e destacar em qual fase o processo encontra-se atualmente.
* Mostrar uma breve explicação de cada fase do processo

## Dependências
* Ruby ~2.6.6

## Instalar
Para rodar localmente:
* clonar o repositório - git@github.com:jbtte/justica-simples.git
* `cd justica-simples`
* `bundle` (Instalar as dependências)
* `rails db:create db:migrate` (Criar o banco de dados)
* `rails s` (rodar o servidor)
* Abrir navegador e visitar localhost:3000

## Version
1.0.0

## Status do Código
### Licença
This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

  This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

  You should have received a copy of the GNU General Public License
  along with this program.  If not, see <https://www.gnu.org/licenses/>

### Créditos
Rails app generated with [lewagon/rails-templates](https://github.com/lewagon/rails-templates), created by the [Le Wagon coding bootcamp](https://www.lewagon.com) team.
Developed by:
* @luexclusiva
* @guigoalmeida
* @treakj
* @jbtte 
