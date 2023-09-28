# Caso para Analista de Dados CRM - iFood

Tradução do case original em inglês para português. O texto original está [neste arquivo PDF](./iFood%20Data%20Analyst%20Case.pdf) baixado do [repositório do GitHub da iFood](https://github.com/ifood/ifood-data-business-analyst-test) para este case.

## Texto de apresentação

O iFood é o aplicativo líder de entrega de alimentos no Brasil, presente em mais de mil cidades. 

Manter um alto engajamento do cliente é fundamental para o crescimento e consolidação da empresa na posição como líder de mercado.

Os analistas de dados que trabalham na equipe de dados são constantemente desafiados a fornecer insights e valor para a empresa por meio de projetos de escopo aberto. Este caso pretende simular isso. 

Neste case, você recebe um conjunto de dados de amostra, que simula metainformações sobre o cliente e as interações da campanha iFood com esse cliente.

É seu desafio entender os dados, encontrar oportunidades e insights de negócios e propor qualquer ação orientada por dados para otimizar os resultados das campanhas e gerar valor para a empresa.

Este case visa avaliar suas habilidades e conhecimentos em dados para duas funções possíveis: 

- Analista de dados de negócios:

> Realizar uma análise exploratória robusta, rica em insights de negócios e propostas orientadas por dados para agregar valor à empresa. Ter fortes habilidades de comunicação para influenciar o tomada de decisão.
 
- Analista de dados avançado:

> Realizar uma análise exploratória robusta, usando ferramentas de análise avançada e métodos estatísticos, para gerar produtos de dados para otimizar os resultados dos negócios (modelos preditivos e de agrupamento, por exemplo).

Tenha foco claro em qual função você deseja executar na iFood e concentre sua energia para se destacar em tópicos mais relevantes para isso. 

Abaixo você encontrará a descrição do caso e mais detalhes do que esperamos como sua solução.

**Por favor, leia atentamente até a última página.**

## A empresa do case

Considere uma empresa bem estabelecida que atua no setor de varejo de alimentos. Atualmente, eles têm milhares de clientes registrados e atendem quase um milhão de consumidores por ano. Eles vendem produtos de 5 grandes categorias: vinhos, carnes, frutas exóticas, peixes especialmente preparados e produtos doces. Estes podem ser divididos ainda mais em produtos *gold* e regulares. Os clientes podem encomendar e adquirir produtos por meio de 3 canais de vendas: lojas físicas, catálogos e site da empresa. Globalmente, a empresa teve receitas sólidas e uma linha de fundo saudável nos últimos 3 anos, mas as perspectivas de crescimento dos lucros para os próximos 3 anos não são promissoras... Por esse motivo, várias iniciativas estratégicas estão sendo consideradas para inverter essa situação. Um deles é melhorar o desempenho das atividades de marketing, com foco especial em campanhas de marketing.

## O departamento de marketing

O departamento de marketing foi pressionado a gastar seu orçamento anual com mais sabedoria. O CMO percebe a importância de ter uma abordagem mais quantitativa ao tomar decisões, razão pela qual uma pequena equipe de cientistas de dados foi contratada com um objetivo claro em mente: construir um modelo preditivo que apoiará iniciativas de marketing direto. Desejavelmente, o sucesso dessas atividades provará o valor da abordagem e convencer os mais céticos dentro da empresa.

## O objetivo

O objetivo da equipe é construir um modelo preditivo que produza o maior lucro para o próxima campanha de marketing direto, programada para o próximo mês. 

A nova campanha, sexta, visa vender um novo gadget para o Banco de Dados de Clientes. Para construir o modelo, uma campanha piloto envolvendo 2.240 clientes foi realizada. Os clientes foram selecionados aleatoriamente e contatados por telefone com relação à aquisição do gadget. Durante os meses seguintes, os clientes que compraram a oferta foram devidamente rotulados. 

O custo total da campanha de amostra foi de 6.720MU e a receita gerado pelos clientes que aceitaram a oferta foi de 3.674MU. Globalmente a campanha teve um lucro de -3.046MU. A taxa de sucesso da campanha foi de 15%. O objetivo da equipe é desenvolver um modelo que preveja o comportamento do cliente e aplicá-lo ao restante da base de clientes. Esperançosamente, o modelo permitirá que a empresa escolha os clientes que são mais propensos a comprar a oferta, deixando de fora os não respondentes, tornando a próxima campanha altamente lucrativa. 

Além disso, além de maximizar o lucro da campanha, o CMO está interessado em entender as características dos clientes que estão dispostos a comprar o gadget.

## Os dados

O conjunto de dados contém recursos sociodemográficos e firmográficos sobre 2.240 clientes que foram contatados. Além disso, contém um rótulo para aqueles clientes que responderam à campanha, comprando o produto.

Dicionário de dados disponível [na pasta `data`](../data/README.md).

## Entregáveis

Os seguintes são os entregáveis mínimos necessários:

1. Explore os dados - seja criativo e preste atenção aos detalhes. Você precisa fornecer para a equipe de marketing uma melhor compreensão das características dos respondentes;
2. Crie e descreva uma segmentação de clientes com base no comportamento dos clientes;
3. Crie e descreva um modelo preditivo (classificação) que permita à empresa maximizar o lucro da próxima campanha de marketing.

Como esperamos que sua solução seja enviada:

1. Um notebook detalhado e bem organizado (ou arquivo de código equivalente) a ser apresentado a partes técnicas interessadas.
2. Uma apresentação do PowerPoint (ou ferramenta similar) a ser apresentada às partes interessadas (stakeholders) do negócio.

Você pode usar qualquer linguagem de programação para esta tarefa (usamos Python).

Simplicidade e consciência do que está acontecendo é preferível a implementações de algoritmos complexos que você não domina.

Se sua solução atender aos nossos critérios mínimos, você deve ser convidado para uma apresentação técnica / negócios. Soluções que não atendem aos nossos critérios, mas que mostram potencial, serão convidadas para uma reunião de feedback curta (30 min).

Você deve receber uma resposta dentro de 1-2 semanas após o envio do caso.

Se houver alguma dúvida, não hesite em nos contatar.
