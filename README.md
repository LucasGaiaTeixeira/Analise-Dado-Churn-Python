# Analise-Dado-Churn-Python
Somente uma breve analise de dados de churn.csv, com analise do dado, correção de inconsistencia, tratamento de ruidos, graficos das tebelas para analise e etc.


<h1>Insigths</h1>
* # analise de "Churn" rotatividade de clientes
* 1 : Ponto central varaivel mais importante Score tentendo a quantidade de compras que um cliente tem feito na empresa | variavel independente
* 2 : Estados Apenas da Região sul
* 3 : Clientes que não sairam muito maior do que os que sairam possivelmente indicando que estão satisfeitos com o negocio
* 4 : Clientes concentrados em RS
* 5 : Idade dos clientes bem medianas, mas alguns clientes acima da media de idades, mas bem poucos, podem ser antigos clientes, ou o negocio não tem o publico de pessoas idosas, mas entre 40 e 30 anos esta bem forte
* 6 : Existem 350 contas de usuarios que estão com valor 0 em saldos 0 de 999 contas, possivelmente estariam testando o produto do negocio na empresa e não quiseram seguir em frente
* 7 : Existem 702 clientes que possuem cartão de credito e 297 que não possue, dando a entender que existe uma alta confiabilidade desta empresa, que esse 20% possam nào querer estar com confiaça no negocio ou estão com algum tipo de receio
* 8 : baixo qualificação do negocio, com 490 não ativos e 509 ativos, podendo ser falta de atrativos para os clientes
* 9 : 4 contas com salarios anuais sendo muito altos, ou podendo ser um erro ou outra coisa


# Correção de valores errados
* Estados Contem Chaves de valores incorretas (corrigido)                       
* Genero Contem chaves com falta de padronizaçao (Corrigido)
* Idade tem um valor de -20 anos e um de 140 anos de idade (corrigido)
* pode ser que salario não tenha valor incorreto mas vou corrigir e manter no codigo os valores antigos por preucausão (corrigido)
* Existe um registro duplicado e pude consultar pelo indice (corrigido)


# Correção de dados faltantes
* Existem valores faltantes nas tabelas:  Salario e Genero (Corrigido)
