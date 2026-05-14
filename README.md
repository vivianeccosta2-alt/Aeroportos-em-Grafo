# Aeroportos-em-Grafo
Objetivo exercitar os conceitos grafos feitos com matriz de adjacência. Programa desenvolvido para a ANAC (Agência Nacional de Aviação Civil) para facilitar a organização da malha aérea do país.

Curso de Sistemas de Informação
Estrutura e Recuperação de Dados II

Trabalho de Grafos com Matriz Esparsa

Ele tem como objetivo exercitar os conceitos grafos feitos com matriz de adjacência, 
conforme foram estudadas em sala de aula. Sua missão é desenvolver para a ANAC 
(Agência Nacional de Aviação Civil) um programa para facilitar a organização da malha 
aérea do país.
Basicamente, você vai ter que criar uma estrutura de dados para cadastrar os aeroportos 
do país e os voos feitos entre os aeroportos. Inicialmente, você vai considerar apenas os 
seguintes aeroportos: Belo Horizonte (CNF), Brasília (BSB), Rio de Janeiro (GIG), Salvador 
(SSA) e São Paulo (GRU), mas sua estrutura deverá comportar quantos aeroportos forem 
desejados.
Uma forma de cadastrar e organizar os voos é através de uma matriz de adjacência: 
basicamente, implementa-se um vetor onde se cadastram os aeroportos (vértices) e os 
vôos que os interligam (arestas).
Isso pode ser observado na figura abaixo: saindo de Belo Horizonte (CNF), existem voos 
para Salvador (SSA), Rio de janeiro (GIG) e São Paulo (GRU). Logo, a linha número 1, que 
contém os vôos que partem do Aeroporto de Confins (CNF) em Belo Horizonte (não por 
coincidência na posição 1 do vetor de aeroportos) contém o número de 3 vôoos, um na 
coluna 2 para o Rio de Janeiro (não por coincidência na posição 2 do vetor de aeroportos), 
um na coluna 3 para Guarulhos (não por coincidência na posição 3 do vetor de aeroportos) 
e um na coluna 4 para Salvador (não por coincidência na posição 4 do vetor de aeroportos).
Figura 1: Diagrama fictício de alguns voos no Brasil representados por matriz de adjacência
Nesse trabalho, você deverá implementar essa estrutura. Considere que cada elemento do 
vetor contém uma estrutura com o código do aeroporto e nome da cidade.
As seguintes operações devem ser implementadas:
1. Cadastramento de um novo aeroporto;
2. Cadastramento de um voo com um determinado número entre dois aeroportos 
identificados pelos seus códigos;
3. Remoção de um voo indicado pelo número;
4. Listagem na tela de todos os voos (número e nome da cidade destino) que saem de um 
determinado aeroporto; e
5. Listagem dos possíveis trajetos para, saindo de determinado aeroporto, atingir outro 
dado aeroporto (diretamente ou indiretamente, ou seja, passando por outros 
aeroportos).
A metriz a ser usada no projeto deverá ser uma matriz esparsa implementada conforme 
explicada em aula. Naturalmente, a implementação deverá ser genérica (admitir que se 
guarde qualquer coisa que se deseje guardar) e modular (organizada num .h e num .c)
Quanto à implementação do vetor, deve-se usar um vetor dinâmico, para poder crescer ou 
encolher se for necessário.
Você deve fazer testes de consistência se essas operações podem ser aplicadas e deve 
imprimir mensagens de sucesso ou falha.
Crie um menu que permita ao usuário realizar cada uma das operações acima. Você deverá 
fazer vários testes com o seu programa.
O trabalho pode ser feito em grupos de até 3 alunos. Para o trabalho ser considerado 
entregue, o grupo deverá apresentar seu projeto pessoalmente ao professor. TODOS os
alunos devem estar presentes nesta ocasião. O professor inquirirá os membros do grupo, 
para determinar a participação individual de cada aluno no trabalho.
Além disso tudo, cada aluno deverá manter um diário do desenvolvimento onde registra 
data, hora de inicio e hora de término de cada implementação por ele feita no projeto, além 
de uma descrição detalhada do que foi feito.
Comentários finais:
1. Comece a fazer este trabalho logo, enquanto o problema está fresco na memória e o 
prazo para terminá-lo está tão longe quanto pode estar;
2. Trabalhos copiados serão penalizados com atribuição de nota zero, tanto para quem 
copiou, como para quem viabilizou a cópia, além de acarretar a relização de prova 
escrita, conforme consta no Plano de Ensino da disciplina.
3. O trabalho deve ser entregue no dia 03/junh
