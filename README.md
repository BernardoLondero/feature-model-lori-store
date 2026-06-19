# LORI Store - Feature-Oriented Domain Analysis (FODA)

Este repositório contém o Modelo de Características (Feature Model) desenvolvido para o mapeamento de domínio da LORI Store, uma plataforma voltada para o comércio de infoprodutos e itens virtuais.

## Objetivo do Projeto
O objetivo foi aplicar a Análise de Domínio Orientada a Características (FODA) para modelar a variabilidade e os pontos de customização do sistema, estabelecendo a base para uma Linha de Produto de Software (SPL).

## Escopo da Modelagem
O diagrama mapeia as funcionalidades do sistema e suas dependências arquiteturais, incluindo:
* Features Obrigatórias: Carrinho, Emissão de notas, Catálogo e API.
* Features Opcionais e Variabilidades: Diferentes métodos de pagamento (Pix, cartões, etc.), autenticação (senha, face-ID) e canais de atendimento (humano ou IA).
* Restrições Lógicas (Cross-tree constraints): Definição de regras de negócio estritas, como a exclusão mútua entre descontos universitários e promoções gerais, ou a dependência entre rotas e entregas.

## Arquivos
* feature-model-lori-store.png: Visualização gráfica do diagrama de características gerado.

## Equipe
Este projeto foi desenvolvido colaborativamente por:
* [Bernardo Londero](https://github.com/BernardoLondero)
* [Arthur Fontoura](https://github.com/Arthur-Fontoura)
* [Gustavo Baptista](https://github.com/SakamotoGB)
* Alterson Marques
* Rodrigo Bragagnolo
* Alan Ziebert
* Artur Ruver
