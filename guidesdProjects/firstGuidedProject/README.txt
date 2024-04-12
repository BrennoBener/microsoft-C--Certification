Preparar

Neste projeto guiado, você usará o Visual Studio Code para desenvolver um aplicativo C#.
O aplicativo usará matrizes, foreach instruções e if instruções para implementar uma lista
de parâmetros de design. Você começará criando as variáveis de matriz que contêm os dados do aplicativo.
Para concluir o projeto, você desenvolverá foreach instruções que if implementam as metas de designdo aplicativo.

Visão geral do projeto
Você está desenvolvendo um aplicativo de avaliação de alunos que automatiza o cálculo de notas para cada aluno em uma classe. Os parâmetros para a sua aplicação são:

Crie uma aplicação de consola C#.

Comece com quatro alunos. Cada aluno tem cinco notas nos exames.

Cada nota do exame é um valor inteiro, 0-100, onde 100 representa 100% de acerto.

A pontuação geral de um aluno no exame é a média das suas cinco pontuações no exame.

Critérios para atribuição de créditos adicionais:

Inclua pontuações extras de atribuição de créditos na matriz de pontuações do aluno.
As atribuições de créditos extras valem 10% da nota de um exame (ao calcular a nota numérica final).
Adicione pontuações extras de atribuição de créditos à pontuação total do exame do aluno antes de calcular a nota numérica final.
A sua candidatura tem de atribuir automaticamente notas de letra com base na pontuação final calculada para cada aluno.

Sua inscrição precisa produzir/exibir o nome de cada aluno e a nota formatada.

Seu aplicativo precisa suportar a adição de outros alunos e pontuações com impacto mínimo no código.

Você já concluiu uma versão inicial do aplicativo. O projeto de código Starter para este módulo
de projeto guiado inclui um arquivo Program.cs que fornece os seguintes recursos de código:

O código declara as variáveis usadas para definir os nomes dos alunos e as pontuações individuaisdos exames de cada aluno.
O código inclui as variáveis e algoritmos usados para somar as notas do exame e calcular a nota média do exame para cada aluno.
O código inclui uma nota de letra codificada que o desenvolvedor deve aplicar manualmente.
O código inclui instruções Console.WriteLine() para exibir o relatório de avaliação do aluno.
Seu objetivo é atualizar o código existente para incluir os seguintes recursos:

Use matrizes para armazenar nomes de alunos e pontuações de tarefas.

Use uma foreach instrução para iterar os nomes dos alunos como um loop externo do programa.

Use uma if instrução dentro do loop externo para identificar o nome do aluno atual e acessar as pontuações da tarefa desse aluno.

Use uma foreach instrução dentro do loop externo para iterar através da matriz de pontuações de atribuição e somar os valores.

Use um algoritmo atualizado dentro do loop externo para calcular a pontuação média do exame para cada aluno.

Use uma construção dentro do loop externo para avaliar a pontuação média do exame e atribuir uma if-elseif-else nota de letra automaticamente.

Integre pontuações de crédito extras ao calcular a pontuação final e a nota do aluno da seguinte forma:

Seu código deve detetar atribuições de créditos extras com base no número de elementos na matriz de pontuações do aluno.
Seu código deve aplicar o fator de ponderação de 10% às atribuições de crédito extras antes de adicionar pontuações de crédito extras à soma das pontuações do exame.
A lista a seguir mostra a nota da letra que corresponde às pontuações numéricas:

OUTPUT
97 - 100   A+
93 - 96    A
90 - 92    A-
87 - 89    B+
83 - 86    B
80 - 82    B-
77 - 79    C+
73 - 76    C
70 - 72    C-
67 - 69    D+
63 - 66    D
60 - 62    D-
0  - 59    F

O aplicativo de atualização precisa produzir um relatório de avaliação de alunos formatado que aparece da seguinte maneira:
Student         Grade

Sophia:         92.2    A-
Andrew:         89.6    B+
Emma:           85.6    B
Logan:          91.2    A-



Resumo
Seu objetivo era criar um aplicativo que usa uma combinação de iteração e instruções de seleção para processar o conteúdo de matrizes e atingir as metas de design do seu aplicativo.

Ao criar uma combinação aninhada de foreach e if declarações, você criou um aplicativo que processa o conteúdo das matrizes de nome do aluno e pontuação da atribuição para calcular e relatar as notas dos alunos. A lógica do aplicativo suporta a adição de alunos adicionais e pontuações de tarefas com atualizações mínimas de código.

Ter a capacidade de implementar instruções de iteração aninhadas que processam dados de matriz e instruções de seleção que ramificam o caminho de execução de código permite criar código mais eficiente e extensível.