Projeto de código 3 - Escrever código que processa o conteúdo de uma matriz de cadeia de caracteres
Aqui estão as condições que seu terceiro projeto de codificação deve implementar:

Sua solução deve usar a seguinte matriz de cadeia de caracteres para representar a entrada para sua lógica de codificação:

string[] myStrings = new string[2] { "I like pizza. I like roast chicken. I like salad", "I like all three of the menu choices" };

Sua solução deve declarar uma variável inteira chamada periodLocation que pode ser usada para manter o local do caractere de ponto dentro de uma cadeia de caracteres.

Sua solução deve incluir um externo foreach ou for loop que possa ser usado para processar cada elemento de cadeia de caracteres na matriz. A variável string que você processará dentro dos loops deve ser nomeada myString.

No loop externo, sua solução deve usar o IndexOf()String método da classe para obter a localização do caractere do primeiro período na myString variável. A chamada de método deve ser semelhante a: myString.IndexOf("."). Se não houver nenhum caractere de ponto na cadeia de caracteres, um valor de -1 será retornado.

Sua solução deve incluir um loop interno do-while que while possa ser usado para processar a myString variável.

No loop interno, sua solução deve extrair e exibir (gravar no console) cada frase contida em cada uma das cadeias de caracteres processadas.

No loop interno, sua solução não deve exibir o caractere de período.

No loop interno, sua solução deve usar os Remove()métodos , Substring()e TrimStart() para processar as informações da cadeia de caracteres.

Comente todo o código no painel Editor de Códigos do Visual Studio

Selecione todas as linhas de código no editor de código
No menu Editar, selecione Alternar Bloquear Comentário.
Escreva o código que implementa cada condição listada para o projeto de código 3.

Execute seu aplicativo e verifique se sua saída atende aos requisitos.

Se a lógica de código funcionar corretamente, a saída deverá ser semelhante à seguinte:

I like pizza
I like roast chicken
I like salad
I like all three of the menu choices