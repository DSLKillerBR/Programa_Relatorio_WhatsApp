# Programa_Relatorio_Telegram


O intuito desse programa é eu reunir o útil ao agradável. Eu queria praticar minha programação, mas estava querendo criar um programa próprio. Como eu tinha um certo trabalho para estar colocando todas as negociações que eu fazia nas corretoras de Criptomoedas, resolvi criar esse programa que facilitará muito a minha vida. 
Ele pede alguns dados como a data da negociação, o preço de compra e venda da moeda, a quantidade negociada (minha quantidade vendida é sempre a mesma comprada. Futuramente planejo adicionar uma vertente que muda o programa caso a quantidade vendida e comprada sejam diferentes) e o lucro obtido antes desta negociação que está sendo adicionada ao programa. 
Planejo adicionar alavancagem no programa, porém não sei se irei adicionar, pois para conseguir saber a alavancagem, teria que solicitar alguns dados para o usuário, já que as corretoras não mostram a alavancagem, e estou tentando fazer esse programa solicitar a menor quantidade de dados possível.
Ele gera para o usuário, um arquivo contendo as informações adicionadas no programa, junto com a porcentagem de lucro do trade, o valor total utilizado para compras as moedas, o valor total recebido ao vendê-las e o lucro total, sendo essas quatro calculadas pelo próprio programa. 
Neste arquivo, denominado "mensagem.txt", os dados são impressos de uma forma que, ao copiar o texto presente no arquivo e colar no Telegram, ficará em negrito as idicações dos dados. Ex.: "**Data da negociação:**" (o Telegram irá ler "Data da negociação" porém em negrito). \n
Ainda possuo alguns planos ambiciosos para esse programa, como adicionar um banco de dados para não ficar dependente do arquivo para salvar os dados dos trades, criar uma interface bacana para o usuário e tentar criar esse programa em outras linguagens de programação, para treinar e aprofundar meus conhecimentos.
O programa seria usado para colocar os relatórios no WhatsApp porém, por limitação do mesmo, irei utilizar o Telegram.
O programa também pode ser utilizado para gerar relatórios de negociações de ações, pois o processo seria muito semenlhante.
Planejo, futuramente, criar uma variação para as negociações de ações também. Acho que vou criar a variação dentro do arquivo main.c ao invés de criar um outro arquivo separado para as negociações de ações.
