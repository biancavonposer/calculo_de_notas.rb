# calculo_de_notas.rb
Este é um programa de cálculo e exibição de respostas para notas de alunos que a Campus Code me encorajou a fazer através do conteúdo das apostilas.

A proposição do exercício era corrigir o problema de inserir uma nota negativa ou maior que 10 e receber uma resposta incoerente de um código baseado apenas na variável nota, no case e no while.

Para o programa servir como calculadora de qualquer nota, substituí a nota fixa estabelecida no primeiro código por um gets.to_i. Assim, além de corrigir a resposta incoerente, acrescentei a possibilidade de inserir números quebrados mesmo com o uso do while, que só trabalha com números inteiros, através do método to_i no gets, que poderia ser substituído por um case.floor também, caso eu não quisesse usar um gets e só trabalhar com a variável nota com um valor pré estabelecido.


