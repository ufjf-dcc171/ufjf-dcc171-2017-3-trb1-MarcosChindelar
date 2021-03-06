{\rtf1\ansi\ansicpg1252\deff0\nouicompat\deflang1046{\fonttbl{\f0\fnil\fcharset0 Calibri;}{\f1\fnil\fcharset2 Symbol;}}
{\*\generator Riched20 10.0.15063}\viewkind4\uc1 
\pard\sa200\sl276\slmult1\f0\fs22\lang22 Trabalho 01 - Laborat\'f3rio de Programa\'e7\'e3o III\par
Nome: Marcos Roberto Chindelar de Oliveira Leite\par
Matricula: 201165248AC\par
Curso: Ci\'eancia da Computa\'e7\'e3o\par
\tab O sistema desenvolvido tem como objetivo atender a bares, lanchonetes e outros estabelecimentos afins, aonde se tem um conjunto de mesas, que tem um conjunto de pedidos e que por sua vez um conjunto de itens. \line\tab Dessa forma um pedido seria um conjunto de itens que possuem como atributo: o  nome do item(que seria o produto em si), a quantidade pedida do item e o pre\'e7o do item. O pedido tamb\'e9m possui um atributo de  registro da hora que o pedido foi feito e fechado e um campo de identifica\'e7\'e3o do pedido, para que se possa ter um controle dos pedidos feitos por cada mesa, que possui um identificador e uma lista de pedidos.\line\tab Para atender a esse cen\'e1rio, foi desenvolvido um sistema que capaz de executar cada uma das tarefas abaixo:\par

\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720\sa200\sl276\slmult1 Abrir a comanda de uma mesa: Inserir uma nova mesa no sistema para que possam ser feitos os pedidos dos clientes da mesa em quest\'e3o.\par
{\pntext\f1\'B7\tab}Gerenciar um pedido: Cria,exclui ou apaga um pedido de uma mesa. Tamb\'e9m \'e9 possivel fechar um pedido, impedindo assim de modifica-lo.\par
{\pntext\f1\'B7\tab}Genciar os itens de um pedido: Cria,exclui ou apaga um item de um pedido.\par

\pard\sa200\sl276\slmult1 O sistema possui duas janelas que funcionam da seguinte forma:\par

\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720\sa200\sl276\slmult1 Principal: Nessa janela \'e9 possivel gerenciar as mesas e os pedidos, atendendo as duas primeiras tarefas citadas anteriormente. Essa janela possui os os bot\'f5es de criar mesa,criar pedido,excluir pedido,fechar pedido e os componentes de exibi\'e7\'e3o das informa\'e7\'f5es da lista de mesas, dos pedidos de cada mesa e dos intens de cada pedido.\par
{\pntext\f1\'B7\tab}Gerenciamento de itens: Nessa janela \'e9 possivel gerenciar os itens de cada pedido, atendendo a terceira tarefa citada anteriormente. Essa janela \'e9 aberta ao se clicar no bot\'e3o de criar pedido: caso um pedido esteja selecionado, a janela exibira as informa\'e7\'f5es dos itens do pedido, permitindo edita-los caso o pedido n\'e3o esteja fechado. Caso nenhum pedido esteja selecionado, um novo pedido ser\'e1 criado e a janela exibira as informa\'e7\'f5es necessarias para a cria\'e7\'e3o dos itens do novo pedido.\par

\pard\sa200\sl276\slmult1 Alguns pontos importantes do funcionamento do sistema:\par

\pard{\pntext\f1\'B7\tab}{\*\pn\pnlvlblt\pnf1\pnindent0{\pntxtb\'B7}}\fi-360\li720\sa200\sl276\slmult1 Todo pedido est\'e1 relacionado a uma mesa, n\'e3o sendo permitido a cria\'e7\'e3o de um pedido que n\'e3o esteja vinculado a uma mesa.\par
{\pntext\f1\'B7\tab}Todo item est\'e1 relacionado a um pedido, n\'e3o sendo permitido a cria\'e7\'e3o de um item que n\'e3o esteja vinculado a um pedido.\par
{\pntext\f1\'B7\tab}N\'e3o \'e9 possivel excluir uma mesa, pois novos clientes podem chegar e ocupa-la.\par
{\pntext\f1\'B7\tab}Caso um pedido esteja registrado como fechado, n\'e3o \'e9 possiv\'e9l edita-lo.\par
{\pntext\f1\'B7\tab}Caso um pedido esteja registrado como fechado, ainda sim \'e9 possivel exclui-lo.\par
{\pntext\f1\'B7\tab}Um pedido pode conter v\'e1rios itens diferentes ou n\'e3o.\par

\pard\sa200\sl276\slmult1 Os maiores problemas ao desenvolver o sistema foram: O planejamento do layout das interfaces que muitas vezes n\'e3o ficavam visualmente agradaveis( n\'e3o apresentando simetria ou confusos por exemplo) e a manipula\'e7\'e3o de mais de uma janela, de forma que a segunda trouxesse alguns dados da primeira janela e pudesse manipula-los tamb\'e9m.\par
Como melhoria podem ser implmentadas algunas funcionalidades como por exemplo: Calculo do valor total do pedido, divis\'e3o do valor do pedido pelo numero de clientes que est\'e3 ocupando a mesa, melhorias de interface, maior controle dos dados inseridos em cada campo e a implementa\'e7\'e3o da persistencia dos dados do sistema.\par
\par
}
 