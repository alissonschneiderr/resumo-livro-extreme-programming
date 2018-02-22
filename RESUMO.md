# eXtreme Programming
<h3>Práticas do dia a dia do desenvolvimento ágil de software</h3>

# Capítulo 1

<h3>Por que projetos falham?</h3>

<p>Os desenvolvedores acham que faltou análise, os analistas jogam a culpa no departamento comercial ue vendeu o que o software não tem e, ainda por cima, com um prazo impossível de ser cumprido; a equipe de vendas aponta para o cilente dizendo que ele não sabe o que quer; e ele, por sua vez, chama seus advogados para cancelar o contrato.</p>

<p>Os motivos para que isso aconteça são os mesmos: falta de proximidade com o cliente; trabalho empurrado goela abaixo do time; codificação a toque de caixa produzindo código sujo; tempo desperdiçado desenvolvendo o que o cliente não pediu (a famosa cereja do bolo); e o retrógrado hábito de testar o software apeans na véspera da sua data de entrega.</p>

<h4>Cliente Distante</h4>

<p>Cena corriqueira em times de desenvolvimento de software: o desenvolvedor recebe uma especificação para trabalhar, e, enquanto está codificando, percebe que algum detalhe passou despercebido pelo processo de análise do requisito. Isto gerou uma dúvida que o impede de prosseguir seu trabalho com segurança; ou seja, o desenvolvedor não tem certeza do que exatamente deve ser feito.</p>

<p>Nesses casos de incerteza, normalmente ele procura o analista ou a pessoa responsável por aquela especificação (ou pelo menos deveria fazer isso), e questiona sobre a dúvida que o impede de avançar no código com a certeza de que está fazendo o qeu foi pedido.</p>

<p>Qunado isso ocorre, é esperado que o analista saiba responder os questionamentos do desenvolvedor e o conduza de volta ao caminho correto a ser seguido. O problema é que as pessoas não sabem tudo, incluindo eu, você, e todos os que nós conhecemos. É normal que, em alguns casos, o analista não consiga responder a dúvida do desenvolvedor, pelo menos, não de imediato.</p>

<p>Quando as dúvidas surgem e ninguém do time sabe o que fazer, a melhor decisão é falar com o cliente, seja por meio de uma reunião, telefone, skype, e- mail ou qualquer outra forma de comunicação. O necessário é falar com ele!</p>

<p>Entrar no ciclo tentativa/ erro/ tentativa/ erro/ ... jamais deve ser uma opção. As pessoas até podem acertar de vez em quando, mas, na média, essa atitude vai gerar retrabalho lá na frente, além de frustrar o cliente e, posteriormente, o time.</p>

<p>Sabemos que nem sempre ele estará disponível. Mesmoq ue esteja fisicamente próximo de você e de seu time, ele pode simplesmente nãoe star livre ou interessado em ajudar; quer dizer, não quer se envolver. Até porque já pagou uma boa grana para uma empresa fazer seu software e espera que o time de desenvolvimento saiba como fazê-lo.</p>

<p>Pois bem, este cenário é oq ue chamamos de cliente distante. Acredite, projetos com clientes distantes têm uma grande tendência a serem entregues com atraso, estourarem o orçamento, os frustrarem ao entregar funcionalidades que não atendam suas expectivas, ou todas as alternativas anteriores juntas (fracasso tremendo).</p>

<b>E qual é a solução?</b>

<p>Precisamos aproximar o cliente desde o início do projeto, deixando bem claro que, a qualquer momento, ele poderá ser acionado para tirar dúvidas, e que a cada funcionalidade, ele poderá ser chamado para realizar uma validação. Ou seja, dar seu consentimento sobre se aquele recurso ficou de acordo com o que esperava, ou indicar o que precisa ser ajustado para atendê-lo, acso o resultado não satisfaça suas expectativas.</p>

<p>Porém, é necessário tomar cuidado. Pedir o aceite do cliente não significa pedir para ele testar. O teste do software é responsabilidade do time de desenvolvimento e, acredite em nós, eles não gostam de testar software. E, principalemnte, não ficam nada felizes quando encontram bugs nele.</p>

<p>E se o cliente odiar a funcionalidade desenvolvida, dizendo que está totalmente fora do que ele esperava? Ótimo! Nós conseguimos falhar rápido e teremos tempo para corrigir, adaptar ou até mesmo refazer o recurso, conseguindo finalmente entregar algo de valor a ele. Imagine como seria desagradável se, somente no final do projeto, nós descobríssemos que algumas (ou várias) funcionalidades não ficaram de acordo com sua expectativa? Seria terrível! E provavelmente nosso tempo já estaria esgotado.</p>

<h4>A cereja do bolo (Gold Plating)</h4>

<p>Se o seu cliente solicita um relatório com as colunas A, B e C; o time deve desenvolver, com qualidade e dentro do prazo, o relatório com as colunas A, B e C. Simples assim!</p>

<p>Entregar um relatório com as colunas A, B, C, X e Y não fazem sentido nenhum! Se ele quiser que as colunas X e Y aparecessem no relatório, teria solicitado. Neste caso, X e Y são a tal cereja do bolo da qual estamos falando.</p>

<p>Vamos lembrar de algo bem importante. Nosso cliente tem uma grande expectativa: receber aquilo que ele pediu! E ele possui outras também! Quer receber o mais rápido possível, com a mais alta qualidade e o menor custo. E com o menor desperdício possível, é claro. Colocar uma cereja no bolo não vai ajudá-lo a esquecer as falhas anteriores.</p>

<b>E qual é a solução?</b>

<p>Simplicidade: maximizar o trabalho que não deve ser feito. A meta do time deve ser trabalhar com o cliente apra enxugar as funcionalidades necessárias. Deve-se questionar muito sua visão de valor.</p>

<p>Indo nessa linha, vamos começar trabalhando naquilo que possui alto risco e valor, e descobrir rapidamente se temos algum problema. Lembra da estratégia de falhar rápido? Esse é o jogo. O mundo perfeito é trabalhar naquilo que possui alto valor e um baixo risco!</p>

<p>Não queremos trabalhar naquilo que possui baixo valor. O único motivo para isto está relacionado às leis, nas quais temos que seguir para a conformidade e evitar uma multa. De resto, fuja daquilo que não tem valor claro. Foque na entrega de valor para seu cliente.</p>

<h4>Testes no Final</h4>

<p>Deixe-nos explicar melhor: desenvolver software é um processo produtivo, no qual executamos tarefas de investigação design, programaçã, testes, entre outros. A forma como indústria começou a desenvolver seus modelos (e independente do modelo a ser adotado) engloba essas etapas.</p>

<p>A questão a ser observada no processo é que a preocupação com os testes só existe no final. Além de acontecer isoladamente não se enxerga seu verdadeiro valor, nem sua relação com a qualidade do produto.</p>

<p>Por esses motivos, os testes não são levados a sério. Por isso pagamos o preço do retrabalho ao entregar funcionaliades erradas e com falhas. Isso gera desconfiança e estressa uma relação que precisa ser totalmente diferente para atingirmos o objetivo.</p>

<b>E qual a solução?</b>

<p>Precisamos traablhar nos recursos até eles estarem prontos de verdade; ou seja, não podemos permitir que exista dentro do time de desenvolvimento o conceito de que está pronto, só falta testar.</p>

<h4>Trabalho empurrado</h4>

<p>Imagine a cena: o gerente de projetos avisa o time de desenvolvimento de que a empresa fechou um novo contrato e que o software deve ser entregue em uma determinada data, deixando já bem claro a todos que não existe a possibilidade de não a cumprir.</p>

<p>O time de desenvolvimento começa a analisar os requisitos e gerar as tarefas, e logo percebe que, para cumprir a data já firmada com o cliente, que inclusive consta no contrato, será necessário produzir em uma velociadde muito acima do habitual. Ao notar isso, o nível de estresse do time é elevado, o ambiente fica tenso e os desenvolvedores programam a toque de caixa, começando a gerar um código sujo, mal estruturado e em cima de requisitios especificados de forma superficial. Como o tempo era curto, ninguém quis perder muito tempo com especificação, assim todos já foram logo metendo a mão na massa.</p>

<p>Esse é um claro cenário de trabalho empurrado, que gera muito caos e pouco resultado!</p>

<b>E qual é a solução?</b>

<p>Se trabalho empurrado é um problema, trabalho puxado é a solução. O ideal é que esteja à disposição do time o que for necessário para o desenvolvimento de software e que as tareafs estejam corretametne priorizadas e, se possível, dispostas em um mural contendo todas as que serão trabalhadas nos próximos dias. Desse modo, uma ou mais pessoas puxam as tarefas e trabalham nelas até o fim, nunca esquecendo de desenvolver + testar, em vez de desenvolver primeiro, testar mais tarde.</p>

<h4>Dívidas Técnicas</h4>

<p>O termo dívida técnica é utilizado apra indiciar trechos de código que foram mal escritos, ou ecritos de qualquer forma, sem refatorar, sem testes automatizados e sem respeitar padrões. São as chamadas gambiarras ou bacas. Com o passar do tempo, esses trechos atrapalharão os desenvolvedores e mudanças que, teoricamente, seriam simples, passam a levar muito tempo para serem realizadas.</p>

<b>E qual a solução?</b>

<p>São excelentes formas de evitar a dívida técnica: especificar os requisitos com o formato de histórias de usuários, projeto simples, padrão de codificação, desenvolvimento guiado por testes (TDD), programação em pares, refatoração, integração contínua, boas práticas de programação e ritmo sustentável.</p>

<h4>Conclusão</h4>

<p>Quando um projeto falhar, não tente encontrar um culpado, olhe para o passado e procure identificar se algum dos problemas ocorreu em seu projeto. Precisamos sempre buscar sua causa raiz. Não busque culpados, busque entender o que ocorreu e converse com seu time para tentar encontrar uma solução, um melhor caminho a ser seguido.</p>

<p>Reuniões de retrospectiva de projeto são ótimas oportunidades de levantar problemas e discutir soluções com seu time. mias à frente, falremos sobre elas.</p>

# Capítulo 2

<h3>Introdução a Métodos Ágeis</h3>

A principal diferença das metodologias ágeis em relação às tradicionais é o enfoque na adaptação, visando ter o mínimo realmente necessário para a realização do trabalho. Com essa estratégia, busca-se aceitar e trabalhar a mudança, reduzindo os custos de implantação.

Os 4 valores do Manifesto Ágil são:

* Indivíduos e interações mais que processos e ferramentas;
* Software em funcionamento mais que documentação abrangente;
* Colaboração com o cliente mais que negociação de contratos;
* Responder a mudanças mais que seguir um plano.

E os 12 princípios do Manifesto Ágil são:

* Nossa maior prioridade é satisfazer o cliente por meio da entrega contínua e adiantada de software com valor agregado;
* Mudanças nos requisitos são bem-vindas no desenvolvimento, mesmo tardiamente. Processos ágeis tiram vantagem das mudanças, visando vantagem competitiva para o cliente;
* Entregar frequentemente software funcionando, de poucas semanas a poucos meses, com preferência à menor escala de tempo;
* Pessoas de negócio e desenvolvedores devem trabalhar diariamente em conjunto por todo o projeto;
* Construa projetos em torno de indivíduos motivados. Dê a eles o ambiente e o suporte necessários e confie neles para fazer o trabalho;
* O método mais eficiente e eficaz de transmitir informações para (e entre) uma equipe de desenvolvimento é por meio de conversa face a face;
* Software funcionando é a medida primário de progresso;
* Os processos ágeis promovem desenvolvimento sustentável. Os patrocinadores, desenvolvedores e usuários devem ser capazes de manter um ritmo constante indefinidamente;
* Contínua atenção à excel~encia técnica e bom design aumentam a agilidade;
* Simplicidade - a arte de maximizar a quantidade de trabalho não realizado - é essencial;
* As melhores arquiteturas, requisitos e designs emergem de equipes auto-organizáveis;
* Em intervalos regulares, a equipe reflete sobre como tornar-se mais eficaz e, então, refina e ajusta seu comportamentode acordo.

<h3>Lean Software Development</h3>

O Lean, ou Sistema Toyouta e Produção (STP), revolucionou a indústria da manufatura, tanto pela geração de valor para o cliente, quanto para a satisfação de trabalho para o time. Essas suas características serviram de base para o casl Mary e Tom Poppendieck identificar semelhanças com o desenvolvimento ágil de software, criando o Lean Software Development (LSD).

Com base nos seus pensmentos, foram identificados 7 princípios para o desenvolvimento de software:

* Eliminar desperdícios;
* Incluir qualidade no processo;
* Criar conhecimento;
* Adiar comprometimentos;
* Entregar rápido;
* Respeitar as pessoas;
* Otimizar o todo;

<h3>Scrum</h3>

O Scrum surgiu na década de 90, crado por Ken Schwaber, Jeff Shuterland e Mike Beedle. Seu principal objetivo é prover um framework de gestão ágil para desenvolver e manter produtos complexos.

Nele, a partir de um Backlog de Produto inicial, o trabalho que será realizado é priorizado na iteração, denominada Sprint. O desenvolvimento do Backlog da Sprint gera um incremento entregável do produto ao final de cada Sprint, na reunião de Revisão da Sprint. Esse trabalho é desenvolvido com a sincronização diária do Time de Desenvolvimento, na Reunião Diária. Ao final da Sprint, é realizada a reunião de Retrospectiva da Sprint, co o objetivo de reduzir riscos e promover a melhora contínua. O Dono do Produto é o papel responsável pelo gerenciamento do produto e o Scrum Master é pelo processo ajudando o Time de Desenvolvimento a resolver seus impedimentos.

<b>Scrum precisa das práticas técnicas do XP</b>

Scrum é um framework bastante popular atualmente e muito utiilzado para o gerenciamento de projetos, produtos e times. Por dar mais ênfase no gerenciamento de atividades e tarefas, ele pode (e deve) ser utilizado em conjunto com outros métodos e processos que focam em engenharia ágil de software, como o eXtreme Programming.

Jeff Sutherland, cocriador do Scrum, diz que o Manifesto Agil é sobre o Scrum com práticas de engenharia do eXtreme Programming, e essa combinação é o framework preferencial.

Veja também o que Ron Jeffries, Martin Fowler e James Shore falam da necessidade das práticas do XP na utilização do Scrum:

"Você não vê times Scrum de alto desempenho sem práticas de engenharia do XP. É difícil escalar times XP sem Scrum, e Scrum soluciona os assuntos de interface com a gestão. Seja cuidadoso ao fazer partes de qualquer cosia e chamar isso de ágil." Ron Jeffries e Jeff Sutherland (2007)

"Se você estiver procurando introduzir Scrum, certifique-se de prestar uma boa atenção às práticas técnicas. Nós tendemos a aplicar muitas dessas a partir do eXtreme Programming e elas se encaixam muito bem." - Martin Fowler (2009)

"XP e Scrum são as melhores maneiras que nós sabemos para trabalhar bem em conjunto. Eles não são necessários - pode haver outras maneiras - e eles certametne não são suficientes - há um milhão de coisas que devemos fazer para ser bem-sucedido, e elas não estão todas escritas nos livros." - Ron Jeffries (2009)

"Sem práticas de engenharia ágil do XP, a qualidade do código a produtividade diminui assintoticamente ao longo do tempo. Com elas, a produtividade começa inferior, mas em seguida aumenta assintoticamente." - James Shore (2008)

<h3>eXtreme Programming (XP)</h3>

<p>O eXtreme Programming é uma metodologia ágil de desenvolvimento de software voltada para times de pequeno a médio porte, no qual os requisitos são vagos e mudam frequentemente. Desenvolvido por Kent Beck, Ward Cunningham e Ron Jeffries, o XP tem como principal tarefa a codificação com ênfase menor nos processos formais de desenvolvimento e com uma maior disciplina de engenharia ágil de software para codificação e testes. Tem como valores a comunicação, a simplicidade, o feedback, a coragem e o respeito.</p>

<p>O XP valoriza a automatização de testes, sendo estes criados antes, durante e depois da codificação. É flexível para a mudanças de requisitos, valorizando o feedback com o usuário e qualidade do código-fonte final.</p>

<p>A ideia principal do XP é a criação de software de alta qualidade, abandonando todo tipo de overhead de processo que não suporte diretamente a entrega de valor. Ele é orientado explicitamente às pessoas e vai contra o senso comum do gerenciamento de que elas são peças intercambiáveis dentro do processo de desenvolvimento.</p>

# Capítulo 3

<h3>Valores	do	eXtreme Programming</h3>

<p>O	 eXtreme	 Programming	 define	 cinco	 valores	 para	 que	 seus
papéis	 e	 práticas	 funcionem	 em	 sinergia	 de	 acordo	 com	 sua
essência	 ágil:	 a	 comunicação,	 o	 feedback,	 a	 simplicidade,	 a
coragem	e	o	respeito</p>
