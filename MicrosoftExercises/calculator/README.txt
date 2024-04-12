Visão geral do projeto
Você está desenvolvendo uma Calculadora GPA do aluno que ajudará a calcular a média geral de pontos
dos alunos. Os parâmetros para a sua aplicação são:

Você recebe o nome do aluno e as informações da turma.
Cada aula tem um nome, a nota do aluno e o número de horas de crédito para essa aula.
Seu aplicativo precisa executar operações matemáticas básicas para calcular o GPA para determinado aluno.
Seu aplicativo precisa produzir/exibir o nome do aluno, as informações da classe e o GPA.
Para calcular o GPA:

Multiplique o valor da nota de um curso pelo número de horas de crédito desse curso.
Faça isso para cada curso e, em seguida, adicione esses resultados.
Divida a soma resultante pelo número total de horas de crédito.
Você recebe a seguinte amostra de informações do curso e do GPA de um aluno:

Student: Sophia Johnson

Course          Grade   Credit Hours	
English 101         4       3
Algebra 101         3       3
Biology 101         3       4
Computer Science I  3       4
Psychology 101      4       3

Final GPA:          3.35

Configurar
Use as seguintes etapas para se preparar para os exercícios guiados do projeto:

Abra o ambiente de codificação do .NET Editor.

Copie e cole o código a seguir no Editor. Esses valores representam o nome do aluno e os detalhes do curso.

string studentName = "Sophia Johnson";
string course1Name = "English 101";
string course2Name = "Algebra 101";
string course3Name = "Biology 101";
string course4Name = "Computer Science I";
string course5Name = "Psychology 101";

int course1Credit = 3;
int course2Credit = 3;
int course3Credit = 4;
int course4Credit = 4;
int course5Credit = 3;

Analise as notas dos alunos para cada curso:

Course			    Grade		
English 101		     A
Algebra 101		     B
Biology 101		     B
Computer Science I	 B
Psychology 101	     A

Você usará essas informações para criar variáveis que armazenarão os valores numéricos de cada curso.
Lembre-se de que, para calcular o GPA de um aluno, você precisa do número total de horas de crédito e
do número total de pontos de nota obtidos. A nota obtida por um curso é igual ao produto do número de horas
de crédito para esse curso e do valor numérico da nota obtida. Por exemplo:

Course          Credit  Credit Hours    Grade Points
English 101     4		3               12

Você criará as variáveis para armazenar os valores necessários para calcular o GPA.
Você criará uma variável para armazenar a soma do total de horas de crédito para cada curso e
outra variável para armazenar a soma dos pontos de nota que o aluno ganhou em cada curso.