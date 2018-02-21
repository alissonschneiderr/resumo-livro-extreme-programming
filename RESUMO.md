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
