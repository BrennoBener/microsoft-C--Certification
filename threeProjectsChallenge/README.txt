Neste desafio, ser-lhe-ão apresentadas condições para três projetos de codificação separados. Cada projeto exigirá que você implemente um bloco de código de iteração usando uma instrução ou uma do-whilewhile . Você precisará avaliar as condições especificadas para escolher entre as do-while instruções e while . Você pode mudar depois de começar se sua primeira escolha não estiver funcionando tão bem quanto você esperava.
Gerencie a entrada do usuário durante este desafio
Ao usar uma instrução para obter a entrada do usuário, é prática comum usar uma Console.ReadLine() cadeia de caracteres de tipo anulável (designada string?) para a variável de entrada e, em seguida, avaliar o valor inserido pelo usuário. O exemplo de código a seguir usa uma cadeia de caracteres de tipo anulável para capturar a entrada do usuário. A iteração continua enquanto o valor fornecido pelo usuário é nulo:

string? readResult;
Console.WriteLine("Enter a string:");
do
{
    readResult = Console.ReadLine();
} while (readResult == null);

A expressão booleana avaliada pela instrução pode ser usada para garantir que a entrada do usuário atenda a while um requisito especificado. Por exemplo, se um prompt solicitar que o usuário insira uma cadeia de caracteres que inclua pelo menos três caracteres, o seguinte código poderá ser usado:

string? readResult;
bool validEntry = false;
Console.WriteLine("Enter a string containing at least three characters:");
do
{
    readResult = Console.ReadLine();
    if (readResult != null)
    {
        if (readResult.Length >= 3)
        {
            validEntry = true;
        }
        else
        {
            Console.WriteLine("Your input is invalid, please try again.");
        }
    }
} while (validEntry == false);



Se você quiser usar Console.ReadLine() a entrada para valores numéricos, precisará converter o valor da cadeia de caracteres em um tipo numérico.

O int.TryParse() método pode ser usado para converter um valor de cadeia de caracteres em um inteiro. O método usa dois parâmetros, uma cadeia de caracteres que será avaliada e o nome de uma variável inteira à qual será atribuído um valor. O método retorna um valor booleano. O exemplo de código a seguir demonstra usando o int.TryParse() método:

// capture user input in a string variable named readResult

int numericValue = 0;
bool validNumber = false;

validNumber = int.TryParse(readResult, out numericValue);

Se o valor da cadeia de caracteres atribuído a readResult representar um inteiro válido, o valor será atribuído à variável inteira denominada , e true será atribuído à variável booleana denominada numericValuevalidNumber. Se o valor atribuído a readResult não representar um número inteiro válido, validNumber será atribuído um valor de false. Por exemplo, se readResult for igual a "7", o valor 7 será atribuído a numericValue.