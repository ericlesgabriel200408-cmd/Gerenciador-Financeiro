### Olá , somos o grupo 28, composto por Ericles e Nathan. Abaixo está uma descrição de nosso projeto, suas funcionalidades e motivos da escolha.
#1
Nome do projeto: 
Tema escolhido: Controle Financeiro Pessoal
Grupo: 28
Integrantes: Ericles Gabriel Clemente Queiroz / Nathan Gabriel Nunes dos Santos
Período/Turma: Matutino / 42_32160_Presencial_90

#2
FIFO é uma fila onde o primeiro que entra é o primeiro que sai, no programa foi usada no Fila_pagamentos e despesas_pagas, para mostrar a primeria transação.

LIFO é onde o ultimo que entrar é o primerio a sair, no programa ele foi utilizado no pilha_pagamentos_realizados.

Não olhei muito pro lado do dicionário e ele foi tulizados apenas na ultima def do tarefas.py ele foi utilizado como .get na pilha_pagamentos_realizados.

Lista e Tupla, Lista ela nos permite alterar informações, e a tupla ela é imutável.
A lista foi utilizada nas variações globais para listar tudo e ficar no banco de dados para acessa-los sempre que possivel.
A tupla foi ulizada com frequência para salvamento de dados e carregamentos de dados, assim não teria qualquer tipo de alteração no conteúdo já informado, garantindo melhor funcionamento das informações.

Modularização ela é a divisão de partes de um programa, no caso nosso projeto foi dividido em 6 partes, sendo elas: Dados.py , Main.py , Tarefas.py , Utils.py , Readme.md e Changelog.md.

3. Como executar o projeto
Versão do Python 3.12.3 
Comando para executar no Terminal: python main.py
Não temos nenhuma biblioteca externa, apenas padrões.

4.
Requisitos obrigatórios
• Cadastrar transação (descrição, valor, tipo:
receita/despesa, categoria)
• Listar todas as transações com status
• Fila de despesas pendentes — FIFO: mais
antiga paga primeiro
• Pilha de pagamentos realizados — LIFO:
último pagamento no topo
• Atualizar status: Pendente > Pago
• Exibir saldo atual (receitas - despesas
pagas
 
A escolha de um gerenciador financeiro foi por 2 motivos, Primeiro para mim (Ericles) foi por conta que eu ja pensava em algo para me ajudar com as minhas contas e organizar minhas finanças pessoais, mas queira fazer um teste em programação para ver.

 O segundo motivo foi do (Nathan) ele achou uma funcionalidade util para o dia a dia, então chegamos a conclusão dessa escolha.

 O objetivo do programa basicamente é servir de gerenciador financeiro, contendo as transações, receita e gastos. Usando essa base o programa identifica despesas para o usuário pagar, contas que foram pagas, além de uma analíse geral de gastos e receitas, contendo seu saldo liquído que sobra a partir dos gastos e despesas informados.

 Sua funcioanlidade é bem simples e o visual bem direto, para melhor entendimento dos usuários, um exemplo são as opções de escolhas
 Onde deixa bem explicíta o que cada opção faz.

 Durante a criação tivemos alguns quebras-cabeças dentro dos códigos, pois tinha muitas opções no inicío, onde após o código estar basicamente estruturado, começamos com os testes e vimos coisas desnecessárias onde em vez de ajudar estava atrapalhando, um exemplo:
 funcionalidade adicionar salário liquído, não entrava no processamento de dados para calcúlo
 acabamos de optar por removê-lo pois o adicionar transação já serveria , pois tinha dentro a opção receita.
 
 Durante a estrutura do código e suas funções foi deixado algumas # informativas, até para facilitar para continuar os codigos e não se perder caso precise sair ou fechar o programa.

 Basicamente, tudo foi começado pelo main.py , tendo um "Menu" visualmente ajudou a dar continuação organizada e ir testando as funções durante o desenvolvimento.

 Logo após foi começado o dados py para colocar as FIFO, LIFO e também foi colocado as variações globais , para que durante o desenvolvimento do tarefas.py, ficar somente as bases das opões menu, após o termino, movemos as variações globais para o tarefa.py. mantendo o código limpo e organizado.

 Durante os testes, fui me incomandando com a tela toda bagunçada, dei a ideia de colocar algo para limpar ao final do programa , Nathan concordou, então buscamos mais informações de como realizar isso, chegando a pesquisar no youtube funções e metodos de realizar. Lá tinham varios tipos de meios de fazer, onde optamos pelo mais simples e funcional no momento, que serviria para limpar a tela no windons "os".

 Logo após termos base estruturada, tivemos alguns problemas de comunicação do que estava sendo desenvolvido a cada processo, o que era implementado ou retirado, onde Nathan deu a ideia e implementou o "CHANGELOG" com ele ficou mais organizado de enteder as alterações e o que planejaria fazer depois. Uma bela escolha para melhorar a organização.

 E durante o Desenvolvimento e teste , estava tendo problemas com calculo e saldo, mesmo excluindo e adicionando coisas para concertar, descobrimos e aprendenmos uma coisa nova sobre o Json, mesmo concertando entavam dando erro no calculo onde descobrimos que os dados ainda estavam salvos no json, então passamos a excluir e reiterar com novas informações conforme necessidade.
