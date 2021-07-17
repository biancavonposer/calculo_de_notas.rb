# calculo_de_notas.rb
Este é um programa de cálculo e exibição de respostas para notas de alunos
que a Campus Code me encorajou a fazer através do conteúdo das apostilas.

A proposição do exercício era corrigir o problema de inserir uma nota negativa
ou maior que 10 e receber uma resposta incoerente do seguinte código:

nota = 7 
case nota 
when 0 
  puts 'Você tirou zero! Precisa melhorar...' 
when 1..4 
  puts 'Reprovado... precisa se esforçar mais...' 
when 5 
  puts 'Passou raspando!' 
when 6..9 
  puts 'Parabéns, você foi aprovado.' 
else 
  puts 'Tirou 10! Você deve ser o melhor aluno que já tive!' 
end 

Além de corrigir a resposta incoerente, acrescentei a possibilidade de inserir números quebrados mesmo com o uso do while
que só trabalha com números inteiros através do método to_i no gets, que poderia ser substituído por um case.floor também.
