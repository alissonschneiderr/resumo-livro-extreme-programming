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

<p>O eXtreme Programming define cinco valores para que seus papéis e práticas funcionem em sinergia de acordo com sua
essência ágil: a comunicação, o feedback, a simplicidade, a coragem e o respeito.</p>

<h3>Comunicação</h3>

<p>A forma mais eficiente é a conversa face a face, usando um quadro branco como apoio para rabiscar ideias e/ou rascunhos sobre arquitetura de software. Distribuir quadros brancos no ambiente de desenvolvimento pode funcionar muito bem para
estimular discussões de arquitetura, fluxos, algoritmos e, assim, aumentar a possibilidade deimplementar certo logona primeira
tentativa.</p>

<p>A comunicação incentiva diretamente outro valor essencial no XP:ofeedback.</p>

<h3>Feedback</h3>

<p>Na adoção das práticas, o feedback é realizado a todo momento, seja em relação aos requisitos do cliente, ao resultado da execução de testes unitários, ou na compilação do código na integração contínua. A compreensão das necessidades dos usuários e do negócio propriamente dito é um aprendizado constante. A razão de adotarmos estratégias iterativas e incrementais é que isso permite que os inevitáveis erros das pessoas sejam descobertos o mais cedo possível e reparados de forma metódica.</p>

<h3>Simplicidade</h3>

<p>Infelizmente, projetar um design simples não é algo fácil, pois muitos times já estão acostumados com a prática de futurologia, sofrendo da Síndrome de Nostradamus; ou seja, mesmo sabendo o que o cliente quer hoje, eles insistem em tentar desenvolver uma solução que também resolva problemas futuros. O ponto é: não temos certeza sobre o que vai acontecer no  futuro, então precisamos nos focar apenas nos problemas e necessidades atuais do nosso cliente.</p>

<p>Lembre-se: busque sempre desenvolver o suficiente de forma simples e com qualidade.</p>

<h3>Coragem</h3>

<p>O cliente teme:</p>

* Não obter o que foi solicitado/contratado;
* Pedir a coisa errada;
* Pagar demais e receber pouco;
* Jamais ver um plano relevante;
* Não saber o que está acontecendo (falta de feedback);
* Ater-se às primeiras decisões de projeto e não ser capaz de reagir à mudança do negócio.

<p>Já o desenvolvedor teme:</p>

* Ser solicitado a fazer mais do que sabe fazer;
* Ser ordenado a fazer coisas que não façam sentido;
* Ficar defasado tecnicamente;
* Receber responsabilidades, mas sem autoridade;
* Não receber definições claras sobre o que precisa ser feito;
* Sacrificar a qualidade em função do prazo;
* Resolver problemas complexos sem ajuda;
* Não ter tempo suficiente para fazer um bom trabalho.

<p>Um verdadeiro time XP é composto de indivíduos corajosos que confiam em suas práticas, bem como nos seus colegas de time. A coragem faz-se ainda mais necessária nos momentos de crise.</p>

<h3>Respeito</h3>

<p>O respeito pelos colegas de time e pelo cliente é muito importante. Pessoas que são respeitadas sentem-se valorizadas. Os
membros do time precisam respeitar o cliente; o cliente precisa respeitar os membros do time; e, além disso, o cliente deve fazer parte das decisões.</p>

<p>Todos no time devem respeitar a posse coletiva do código, sempre primando pela qualidade e buscando um design simples por meio da refatoração.</p>

<p>O ponto é: como se adquirem confiança e respeito? Obviamente, entregando softwares que funcionam. E mais que isso, o respeito é fundamental para uma relação transparente e duradoura. É isso que realmente forma a parceria e a colaboração de todos  envolvidos, algo essencial para a entrega contínua de valor.</p>

# Capítulo 4

<h3>Papéis do eXtreme Programming</h3>

<p>O time XP é formado por papéis com objetivos diferentes, porém complementares, tais como: o papel de desenvolvedor (programador), do cliente, do gerente, do coach, do testador, do tracker e do cleaner (BECK, 1999).</p>

<h3>Desenvolvedor</h3>

<p>O desenvolvedor, também denominado programador, é o coração do XP. O desenvolvedor multidisciplinado é um
profissional capaz de trabalhar em todas as etapas do desenvolvimento de software, desde a escrita de histórias de
usuário até o deploy em produção. No time XP, ele é um programador que estima as histórias de usuários e tarefas, quebra
as histórias em tarefas, escreve testes, escreve código, automatiza processos de desenvolvimento e, gradualmente, aprimora o design do sistema.</p>

<p>Especificação, prototipação, design, desenvolvimento, testes e atividades ligadas ao DevOps são tarefas que o desenvolvedor
poderá exercer em seu dia a dia. Desenvolvedores multidisciplinados elevam o nível de agilidade de um time, uma vez que todos podem vir a atuar em atividades que, eventualmente, tornam-se gargalos do projeto. Visto que eles escrevem código de produção em pares, precisam ter boas habilidades sociais e de relacionamento.</p>

<h3>Cliente</h3>

<p>Também conhecido como o dono do ouro, o cliente define e prioriza as histórias de usuário, validando o produto desenvolvido
por meio de testes de aceitação. É importante que ele esteja o mais próximo possível do time, com disponibilidade suficiente para conversar e tirar as dúvidas habituais.</p>

<p>O nosso cliente nem sempre será o usuário, podem ser as pessoas que realmente utilizarão o software no dia a dia.</p>

<h3>Coach</h3>

<p>É o técnico do time XP. Ele orienta a todos, mantendo a disciplina na aplicação das práticas ágeis, e lembra a equipe da
importância das cerimônias (como a reunião em pé, o jogo do planejamento e a reunião de retrospectiva, tudo que veremos mais
à frente), da construção e manutenção de artefatos e do uso de ferramentas.</p>

<h3>Testador</h3>

<p>O testador no time XP auxilia o cliente a escolher e escrever testes de aceitação, para, então, automatizá-los. Ele serve também como um programador coach em técnicas de testes. Para o time de desenvolvimento, o testador não é responsável por pegar erros triviais, isto é papel dos próprios desenvolvedores. Ele faz parte do time XP, não devendo ser uma pessoa isolada e trabalhando em outro local. Ele pensa no teste e na qualidade do produto como um todo, considerando também os que rodarão na integração contínua, auxiliando em par os programadores a resolver problemas do sistema.</p>

<h3>Cleaner</h3>

<p>O cleaner é um membro do time que assume o papel de limpar o código; encorajar os membros a praticar pequenas refatorações;
reduzir a complexidade e acoplamento do código; e a aumentar a coesão dos métodos, realizando sua extração e tornando o código cada vez mais enxuto (WUESTEFELD, 2010). Ele também se mantém o tempo todo atento aos impedimentos do time e às
dívidas técnicas, ajudando, assim, a garantir a qualidade do código. </p>

<p>São pré-requisitos para um bom cleaner: a excelência técnica, o conhecimento do negócio e da arquitetura, bem como uma boa
didática para explicar aos desenvolvedores o motivo de cada refatoração para elevar o nível técnico de todos os membros do
time.</p>

<p>O cleaner incentiva o grupo a cuidar da saúde e do bem-estar do código. Um bom candidato pode ser o líder técnico ou o
arquiteto do produto. Ele também pode conduzir Coding Dojos ou outras dinâmicas para elevar o conhecimento técnico da equipe.</p>

<h3>Tracker</h3>

<p>Responsável por coletar as métricas de projeto, o tracker é capaz de contar uma história da iteração do início ao fim, por meio dos apontamentos que realizou e das informações que foram coletadas.<p>

<p>Ao final de cada iteração, ele pode gerar métricas que mostram o desempenho do time. O coach pode trabalhá-las com o grupo,
buscando manter aquilo que estiver satisfatório e modificar o que não estiver indo bem.</p>

<h3>Gerente</h3>

<p>O gerente facilita a comunicação dentro de um time XP e coordena a comunicação com clientes, fornecedores e com o resto da organização. Ele gerencia e acompanha o planejamento do projeto, pois o planejamento no XP é uma atividade, e não uma fase; e auxilia na priorização das histórias de usuário, assim como no agendamento de reuniões e de demonstrações com o cliente e os usuários. Também gera relatórios e gráficos de acompanhamento do projeto e administra a infraestrutura necessária ao time (máquinas, licenças, espaços físicos etc.).</p>

<p>O gerente não é o chefe do time de desenvolvimento, mas pode (e deve) ser um líder servo, o que significa que ele reconhece e
auxilia nas suas necessidades reais.</p>

<h3>Outros Papéis</h3>

<p>O XP considera que outros papéis relacionados ao negócio podem fazer parte do time, podendo incluir: usuários, consultores, chefes e executivos (BECK, 2004). Porém, por tratarem-se de papéis complementares do XP, eles não serão abordados por nós.</p>

# Capítulo 5

<h3>Time Coeso</h3>

<h4>"A aprendizagem	não	é	obrigatória...	Nem	a	sobrevivência."	─ William	Edwards	Deming</h4>

<p>Comumente	nas	organizações,	diversos	processos	e ferramentas	são	desenvolvidos	para	tentar	resolver	problemas	que, na	realidade,	são	causados	por	lacunas	na	comunicação,	na confiança	das	pessoas	e	na	falta	de	motivação	dos	indivíduos, criando	formalismos	que	engessam	o	trabalho	e	geram	novos problemas.	Esse	primeiro	valor	enfatiza	a	importância	das	pessoas e	do	trabalho	em	time	para	um	melhor	desenvolvimento	de software.</p>

<h3>Time Multidisciplinar</h3>

<p>O	trabalho	multidisciplinar	tem	raízes	nas	células	de	produção do	Sistema	Toyota	de	Produção	(LIKER,	2005).	O	conceito	de células	de	produção	defende	o	trabalho	em	equipe	para	a	produção de	itens	com	características	similares,	sendo	uma	grande	inovação dos	japoneses	na	década	de	70.	Isso	revolucionou	a	ideia	tayloristafordista	de	ter-se	apenas	um	homem	por	estação	de trabalho executando	apenas	um	tipo	de	tarefa	especializada.</p>
  
<p>O	trabalho	em	célula	de	produção	cria	sinergia	entre	os indivíduos	e	otimiza	o	desempenho	do	processo,	eliminando diversos	desperdícios,	tais	como:	espera;	superprodução;	estoque; defeitos	de	qualidade;	movimentos;	transportes;	processos desnecessários;	e,	principalmente,	o	não	uso	da	criatividade	dos funcionários.	É	importante	salientar	que	o	membro	de	time	XP pode	assumir	mais	de	um	papel,	o	que	foi	abordado	com	mais detalhes	no	capítulo	anterior.</p>

<h3>Time Auto-organizável</h3>

<p>	Não	há	a	necessidade	de controle	das	atividades	de	cada	indivíduo	do	time	por	um	gerente de	projetos	ou	um	coordenador. 	O	gerente	empodera	o	time nas	suas	decisões	e	trabalha	no	macrogerenciamento.	O microgerenciamento	está	dentro	do	próprio	time;	não	há	ninguém melhor	do	que	a	própria	equipe	para	tomar	suas	decisões	de trabalho.</p>

<h3>Sentando lado a lado</h3>

<p>É	essencial	que	o	time	sente-se	junto	no mesmo	ambiente	físico.	No	início	do	dia,	os	membros	realizam	as reuniões	diárias	face	a	face	e,	durante	ele,	a	programação	em	pares é	feita	constantemente.</p>

<h3>As reuniões de retrospectiva e a melhoria contínua</h3>

<p>Em	desenvolvimento	de	software,	existe	apenas	o	aperfeiçoar,	e não	a	perfeição.	Não	há	processo	perfeito,	nem	projeto	e	nem histórias	de	usuário.	Contudo,	a	melhoria	contínua	é	buscada	no dia	a	dia,	sendo	possível	aperfeiçoar	seu	processo,	seu	projeto	e suas	histórias. </p>

<p>Qual	é	a	abordagem	do	XP	para	a	melhoria	contínua?	É simples:	conserte	o	XP	quando	ele	falhar.	O	eXtreme Programming	assume	que	não	trará	todas	as	respostas	para	o desenvolvimento	de	software,	pois	sabemos	que	não	há	bala	de prata	(BROOKS,	1987).	As	regras	devem	ser	seguidas	até	o	time precisar	mudá-las. </p>

# Capítulo 6

<h3>Cliente Presente</h3>

<h4>"Clientes	não	esperam	que	você	seja	perfeito.	Eles	esperam	que você	resolva	coisas	que	eles	fizeram	errado."	─	Donald	Porter,	vicepresidente	da	British	Airways</h4>

<p>Uma	das	necessidades	básicas	do	XP	é	ter	o	cliente	presente, pois	isso	faz	com	que	ele	se	sinta	parte	do	time,	o	que	agiliza	o trabalho	dos	programadores. Todas	as	fases	do	XP	precisam	da	comunicação	com	o	cliente, de	preferência	face	a	face.	Por	isso,	é	interessante	que	ele	esteja	no próprio	local	do	desenvolvimento	do	software.	</p>

<p>O	cliente	tem	uma	participação	essencial	no	jogo	do planejamento,	escrevendo	e	priorizando	histórias	e	discutindo detalhes	dos	requisitos	diretamente	com	o	time	para	criarem	as tarefas	de	implementação. 	Ele	também	precisa	estar	disponível para	discutir	os testes	de	aceitação	para	que	o	time	valide	as histórias.</p>

<p>Uma	objeção	comum	sobre	ter-se	o	cliente	presente	é	que	ele requisitará	apenas	o	que	é	de	seu	interesse	e	não	pensará	no negócio como	um	todo.	Isso	é	de	responsabilidade	do	trabalho	dele e	de	outras	pessoas	ligadas	ao	negócio,	e	poderá	acontecer	de qualquer	forma,	com	ou	sem	sua	presença.</p>
  
<p>Ter	somente	um	representante	do	negócio	(ou	até	não	possuir cliente)	pode	ser	um	problema,	pois	faz	com	que	funcionalidades sem	utilidade	sejam	desenvolvidas	e	que	critérios	de	aceitação	não realistas	sejam	criados.	O	time	de	desenvolvimento	trabalhará	por itens	sem	valor	real	que	não	fazem	parte	da	solução	real.</p>

<h3>O que fazer quando o cliente não pode estar presente?</h3>

<p>Utilize	ao	máximo	a	comunicação	por	telefone	e	reuniões virtuais.	O	trabalho	por	reuniões	remotas	é	uma	boa	alternativa. Ajudará	também	ter	um	representante	que	entenda	do	negócio	e tenha	tempo	e	acesso	ao	cliente.	Tente	ao	menos	que	ele compareça	nas	reuniões	de	planejamento.	E	mais,	se	for	possível, aproveite	ao	máximo	seu	tempo	e	faça	um	planejamento	presencial intensivo de	um	dia	inteiro	ou	de	uma	semana	inteira.</p>

# Capítulo 7

<h3>Histórias de Usuário</h3>

<h4>"Histórias	não	são	requisitos;	elas	são	discussões	sobre	resolver problemas	para	nossa	organização,	nossos	clientes	e	nossos usuários que	levam	a	acordos	sobre	o	que	construir."	─	Jeff	Patton </h4>

<p>Cada	história	segue	um	ciclo	de	vida, normalmente	nascendo	como	um	épico	(histórias	grandes),	sendo detalhada	de	acordo	com	sua	prioridade.	Elas	são	textuais,	não necessitam	de	ferramenta	específica,	são	compreensíveis	por	todos do	desenvolvimento	ou	do negócio,	e	são	descritas	em	cartões, também	chamadas	de	cartões	de	história	(story card).</p>

<p>Exemplos	de	histórias	de	usuário:</p>

* Como	um	contador,	eu	quero	registrar	uma movimentação	de	patrimônio; Como	uma	leitora,	quero	pesquisar	livros	por categoria;
* Como	repositor	de	estoque,	quero	localizar	quais	as prateleiras	do	supermercado	que	contêm	menos	de 50%	de	sua	capacidade	de produtos. 
* Como	cliente,	quero	encontrar	as	pizzarias	na	minha cidade	que	estejam	abertas	na	segunda-feira	à	noite.

<p>A	essência	da	utilização	de	histórias	de	usuários	como requisitos	está	de	acordo	com	os	valores	do	Manifesto	Ágil</p>

* <b>Indivíduos	e	interações	mais	que	processos	e ferramentas:</b>	elas	enfatizam	a	conversação,	não dependendo	de	processo	ou	de	ferramenta; 
* <b>Software	em	funcionamento	mais	que documentação	abrangente:</b>	elas	vão	direto	ao	ponto com	uma	forma	flexível	de	documentação	para	o	que há	de	maior	valor	para	o	negócio;
* <b>Colaboração	com	o	cliente	mais	que	negociação	de contratos:</b>	por	serem	sucintas	e	necessitarem	da conversação	do	cliente	com	os	desenvolvedores, permitem	a	negociação	e	colaboração	com	o	negócio;
* <b>Responder	a	mudanças	mais	que	seguir	um	plano:</b> elas	respondem	às	mudanças	por	serem	flexíveis	em seu	ciclo	de	vida,	dando	base	para	as	alterações quando	necessárias.

<h3>Modelo 3C</h3>

* <b>Cartão:</b> as	histórias	de	usuário	são	escritas	em cartões	(ou	no	tamanho	de	um	cartão).	Ele	não conterá	toda	a	informação	de	um	requisito,	mas	serve para	lembrar	a	todos	do	que	este	se	trata.	As prioridades	e	os	custos	também	podem	ser	anotados neles. 

* <b>Conversação:</b>	o	requisito	é	comunicado	do	cliente ao	time	por	conversação	(face	a	face),	podendo	ser suplementado	por	documentos. 

* <b>Confirmação:</b> a	confirmação	da	história	dá-se	por exemplos	para	criar	testes	de	aceitação;	ou	seja,	pelos critérios	de	aceitação.	O	cliente	dirá	ao	time	como aceitará	cada	história	por	meio	de	critérios	de aceitação.	Essa	é	uma	ótima	forma	de	suplementar	a documentação.	A	preferência	é	de	que	esses	critérios sejam	automatizados	pelo	time.	A	história	de	usuário estará	pronta	quando	todos	eles	estiverem passando nos	testes	de	aceitação.

<h3>Ciclo de Vida</h3>

<p>Cada	história	segue	um	ciclo	de	vida,	sendo	refinada progressivamente.	Elas	normalmente	nascem	em	épicos	e	são agrupadas	em	temas.	Um	épico	pode	ser	visto	como	uma	história muito	grande	(PICHLER,	2010)	que	pode	levar	diversas	iterações para	serem	desenvolvidas	e	que	ajudam	a	esboçar	a	funcionalidade do	produto	sem	se	comprometer	com	detalhes.	Assim	que priorizado,	ele	é	quebrado em	diversas	histórias.</p>

<p>Um	tema	representa	uma	capacidade	do	produto	ou	um objetivo,	ajudando	a	mostrar	sua	completude	e	também	a encontrar	as	histórias	certas.	Uma	estratégia	é	priorizar	os	temas para,	então,	priorizar	as	histórias	relacionadas.	Aquelas	de	maior prioridade terão	seus	critérios	de	aceitação	completos	e,	depois, serão	refinadas	com	INVEST 	e quebradas	em	tarefas	de	implementação.</p>

<p>Um	exemplo	de	épico	pode	ser:	como	um	repositor	de	estoque, eu	quero	gerenciar	a	reposição	do	supermercado,	fazendo	parte	do tema	“Gestão	de	estoque”.	Uma	história	que	pode	nascer	a	partir dele	é:	como	repositor	de	estoque,	quero	localizar	quais	as prateleiras	do	supermercado	que	contêm	menos	de	50%	de	sua capacidade	de	produtos.</p>

<h3>Utilizando um modelo de escrita</h3>

<p>	Existem	alguns tipos	de	modelos	e	variações;	um	dos	mais	utilizados	é	o	da Connextra,	que	traz	as	informações principais	no cartão:</p>

* <b>Como	um	(As	a…):</b>	para	quem	será	útil	a	história, para	qual	usuário	protagonista	do	sistema;	pode também	ser	uma	persona	(veremos	mais	na	seção Personas); 

* <b>Eu	quero	(I	want…):</b>	o	que	a	história	está especificando	de	requisito,	a	necessidade	do	usuário propriamente	dita; 

* <b>Para	que	(So	that…):</b>	razão	de	negócio,	o	motivo	pelo qual	a	história	existe;	mostra	o	valor	de	negócio	da história.

<h3>Refinando com INVEST</h3>

<p>Muitas	vezes,	as	histórias	de	usuário	precisam	ser	lapidadas, pois	podem	estar	complicadas	de	entender,	grandes	demais	para serem	desenvolvidas,	dependentes	demais	para	serem	entregues, ou	podem	não	ser	verificadas.	Para	esse	refinamento,	utiliza-se	o acrônimo	INVEST,	o	qual	traz	7	características.	Aplicar	todas	elas não	é	tão	fácil;	até	dizem	que	INVEST	é	o	nirvana	das	histórias	de usuários,	mas	deve-se	tentar	ao	máximo	obtê-las.</p>

<p>Refinando	com	INVEST,	uma	história	de	usuário	deve	ser: </p>

* <b>I</b>ndependente	de	outras	histórias	para	facilitar	a negociação,	a	priorização	e	a	implementação; 
* <b>N</b>egociável	com	o	cliente,	para	que	o	time	possa manter	um	ritmo	sustentável	para	a	entrega	contínua de	valor; 
* <b>V</b>alorosa,	assim	cada	entrega	agregará	grande	valor	ao negócio	do	cliente; 
* <b>E</b>stimável,	desse	modo	o	time	poderá	estabelecer	quais histórias	serão	implementadas	de	acordo	com	sua velocidade; 
* <b>S</b>mall	(pequena)	o	suficiente	para	ser	implementada dentro	de	uma	iteração,	sem	correr	grandes	riscos	de não	a	completar;
* <b>T</b>estável,	apenas	assim	poderá	ter	qualidade	na entrega	e	certeza	de	que	o	cliente	aceitará	a	história como	pronta.

<h3>Implementando com tarefas SMART</h3>

<p>Cada	história	de	usuário	possuirá	tarefas	a	serem desenvolvidas,	como:	implementação,	teste,	integração	e	deploy. Quebrá-las	em	tarefas	gera	mais	certeza	do	trabalho	que	o	time precisará	entregar.	Cada	uma	delas	deverá	possuir	as	5 características	do	acrônimo	SMART:</p>

* e<b>S</b>pecífica	o	suficiente	para	ser	entendida,	para	que	se implemente	exatamente	o	que	é	necessário,	evitando	a sobreposição	de	outras	tarefas;
* <b>M</b>ensurável,	possuindo	um	tamanho	para	garantir	que a	tarefa	seja	concluída	(contabilizando	testes	e refatoração); 
* <b>A</b>lcançável	para	que	todos	possam	ter	acesso	às informações	necessárias	para	sua	conclusão;
* <b>R</b>elevante,	contribuindo	para	a	implementação	da história; 
* <b>T</b>ime-boxed,	limitada	a	uma	duração	específica	(não sendo	uma	estimativa	formal,	mas	uma	expectativa	de desenvolvimento,	inclusive	para	pedir	ajuda).	Tarefas com	grande	duração	devem	ser	evitadas,	podendo serem	divididas	em	tarefas	menores	ou	sendo revisadas.

<h3>Personas</h3>

<p>Uma	forma	recomendada	para	pensar	mais	no	usuário	do sistema	é	utilizar	o	conceito	de	personas,	que	é	a	caracterização	de um	papel	de	usuário	do	sistema.	Uma	persona	descreve	as qualidades,	os	valores,	o	comportamento	e	os	objetivos	de	usuários alvos	no	sistema.	Uma	dica	é	dar	nomes	às	personas	que	lembrem seus	papéis;	por	exemplo,	o	nome	Ademar	para	a	persona	relativa ao	papel	de	administrador.	Na	escrita	da	história,	escreve-se	o nome	da	persona,	em	vez	do	papel	de	usuário.</p>

<h3>Escrevendo boas histórias</h3>

* <b>Comece	com	as	histórias	objetivas:</b> os usuários do sistema possuem	objetivos	diretos	no	sistema;	comece escrevendo	as	histórias	que	resolvam	os	problemas desses	objetivos. 
* <b>Fatie	o	bolo:</b>	escreva	histórias	que	possuam	uma camada	de	cada	fase	de	implementação	de	uma funcionalidade,	desse	modo	entregará	valor.	Imagine uma	história	como	uma	fatia	de	bolo,	em	que	cada camada	é	a	parte	de	projeto,	codificação,	teste, integração	e	deploy. 
* <b>Escreva	histórias	fechadas:</b>	faça	com	que	a	história entregue	valor	real	ao	negócio,	algo	que	conclua	o processo	do	usuário. 
* <b>Coloque	as	restrições	nos	cartões:</b>	as	restrições	são	os requisitos	não	funcionais,	como	de	desempenho,	de carga,	de	segurança	e	de	usabilidade.	Elas	podem	ser descritas	nos	cartões	na	forma	de	critérios	de aceitação. 
* <b>Escreva	suas	histórias	no	horizonte:</b>	utilize	o	ciclo	de vida	das	histórias	de	usuário.	Faça	com	que	elas surjam	de	épicos.	Conforme	a	prioridade,	os	épicos são	quebrados	em	histórias	e,	então,	é	iniciada	a especificação	dos	critérios	de	aceitação	relacionados. 
* <b>Evite	a	interface	de	usuário	o	maior	tempo	possível:</b> a	essência	dos	detalhes	da	interface	de	usuário	é	de projeto,	e	não	de	requisito	de	usuário,	na	maioria	das vezes.	Detalhá-la	torna-se	necessário	conforme	a prioridade	aumenta.
* <b>Algumas	coisas	não	são	histórias:</b>	histórias	são	para escrever	requisitos	de	usuário,	e	não	para	documentar a	ajuda	do	sistema,	por	exemplo. 
* <b>Inclua	os	papéis	de	usuários:</b>	a	utilização	de	um modelo	ajuda	nisso,	pois	ele	lembra	de	escrever	para quem	a	história	servirá. 
* <b>Escreva	para	a	persona	protagonista:</b>	muitas	vezes, uma	história	de	usuário	servirá	para	mais	de	uma persona	ou	mais	de	um	papel	de	usuário.	Por	essa razão,	escreva	a	história	para	a	persona	ou	papel	de usuário	que	mais	agregará	valor,	de	maior	propósito. 
* <b>Escreva	em	voz	ativa:</b>	escrever	em	voz	passiva	pode tornar	a	história	confusa. 
* <b>O	cliente	escreve:</b>	apenas	dessa	forma	não	haverá lacunas	na	escrita.	Quando	isso	não	for	possível,	faça com	que	ele	leia,	valide	e	discuta	todas	as	histórias. 
* <b>Dê	títulos	às	histórias:</b>	um	título	ajudará	na	sua identificação.	Não	enumere	apenas	os	cartões	de história,	pois	é	muito	estranho	conversar	sobre	a "história	32".
* <b>Não	esqueça	do	propósito:</b>	lembre-se	sempre	do propósito	de	uma	história	de	usuário,	que	é	servir como	um	lembrete	a	todos	(time	e	cliente)	para	a comunicação	do	requisito. 
* <b>Descreva	os	defeitos	(bugs)	como	critérios	de aceitação:</b> 	quando	houver	um	bug,	provavelmente	é porque	faltou	ter	escrito	(ou	automatizado)	um critério	de	aceitação.	Escreva	um	critério	de	aceitação que	falhe	diretamente	no	problema.

<h3>Catálogo de Story Points</h3>

<p>Para	escrever	boas	histórias,	também	é	necessário	identificar	e evitar	bad	smells	(maus	cheiros).	O	livro	User	stories	applied	do Mike	Cohn	(2004)	possui	um	catálogo	desses	smells,	que	ocorrem normalmente	quando: </p>

* <b>A	história	depende	de	várias	outras	histórias:</b>	a interdependência	impossibilita	a	negociação	e	a priorização	das	histórias; A	história	está	muito	curta:	histórias	são	sucintas, mas	não	é	para	serem	muito	curtas; 
* <b>A	história	possui	muitos	detalhes:</b>	repetindo	que histórias	são	sucintas.	Os	detalhes	normalmente	serão discutidos	entre	o	time	e	o	cliente,	lembre-se	do modelo	3C; 
* <b>Há	funcionalidades	não	necessárias:</b>	lembre-se	do valor	do	XP:	simplicidade.	Quando	houver funcionalidades	desnecessárias	em	histórias,	é	um grande	indicador	de	que	não	se	está	pensando	em simplicidade; 
* <b>O	cliente	não	escreve,	não	confirma	e	não	prioriza as	histórias:</b>	esse	é	um	dos	mais	comuns	e	piores maus	cheiros; 
* <b>Não	está	explícito	o	valor	do	negócio:</b>	escrever	a razão	de	negócio	ajuda	a	demonstrar	seu	valor.	Um modelo	ajuda	nisso.	Histórias	com	pouco	valor	não podem	ser	priorizadas.	Provavelmente,	o	problema está	em	uma	lacuna	na	realização	do	jogo	do planejamento; 
* <b>É	pensado	muito	à	frente	nas	histórias:</b>	isso atrapalha	a	agilidade,	pois	mudanças	poderão	vir	logo, então	não	se	deve	detalhar	muito	à	frente.	Deve-se fazer	somente	o	necessário	para	as	histórias priorizadas; 
* <b>É	detalhada	a	interface	de	usuário	muito antecipadamente:</b>	deve-se	pensar	na	interface	de usuário	quando	a	história	for	priorizada.	Utilize	o tempo	presente	para	trabalhar	com	as	histórias	já priorizadas; 
* <b>Existir	detalhes	específicos	de	tecnologia,	projeto	de banco	de	dados	e	algoritmos:</b>	detalhes	de	projeto	e	de implementação	não	fazem	parte	de	requisitos.	Esses detalhes	deveriam	ser	discutidos	entre	o	time,	ou então	em	outros	formatos	de	especificação,	tais	como diagramas	e	protótipos.

# Capítulo 8

<h3>Testes de Aceitação</h3>

<h4>"Testes	de	aceitação	são	mapas	da	estrada	para	a	iteração, dizendo	ao	time	aonde	é	preciso	ir	e	quais	pontos	de	referência olhar."	─	Lisa	Crispin</h4>

<p>O	propósito	dos	testes	de	aceitação	é	a	comunicação,	a transparência	e	a	precisão	(MARTIN,	2012).	Quando	os desenvolvedores,	os	testadores	e	o	cliente	concordarem	com	eles, todos	entenderão	qual	é	o	plano	para	o	comportamento	do sistema.	Chegar	a	esse	ponto	é	responsabilidade	de	todas	as	partes. Eles	validam	como	o	cliente	aceitará	as	funcionalidades	prontas, pois	são	testes	funcionais	que	guiam	o	time	no	desenvolvimento para,	então,	colocar	em	produção	o	que	foi	decidido	que	o	sistema deve	conter.</p>

<p>Esses	testes	são	criados	a	partir	das	histórias	de	usuários selecionadas	pelas	pessoas	de	negócio	no	planejamento	de iterações	(veremos	no	capítulo	O	jogo	do	planejamento).	A	história de	usuário	apenas	estará	completa	quando	todos	seus	critérios	de aceitação	estiverem	passando.	Auxiliado	pelo	testador	do	time,	o cliente	é	quem	especifica	os	exemplos	dos	critérios	de	aceitação	na forma	de	cenários,	que	podem	conter	dados	e	variações	que criticam	a	história	(CRISPIN,	2009).	Os	exemplos	de	cenários esclarecem	as	histórias	ao	time.</p>

<h3>Automatização</h3>

<p>Testes	de	aceitação	sempre	têm	de	ser	automatizados	por	uma razão	simples:	custo	(MARTIN,	2012).	Caso	você	ache	custoso	ter testes	de	aceitação	automatizados,	aguarde	para	ver	o	custo	da confusão	e	do	debug	de	código	ao	longo	prazo.</p>

<p>Para	fazer	pequenas	entregas	frequentes,	é	necessário	que	os testes	de	aceitação	estejam	automatizados	e	que	rodem	no	build gerado	pelo	servidor	de	integração	contínua.	O	cliente	poderá decidir	se	uma	história	desenvolvida	poderá	ir	para	produção mesmo	quando	alguns	testes	de	aceitação	não	estiverem	passando. Apenas	ele	tem	esse	poder.</p>

<h3>Validando com critérios de aceitação</h3>

<p>Cada	história	de	usuário	possui	um	ou	mais	critério	de aceitação,	criado	também	pelo	cliente.	O	testador	ajuda-o	a	pensar em	cenários	bons	de	teste,	sendo	escritos	já	prevendo	a automatização.	Esses	critérios	descrevem	como	a	história	será aceita	pelo	cliente	e	servem	de	guia	para	o	desenvolvimento.</p>
  
<p>Como	exemplo,	considerando	a	história	Como	um	repositor	de estoque,	quero	localizar	quais	as	prateleiras	do	supermercado	que contêm	menos	de	50%	de	sua	capacidade	de	produtos,	podemos escrever	os	critérios	de	aceitação:</p>

* Deve	exibir	uma	lista	de	prateleiras	com	o	setor	e	a seção	de	cada	uma,	e	o	tipo	e	o	nome	do	produto contido;
* Deve	exibir	as	prateleiras	com	menos	de	50%	da capacidade	de	itens; 
* Não	deve	exibir	as	prateleiras	com	50%	ou	mais	da capacidade	de	itens.

<p>Os	critérios	de	aceitação	também	podem	seguir	um	modelo. Comumente,	o	utilizado	é	o	de	cenários	de	BDD	(BehaviourDriven	Development	─	Desenvolvimento	Guiado	por Comportamento)	(NORTH,	2006).	Esse	modelo	possui	três informações:</p>

* <b>Dado	que:</b>	precondição,	são	os	passos	para	preparar para	ação	a	ser	validada; 
* <b>Quando:</b>	ação	que	vai	disparar	o	resultado	a	ser validado; 
* <b>Então:</b>	resultado	a	ser	validado.

<p>Você	encontrará	bons	exemplos	de	histórias	com	critérios	de aceitação	no	livro	Histórias	de	usuário	(HELM;	WILDT,	2014). Como	um	exemplo,	o	critério	de	aceitação	Deve	exibir	o	setor	e	a seção	da	prateleira	com	o	tipo	e	o	nome	do	produto	usando	o modelo,	ficará	desta	forma:</p>

* <b>Dado	que</b>	o	usuário	logado	é	um	repositor	de	estoque; 
* <b>Quando</b>	o	item	de	menu	“Consultar	prateleiras	para reposição”	for	clicado; 
* <b>Então</b>	a	lista	de	todas	as	prateleiras	para	reposição	é exibida.

# Capítulo 9

<h3>Liberação frequente de pequenas entregas</h3>

<h4>"Software	funcionando	é	a	medida	primária	de	progresso."	─	7º princípio	do	Manifesto	Ágil</h4>

<p>Diversos	benefícios	surgem	quando	se	liberam	frequentemente pequenas	entregas	com	alto	valor: </p>

* Entrega	de	valor	adiantado	e	contínuo; 
* O	processo	é	aprimorado	rapidamente	por	falhar	mais cedo	(conceito	fail	fast);
* Feedback	do	cliente	mais	cedo	para	confirmação	ou adaptação	dos	requisitos;
* Satisfação	dos	usuários	por	ter	respostas	rápidas	às suas	necessidades; 
* Maior	qualidade,	confiança	e	estabilidade; 
* Reduz	a	taxa	de	defeitos	por	precisar	realizar	testes completos	em	ciclos	menores; 
* Realiza	um	design	simplificado	e	suficiente	apenas para	a	entrega	em	questão; 
* O	código	é	atualizado	e	integrado	com	maior frequência; 
* O	software	não	fica	ultrapassado; 
* Maior	engajamento	do	time	por	ver	seu	trabalho sendo	útil	e	empoderado; 
* Facilita	enxergar	os	diversos	desperdícios	ocultados nas	grandes	entregas; 
* Evita	a	procrastinação	de	prazos.

<h3>Foco na qualidade é o ponto chave</h3>

<p>A	qualidade	é	o	ponto-chave	para	entregar	com	frequência.	Os testes	automatizados	e	a	integração	contínua	são	essenciais	para agilizar	os	builds	das	entregas	com	alta	qualidade	no	software.</p>

<h3>Releases tudo ou nada</h3>

<p>Quanto	mais	tempo	aguardamos	para	liberar	uma funcionalidade	aos	usuários,	menos	tempo	você	terá	e	mais complexo	será	para	adaptá-la	ou	corrigi-la.	Na	visão	enxuta (LIKER,	2005),	a	liberação	frequente	de	pequenas	entregas	diminui consideravelmente	os	desperdícios	de	estoque,	defeitos	e	tempo	de espera	(do	cliente).	Isso	gera	fluidez	e	reduz	o	tempo	de	ciclo	das entregas	(tempo entre	o	fim	ou	o	início	de	produção	de	dois	itens).</p>

# Capítulo 10

<h3>O jogo do planejamento</h3>

<h4>"Planos	não	são	nada.	Planejamento	é	tudo."	─	Dwight	David "Ike"	Eisenhower</h4>

<p>As	pessoas	de	negócio	definem	o	escopo,	a	prioridade,	a composição	e	as	datas	das	entregas.	As	decisões	de	negócio	têm suporte	das	pessoas	de	desenvolvimento.	Estas	tomam	decisões técnicas	por	meio	de	estimativas	e	de	análises	de	consequências técnicas	no negócio,	e	decidem	seu	processo	de	trabalho.	Tanto	o Negócio	quanto	o	Desenvolvimento	têm	voz	nas	decisões	das entregas.	Não	há bola	de	neve	no	XP.</p>

<h3>Definindo o jogo e suas regras</h3>

* <b>Objetivo:</b>	maximizar	o	valor	do	software	produzido pelo	time;	ou	seja,	colocar	em	produção	a	maior quantidade	de	histórias	de	usuário	com	maior	valor	ao longo do projeto;

* <b>Estratégia:</b>	o	time	deve	investir	o	menor	esforço	para colocar	a	funcionalidade	de	maior	valor	em	produção tão	rápido	quanto	possível,	em	conjunto	com estratégias	de	projeto	e	programação	para	reduzir	o risco.	Dividir	para	conquistar	é	a	estratégia	utilizada ao	dividir	o	software	em	entregas	frequentes,	e	cada entrega	em	iterações	pequenas. 

* <b>As	peças:<b/>	as	peças	básicas	do	jogo	são	histórias	de usuário	e	as	tarefas	de	implementação.	As	histórias	são as	peças	no	planejamento	das	releases;	já	as	tarefas,	no planejamento	das	iterações.

* <b>Os	jogadores:</b>	as	pessoas	do	Desenvolvimento	e	as pessoas	de	Negócio. 

* <b>Os	movimentos:</b>	as	regras	dos	movimentos	existem para	lembrar	a	todos	de	como	eles	gostariam	de	agir em	um	melhor	ambiente	com	confiança	mútua	e	dar uma	referência	para	quando	as	coisas	não	estiverem indo	bem.

<h3>Entendendo regras e comprometimento</h3>

<h3>Parte A - Planejamento de Releases</h3>

1 - Escrever histórias
2 - Estimar histórias
3 - Quebrar histórias grandes
4 - Ordenar por valor
5 - Ordenar por risco
6 - Ordenar por velocidade
7 - Selecionar escopo
8 - Selecionar iteração
9 - Recuperar?
10 - Negociar nova história?
11 - Reestimar?

<h3>Parte B - Planejamento de Iterações</h3>

1 - Escrever tarefas
2 - Quebrar ou unir tarefas
3 - Estabelecer fator de carga
4 - Balancear tarefas
5 - Estimar tarefas
6 - Aceitar tarefas
7 - Implementar tarefas
8 - Registrar progresso
9 - Recuperar?
10 - Verificar histórias prontas

<h3>Planejamento de releases</h3>

<p>Para	uma	release,	o	jogo	do	planejamento	define	as	regras	para o	cliente	direcionar	o	desenvolvimento	na	frequência	de	uma	a	três semanas.	Seus	movimentos	para	uma	release	são	dados	em	três fases:	Exploração,	Comprometimento	e	Direcionamento.</p>

<p><b>Exploração:</b>	ambos	os	jogadores	descobrem	novos itens	que	o	sistema	pode	fazer,	dividindo-se	em	três movimentos:</p>

* Escrever	uma	história	de	usuário:	o	Negócio escreve	algo	que	o	sistema	deverá	fazer;
* Estimar	uma	história	de	usuário:	o Desenvolvimento	estima	o	tempo	ideal	de programação	para	implementar	a	história;
* Quebrar	uma	história	de	usuário:	caso	o Desenvolvimento	não	consiga	estimar	a	história ou	sua	estimativa	for	muito	grande,	o	Negócio identifica	sua	parte	mais	importante	para	que	o Desenvolvimento	possa	estimá-la	e	desenvolvêla.	Spikes	podem	ser	utilizados para	melhorar	a estimativa	da	história.

<p><b>Comprometimento:</b>	o	Negócio	decide	o	escopo	e	o tempo	para	a	próxima	entrega	de	acordo	com	as estimativas,	e	o	Desenvolvimento	se	compromete	com a	entrega,	dividindo-se	em	quatro	movimentos:</p>

* Ordenar	por	valor:	o	Negócio	separa	as	histórias em	três	categorias:	as	essenciais;	as	menos essenciais,	mas	de	alto	valor; e	as	que	seriam agradáveis	de	se	ter; 
* Ordenar	por	risco:	o	Desenvolvimento	separa	as histórias	em	três	categorias:	aquelas	que	podem ser	estimadas	com	precisão,	aquelas	que	podem ser	estimadas	razoavelmente	bem,	e	aquelas	que não	podem	ser	estimadas	de	qualquer	modo; 
* Ordenar	por	velocidade:	o	Desenvolvimento mostra	ao	Negócio	quanto	de	tempo	ideal	de programação	o	time	poderá	trabalhar	em	um mês do	calendário; 
* Selecionar	escopo:	o	Negócio	escolhe	as	histórias para	a	entrega	(trabalhando	por	tempo)	ou	uma data	para	as	histórias	a	serem	desenvolvidas (trabalhando	por	escopo),	utilizando	as estimativas	realizadas	pelo	Desenvolvimento. 

<p><b>Direcionamento:</b>	o	plano	é	atualizado	no	que	foi aprendido	pelo	Negócio	e	pelo	Desenvolvimento, dividindo-se	em	quatro	movimentos:</p>

* Iteração:	a	cada	iteração	(uma	a	três	semanas),	o Negócio	seleciona	uma	com	as	histórias	de	maior valor	a	serem	implementadas; * Recuperação:	caso	o	Desenvolvimento	descubra que	sua	velocidade	foi	superestimada,	ele	pode pedir	ao	Negócio	para	encaixar	apenas	as histórias	de	maior	valor	de	acordo	com	a	nova velocidade; 
* Nova	história:	caso	o	Negócio	descubra	uma nova	história	a	ser	adicionada	à	entrega	que	já está	sendo	desenvolvida,	ele	pode	escrevê-la,	o Desenvolvimento	estimá-la,	e,	então,	trocá-la	por outra	selecionada	pelo	Negócio; 
* Reestimar:	caso	o	Desenvolvimento	descubra	que o	plano	não	é	exato,	ele	pode	reestimar	todas	as histórias	restantes.

<h3>Planejamento de iterações</h3>

<p>	As	decisões	sobre	as	iterações	são	mais	flexíveis em	questão	de	escopo	e	de	prazos,	pois	dependem	mais	do Desenvolvimento;	enquanto	as	sobre	entregas	dependem	mais	do Negócio.	Suas	fases	são	semelhantes	às	de	uma	entrega: Exploração, Comprometimento	e	Direcionamento.</p>

<p><b>Exploração:</b>	o	Desenvolvimento	cria	suas	tarefas	e identifica	o	tempo	de	trabalho,	dividindo-se	em	três movimentos:</p>

* Escrever	uma	tarefa:	transformar	as	histórias	da iteração	atual	em	tarefas; 
* Quebrar	ou	unir	tarefas:	caso	a	tarefa	esteja grande	demais,	quebre-a	em	tarefas	menores. Caso	ela	esteja	pequena	demais,	una-a	a	outra relacionada; 
* Estabeleça	um	fator	de	carga:	cada	programador escolherá	seu	fator	de	carga	para	a	iteração,	o qual	é	a	porcentagem	de	tempo	que	ele	realmente estará	desenvolvendo;	ou	seja,	é	removido	o tempo	em	que	se	realiza	outras,	tais	como reuniões	do	time.

<p><b>Comprometimento:</b>	o	Desenvolvimento compromete-se	com	suas	tarefas,	dividindo-se	em	três movimentos:</p>

* Aceitar	uma	tarefa:	o	programador	puxa	a	tarefa para	si	e	aceita	a	responsabilidade	por	ela; 
* Estimar	a	tarefa:	o	programador	responsável	pela tarefa	a	estima	em	Dias	Ideais	de	programação;
* Balanceamento:	cada	programador	soma	suas tarefas	e	multiplica	pelo	fator	de	carga, balanceando	sua	carga	de	trabalho,	caso	esteja maior	ou	menor	do	que	a	estabelecida. 

<p><b>Direcionamento:</b>	o	Desenvolvimento	desenvolve	as tarefas	para	verificar	a	história,	dividindo-se	em quatro	movimentos:</p>

* Implementar	uma	tarefa:	o	programador	pega	o cartão	da	tarefa,	encontra	um	par	para programar,	desenvolve	a	tarefa	com	TDD (Desenvolvimento	Guiado	por	Testes)	e	ao	final integra	o	código	fazendo	passar	a	suíte	de	teste relacionada; 
* Registrar	progresso:	a	cada	dois	ou	três	dias,	um membro	do	time	atualiza	o	andamento	das tarefas	de	cada	membro,	com	o	tempo	gasto	e	o tempo	que	falta	para	cada	tarefa; 
* Recuperação:	programadores	que	ficaram sobrecarregados	pedem	ajuda	reduzindo	o escopo	das	tarefas,	reduzindo	o	escopo	das histórias, removendo	aquelas	não	essenciais	ou pedindo	ao	cliente	para	postergar	a	história	para outra	iteração; 
* Verificar	a	história:	caso	estiverem	prontos,	rodar os	testes	funcionais	para	as	tarefas	que	já	foram concluídas,	complementando a	suíte	de	testes funcionais	com	os	novos	casos	de	testes;

<h3>Mantendo o foco</h3>

<p>Você	lembra-se	do	objetivo	do	jogo	do	planejamento? Maximizar	o	valor	do	software	construído	pelo	time	para	o	cliente é	o	foco	do	jogo.	É	importante	que	todos	participem (Desenvolvimento	e	Negócio)	com	colaboração.</p>

<h3>Todo momomento é um momento de aprendizado</h3>

<p>No	jogo	do	planejamento,	até	quando	se	erra,	aprende-se.	O erro	não	é	visto	como	algo	ruim,	desde	que	se	aprenda	com	ele. Quando	o	time	reconhecer	que	superestimou	sua	velocidade,	ele deve	comunicar	ao	Negócio	para	rearranjar	as	histórias	dentro	de sua	nova	velocidade.	Quando	houver	problemas	com	as estimativas,	devem-se	reavaliar	essas	estimativas	das	histórias.	É preciso	ter coragem	para	buscar	um	processo	que	seja transparente.	A	comunicação	e	o	feedback	são	importantes	para que	os	dois	jogadores	aprendam	a	melhor	forma	de	maximizar	o jogo.</p>

# Capítulo 11

<h3>Spikes de Planejamento</h3>

<h4>"Algumas	vezes,	a	melhor	maneira	de	resolver	um	problema	é	ir para	casa,	jantar,	assistir	TV,	ir	para	a	cama,	e,	então,	acordar	na manhã	seguinte	e	tomar	um	banho."	─	Robert	C.	Martin</h4>

<p>Os	spikes	de	planejamento	fazem	parte	de	uma	prática	que ajuda	o	time	a	gerar	o	conhecimento	necessário	para	estimar	as histórias	de	usuários	corretamente,	diminuindo,	assim,	o	risco	no planejamento	(WILDT;	LACERDA,	2010).	O	objetivo	é	aumentar a	confiança	para	um	bom	jogo	do	planejamento.	Um	spike	é	um programa	muito	simples	para	explorar	soluções	potenciais (WELLS,	1999).</p>

<p>Faça	spikes	arquiteturais	para	descobrir	respostas	em dificuldades	técnicas	e	em	problemas	de	design,	ou	para	conhecer novas	tecnologias	(APIs,	frameworks,	ferramentas,	linguagens	de programação	etc.).	Quando	uma	dificuldade	técnica	importante surgir,	deixe	um	par	de	desenvolvedores	fazer	uma	por	alguns	dias até	ter	certeza	suficiente	sobre	sua	solução.</p>

<p>Por	ser	uma	tarefa	a	ser	realizada,	os	spikes	podem	ser estimados.	Portanto,	trata-se	de	um	momento	planejado, garantindo-se que	será	feito	durante	uma	iteração. Preferencialmente,	faça-o	em	uma	iteração	e	somente	desenvolva	a história	de	usuário relativa	na	próxima.	Lembre-se	que	ele	serve para	diminuir	o	risco	da	estimativa	que	servirá	no	próximo planejamento,	e	também	não	se	esqueça	de	não	aproveitar	seu código.</p>

<h3>Jogue fora o código gerado no spike</h3>

<p>Trate	o	spike	como	um	experimento	e	assuma	que	seu	código será	jogado	fora.	Vá	direto	ao	ponto	para	resolver	a	incerteza.	Ele serve	para	saber	como	resolver	um	problema,	e	não	para	produzir um	código	(de	produção)	que	o	resolva	(SHORE,	2010).	Não	tente criar	programas	úteis	ou	reutilizáveis	em	produção.	O	spike	serve para	aprendizado,	uma	vez	que	se	trata	de	uma	prática	para descoberta.	Por	isso,	ignore	todas	as	preocupações	no	entorno	da questão.</p>

# Capítulo 12

<h3>Projeto simples do início ao fim</h3>

<h4>"Simplicidade	é	mais	complicada	do	que	você	pensa.	Mas	ela	é bem	valiosa."	─	Ron	Jeffries</h4>

<p>Para	termos	um	código	limpo,	a	refatoração	é	necessária,	assim evitando	os	code	smells	(maus	cheiros)	nele.	Um	código	é	simples (JEFFRIES,	2000)	quando:</p>

* Roda	todos	os	testes; 
* Expressa	todas	as	ideias	necessárias; 
* Não	contém	código	duplicado; 
* Possui	a	menor	quantidade	de	classes,	métodos	e variáveis; 
* É	conciso	e	legível.

<h3>MVP</h3>

<h4>"Simplicidade	─	a	arte	de	maximizar	a	quantidade	de	trabalho não	realizado	─	é	essencial."	─	Décimo	princípio	do	Manifesto Ágil</h4>

<p>A	expressão	YAGNI	(do	inglês,	You’re	Not	Gonna	Need	It	─ Você	não	precisará	disso)	lembra	todos	a	desenvolver	somente	o necessário	nas	histórias	atuais,	até	no	caso	de	que	se	saiba	que	será necessário	no	futuro.</p>

<p>Menos	é	mais.	A	simplicidade	tem	foco	no	desenvolvimento	da essência	do	software.	Pequenas	entregas	de	valor	representam muito	do	que	o	cliente	necessita.	Alguns	programadores	(não	XP) adoram	entregar	algo	a	mais	ao	cliente;	já	os	extremos	não	fazem isso.	Programadores	XP	mantêm	o	projeto	simples	do	início	ao fim.</p>

# Capítulo 13

<h3>Metáfora de Sistema</h3>

<h4>"98%	de	nosso	pensamento	 está	 realmente	acontecendo	em	um nível	 inconsciente,	 grande	 parte	 através	 de	 metáforas." ─  Esther Derby</h4>

<p>No	 XP,	 a	 metáfora	 de	 sistema	 traz	 uma	 visão	 comum	 que auxilia	o	 time	e	o	cliente	a	entender	os	elementos	do	sistema.	Ela funciona	como	um	pattern	de	alto	nível	e	explica	 seu	design	 sem uma	documentação	pesada.	Ela	é	semelhante	à	linguagem	ubíqua, porém,	 enquanto	 esta	 se	 concentra	 em	 uma	 linguagem	 comum entre	o	negócio	e	os	desenvolvedores,	aquela	foca	na	linguagem	da arquitetura	da	solução.</p>

<p>O	 nascimento	 dessa	 prática	 deu-se	 no	 sistema	 de	 folha	 de pagamento	 da	 Chrysler	 (KHALED;	 NOBLE;	 BIDDLE,	 2004).	 A
metáfora	era	de	uma	fábrica	para	produzir	o	salário,	onde	as	caixas desciam	 em	 uma	 linha	 de	 montagem	 para	 serem  montadas.	 As caixas	 são	 as	 partes	 do	 salário	 a	 serem	 montadas	 em	 um	 item apenas:	o	salário	do	funcionário.	Um	outro	exemplo	é	o	de	James Shore	 em	 seu	 primeiro	 projeto	 XP,	 que	 era	 de	 data	 warehouse (armazém	 de	 dados)	 (SHORE,	2008),	 cujos	 nomes	 das	 classes	 do sistema	 utilizavam	 a	 metáfora	 de	 uma	 empilhadeira	 em	 um armazém.</p>

<p>Muitas	 pessoas	 ignoram	 o	 uso	 dessa	 prática	 por	 não conhecerem	 sua	 utilidade.	 Uma	 metáfora	 de	 sistema	 ajuda	 a padronizar	os	nomes	dos	objetos	para	entendê-lo	e	também	auxilia a	reutilizar	códigos.	Desse	modo,	o	desenvolvedor	pode	descobrir se	 algum	 objeto	 já	 existe	 no	 software	 e	 decidir	 onde	 é	 o	 melhor local	 para	 colocá-lo.	 Por	 trazer	 um	 vocabulário	 compartilhado,	 é uma	excelente	fonte	de	comunicação	entre	a	equipe	e	pode	facilitar também	 na	 discussão	 das	 estimativas.	Apenas	 uma	 boa	metáfora pode	ser	realmente	efetiva.</p>

<h3>Descobrindo uma boa metáfora</h3>

<p>Joshua	 Kerievsky	 (2009)	 define	 os	 três	 Is	 da	 metáfora: Iluminação,	Inspiração	e	Integridade.	Uma	boa	metáfora	auxilia	a
iluminar	 o	 design,	 inspirar	 novas	 ideias	 e	 ajudar	 a	 sentir	 que	 o projeto	do	sistema	está	coerente,	encaixando-se	bem	em	conjunto. Deve-se	buscar	uma	que	contenha	esses	três	itens.</p>

# Capítulo 14

<h3>Reunião Diária em Pé</h3>

<h4>"Ter	as	melhores	ideias,	o	código	mais	afinado,	ou	o	pensamento mais	 pragmático	 é,	 em	 última	instância,	 estéril,	 a	menos	 que	 você possa	 se	 comunicar	 com	 outras	 pessoas.” ─	 Andy	 Hunt	 &	 Dave Thomas</h4>

<h4>"Ao	 longo	 dos	 anos,	 eu	 tenho	 desenvolvido	 uma	 simples	 regra: quando	a	reunião	fica	entediante,	saia.” ─	Robert	C.	Martin</h4>

<p>Para	o	time	no	XP,	as	reuniões	diárias	em	pé	─	do	inglês	Daily Stand	Up	Meeting ─	são	focadas	e	rápidas,	ocorrem	no	começo	do dia	 e	 duram	 até	 quinze	 minutos.	 Seu	 formato	 físico	 é	 simples: todos	 de	 pé	 formam	 um	 círculo	 e	 cada	 pessoa	 tem	 a	 sua	 vez	 de falar	no	sentido	horário	(ou	anti-horário).	Ela	faz	com	que	o	time mantenha-se	 alinhado,	 trocando	 conhecimento	 constantemente. Ao	 começar	 a	 fazê-las,	 diversos	 erros	 comuns	 podem	 ocorrer.</p>

<h3>Troca de Conhecimento</h3>

<p>Na	 reunião	 diária,	 cada	 indivíduo	 sabe	 o	 que	 o	 outro	 está trabalhando	 e	 se	 possui	 problemas	 relacionados	 a	 isso.	 Qualquer membro	do	grupo	pode	pedir	e	oferecer	ajuda	ao	outro,	tanto	em dúvidas	 de	 negócio,	 quanto	 de	 técnicas.	 Mesmo	 que	 cada programador	 puxe	 as	 tarefas	 das	 quais	 tem	 conhecimento suficiente	 para	 desenvolver,	 algumas	 virão	 somente	 durante	 seu desenvolvimento.	Muitas	vezes,	algo	que	foi	dito	na	reunião	servirá como	 referência	 no	 futuro.	 Uma	 boa	 forma	 para	 pedir	 ajuda	 é parear	(programar	em	pares)	com	a	pessoa	referente	ao	assunto	em questão.	Assim,	o	aprendizado	e	a	troca	de	conhecimento	tornamse constantes	e	colaborativos.</p>

<h3>Erros Comuns</h3>

* <b>Reunião	 de	 status:</b>	 a	 diária	 não	 é	 uma	 reunião	 de status	 reporting	 para	 uma	 pessoa,	 tal	 como	 um
coordenador	ou	gerente.	Caso	seja	necessário,	a	dica	é realizá-la	 após	 alguém	 fazer	 o	 status	 reporting, possivelmente	o	Tracker.

* <b>Discutir	soluções:</b>	um	dos	propósitos	dessa	reunião	é identificar	 problemas,	 não	 resolvê-los.	 A	 dica	 é continuar	 com	 a	 reunião	 diária,	 deixando	 a	 conversa sobre	as	solução	para	depois	dela.

* <b>O	 time	 não	 vê	 valor:</b>	 isso	 pode	 ocorrer	 quando	 um time	 ágil	 está	 se	 formando.	 A	 dica	 é	 levantar	 esse
problema	 na	 próxima	 reunião	 de	 retrospectiva	 do time.	Não	postergue.

* <b>Não	 ter	 um	 horário	 fixo:</b>	 todos	 do	 time	 precisam saber	 o	 horário	 fixo	 diário	 da	 reunião	 para	 segui-lo
estritamente.	 O	 horário	 da	 diária	 deve	 ser	 sagrado. Uma	 dica	 é	 ter	 o	 papel	 do	 "chato	 da	 diária";	 uma
pessoa	eleita	para	lembrar	do	horário	e	dar	um	 toque caso	 a	 reunião	 demore	 ou	 perca	 o	 foco.	 Outra	 dica: 
um	despertador	ajuda	a	lembrar	o	time.

* <b>Sem	local	 dedicado:</b>	 é	 importante	 manter	 um	 único lugar	para	que	o	 time	faça	a	diária,	de	preferência	ao próprio	 local	 de	 trabalho.	 A	 dica	 é	 fazer	 a	 reunião próximo	ao	quadro	de	histórias	e	tarefas	para	a	gestão visual.

* <b>Não	 saber	 ouvir:</b	 para	 uma	 boa	 comunicação,	 é necessário	 saber	 falar	 e	 também	 ouvir	 atentamente Uma	 dica	 é	 ter um	 token	 para	 chamar	 a	 atenção	 de todos.	 Ele	 pode	 ser	 qualquer	 objeto	 que	 chame	 a atenção.	Se	for	um	objeto	engraçado,	fica	mais	fácil	de pedir	a	atenção	de	 todos.	 Já	vimos	equipes	utilizando canetas	 de	 quadro,	 apagadores,	 guarda-chuvas	 e	 até garrafa	de	óleo	diesel	(em	uma	empresa	de	refinaria). O	token	é	como	uma	bengala:	é	para	ser	temporário até que	o	time	caminhe	bem	nas	diárias.
  
* <b>Não	 fazer	 a	 reunião,	 porque	 um	 indivíduo	 está ausente:</b>	 é	melhor	 ter	 uma	 reunião	 sem	 um	membro do	time	do	que	não	tê-la.	A	dica	é	simples:	apenas	faça a	reunião. 

* <b>Não	 ficar	 de	 pé:</b>	 uma	 dica	 de	 produtividade	 é	 fazer com	 que	 todos	 os	 participantes	 fiquem	 de	 pé	 na reunião	para	que	ela	seja	rápida	e	tenha	foco.	Isso	faz com	que	as	pessoas	prestem	mais	atenção	nas	outras. Reuniões	improdutivas com	elas	 sentadas	fazem	com que	 seja	 confortável	 a	 participação.	 Caso	 ela	 perca	 o foco,	as	pessoas	ficarão	cansadas	e	logo vão	querer	dar um	jeito	de	realinhar	e	finalizá-la.
