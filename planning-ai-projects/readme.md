## Planning AI Projects

https://towardsdatascience.com/planning-ai-projects-32060f1d98d6

A construção de um projeto baseado em IA é necessariamente diferente da construção de um app, por exemplo. Um desenvolvedor experiente sabe quanto tempo demora para montar um app com seus botões, formulários e bancos de dados, mas um cientsita de dados não pode dar estimativas tão corretas, apesar de já ter efetuado uma tarefa específica de ML várias vezes. Por quê isso acontece?

Em projetos baseados em ML, cientistas de dados lidão com milhões de números que interagem entre si e sua responsabilidade é entender e modelar essa interação para que consiga alcançar o resultado solicitado.

Em projetos de desenvolvimento tradicional de software, cada feature pode ser feita de forma iterativa e quebrada em pequenas tasks que, quando, atacadas de forma paralela levam a um resultado mais rápido.

As interações entre os milhões de números gerados por um modelo de ML não são previamente conhecidas e devem ser desbravadas pelo cientista de dados a cada nova iteração do projeto, o que torna o trabalho bem mais imprevisível.

O desenvolvimento tradcional depende de componentes já conhecidos e com comportamentos previsíveis. Contudo, projetos de ML dependem altamente da qualidade dos dados que serão utilizados, fator que contribui bastante para a inconsistências em previsões para projetos de ML.Entender os dados antes de dar uma estimativa de tempo é necessária, porém este trabalho é, em si, custoso em termos de tempo e equipe.

Tomando como exemplo o desenvolvimento de um app e de um sistema que reconheça diferentes raças de cachorros, podemos colocar essa situação num plano mais real.

O app vai ser composto por uma série de formulários, telas e bancos de dados.

O desenvolvedores precisarão entender quais são as features solicitas pelo cliente, quebrar elas em tarefas pequenas e que possam ser executadas de forma independente e, com o conhecimento já adquirido e ferramentas previsíveis, metrificar quanto tempo vair ser necessários para terminar o projeto.

O sistema de reconhecimento de raças vai ser composto por dados e um modelo.

Se um cientista de dados já tiver treinado um modelo para reconhecer gatos, eles não necessariamente vai reconhecer cachorros, logo ele precisa ser treinado para efetuar aquela tarefa específica. Para que o modelo seja corretamente treinado é necessário entender qual é a melhor arquitetura para o trabalho solicitado e, ainda mais importante, avaliar os dados que serão usados.

Imagine utilizar somente dados de uma raça. O modelo aprenderá somente aquela raça e nunca reconhecerá nenhuma outra. Ou seja, o trabalho de avaliação dos dados é crucial para o sucesso do projeto.

Então, como podemos ter sucesso em projetos de machine learning? Indo mais além, quais são boas práticas para planejar esse tipo de projeto?

O autor comenta que, para responder essas perguntas é importante que entendamos primeiro os dados que serão alvo de um projeto de ML. Criar pequenos ciclos de trabalho é uma boa prática.

### Minha conclusão

___


É da minha experiência que projetos de ML DEVEM ser precedidos de um fase de concepção do trabalho a ser feito e outra de exploração dos dados. Ou seja, antes de criar um projeto de ML é necessário entender qual é o problema real do cliente, o que podemos fazer e se o que ele está solicitando realmente é alvo de um projeto de ML (muitas vezes existem opções mais baratas ou já prontas).

A segunda fase pré-projeto de ML seria a exploração dos dados disponíveis para a execução do trabalho. Se existem dados insuficientes mais dados devem ser coletados. Se os dados tem má qualidade (distribuições impróprias para classes, prodminâncias de valores nulos, predominâncias de features não relacionadas ao trabalho) deve-se mudar a fonte ou colher mais dados de qualidade. 

_"Data analysis and data quality assessment provide your engineers with a good understanding of the problem and what machine learning algorithms are applicable. It may also save you from failed investments if the engineers determine the problem can’t be solved with the current state of the art, or due to data quality."_

O pré-projeto de ML deve responder 4 questões:

1. O que o cliente quer resolver?
2. É necessário utilizar machine learning para alcançar os resultados esperados pelo cliente?
3. O que o cliente está solcitando é tecnicamente viável?
4. Os dados disponbilizados pelo cliente são úteis em termos de quantidade e qualidade?
