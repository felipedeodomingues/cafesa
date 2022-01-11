# cafesa
Bom dia pessoal, 
Vou falar sobre a Jornada de Modelagem de Dados
•	O que é Modelagem de Dados
•	Como validar um modelo de dados
•	Como se relaciona com a LGPD
•	Governança de Dados
Para falar de Modelagem de dados, temos que ter em mente o que é Dado.
Dado para nós é uma fato isolado, está na sua forma primária, ou seja, é um conteúdo quantificável e que por si só não transmite nenhuma mensagem que possibilite conhecimento.
Exemplo: Saldo inicial da conta
Agora, se eu tenho por exemplo o dado: Saldo final de sua conta aí já consigo tirar uma informação: com o dado saldo inicial e o dado saldo final eu consigo eu consigo a informação de qual minha posição atual.
Vejam que consigo fazer um relacionamento entre esses dois dados.
Outro exemplo: número do RoP, Id
Diretoria
Eu tenho a informação que, segundo a regra de negócio, este número de RoP está relacionado a DED, por exemplo.

Então podemos dizer que a modelagem de dados são as ferramentas que permitem demonstrar como serão construídas os relacionamentos entre esses dados, segundo uma especificação de regra de negócio.

A Modelagem é dividida em 3 níveis:
Modelo Conceitual
Representação do mundo real através de uma visão simplificada dos dados e seus relacionamentos
Modelo Lógico
Especificação lógica do dados, defino a tipo dos valores (se é um texto ou um número), crio as tabelas, os campos (que chamamos de atributos)
Modelo Físico 
A partir do Modelo Lógico, o modelo físico é gerado com um nível absurdo de detalhamento e fica pronto para ser transformado em um banco de dados real.
Lembrando que banco de dados é coleção de dados relacionais.

Certo, mas o que isso se relaciona com a LGPD?
RoP
O Gabs irá entrar em um nível maior de detalhes, mas a nossa ferramenta ela está saindo do ambiente de automação sustentada e indo para uma sigla de tecnologia.
Okay, mas o que é automação sustentada?
É um modelo de execução que agiliza a criação de soluções departamentais;
Ou seja, eu tenho uma necessidade de criar ou melhorar um processo, por exemplo, “Registro de Processos de tratamento de dados no banco”; Então, existe uma Governança de Automação Sustentada que permite nós aqui criarmos essa ferramenta: desenvolver, implantar e dar sustentação. Enquanto que a Tecnologia oferece a infraestrutura, por exemplo, nosso banco de dados SQL. 

Okay, então basta Migrar para o novo ambiente e sucesso!? Não.

O banco possui toda uma Governança de Dados, que não vou entrar em detalhes, mas foi necessário pois, por exemplo, o Gabriel desenvolveu todo nosso banco de dados do RoP, ele é referência no banco, expert no assunto. De repente, Gabriel recebe uma proposta da concorrência e pica a mula, sai do banco.
E agora, como que valos fazer melhoria do banco de dados, acrescentar um novo campo que o Pedro e a Bella estão pedindo? Uma vez que não temos isso documentado?
Pensando nesse cenário então que temos a Governança de Dados.
Que exige a Modelagem naqueles 3 níveis:
Modelo Conceitual
Modelo Lógico
Modelo Físico 
Pois construir esses modelos são formas de documentar. E caso o analista responsável saia do banco, isso estará documentado. E também essa mesma modelagem poderá ser utilizada por outra área.
Como o modelo conceitual é onde levantamos as especificações com a área de negócio, que no nosso caso já está no RoP funcional, então, nem precisamos passar por essa etapa: já temos todos os requisitos necessários.

Então partimos partimos do Modelo Lógico.

Anl responsável – AD
AD Aprova
AD – DBA
DBA gera o script
