Especificação do projeto
O projeto de código Starter para este módulo inclui um arquivo Program.cs com os seguintes recursos de código:

O código declara variáveis usadas para coletar e processar dados de animais de estimação e seleções de itens de menu

O código declara a matriz ourAnimals que inclui as seguintes informações para cada animal na matriz:

ID do animal de estimação #.
Espécies de animais de companhia (gato ou cão).
Idade do animal de estimação (anos).
Uma descrição da aparência física do animal de estimação.
Uma descrição da personalidade do animal de estimação.
O apelido do animal de estimação.
O código usa um loop for em torno de uma construção switch-case para preencher elementos da matriz ourAnimals.

O código inclui um loop em torno de um menu principal que termina quando o usuário insere "exit". O menu principal inclui:

Liste todas as nossas informações atuais sobre animais de estimação.
Atribua valores aos campos da matriz ourAnimals.
Certifique-se de que as idades dos animais e as descrições físicas estão completas.
Certifique-se de que os apelidos dos animais e as descrições de personalidade estão completos.
Editar a idade de um animal.
Edite a descrição da personalidade de um animal.
Exiba todos os gatos com uma característica especificada.
Exiba todos os cães com uma característica especificada.
Entre na seleção de itens de menu ou digite "Sair" para sair do programa

O código lê a seleção de item de menu do usuário e usa uma instrução switch para ramificar o código para cada número de item de menu.

O código inclui implementação para as opções de menu 1 e 2.

O código exibe uma mensagem "em construção" para as opções de menu 3-8.

Seu objetivo neste desafio é criar os recursos do aplicativo alinhados com as opções de menu 3 e 4.

 Nota

Novos animais devem ser adicionados à matriz ourAnimals quando chegarem. No entanto, a idade de um animal e algumas características físicas de um animal de estimação podem ser desconhecidas até depois do exame de um veterinário. Além disso, o apelido e a personalidade de um animal podem ser desconhecidos quando um animal de estimação chega pela primeira vez. Os novos recursos que você está desenvolvendo garantirão a existência de um conjunto de dados completo para cada animal na matriz ourAnimals.

Para garantir que as idades dos animais e as descrições físicas estejam completas, o seu código deve:

Atribua um valor numérico válido a petAge para qualquer animal que tenha recebido dados na matriz ourAnimals, mas não tenha recebido uma idade.
Atribua uma cadeia de caracteres válida a petPhysicalDescription para qualquer animal que tenha recebido dados na matriz ourAnimals, mas não tenha recebido uma descrição física.
Verifique se as descrições físicas têm um valor atribuído. Os valores atribuídos não podem ter zero caracteres. Qualquer requisito adicional depende de si.
Para garantir que os apelidos de animais e as descrições de personalidade estejam completos, seu código deve:

Atribua uma cadeia de caracteres válida a petNickname para qualquer animal que tenha recebido dados na matriz ourAnimals, mas não tenha recebido um apelido.
Atribua uma cadeia de caracteres válida a petPersonalityDescription para qualquer animal que tenha recebido dados na matriz ourAnimals, mas não tenha recebido uma descrição de personalidade.
Verifique se os apelidos e as descrições de personalidade têm um valor atribuído. Os valores atribuídos não podem ter zero caracteres. Qualquer requisito adicional depende de si.
Configurar
Use as seguintes etapas para se preparar para os exercícios do projeto Desafio:

Para baixar um arquivo zip contendo o código do projeto Starter, selecione o seguinte link: Arquivos de laboratório.

Descompacte os arquivos de download.

Descompacte os arquivos em seu ambiente de desenvolvimento. Considere usar seu PC como seu ambiente de desenvolvimento para que você tenha acesso ao seu código depois de concluir este módulo. Se você não estiver usando seu PC como seu ambiente de desenvolvimento, poderá descompactar os arquivos em uma área restrita ou ambiente hospedado.

Na sua máquina local, navegue até a pasta de downloads.
Clique com o botão direito do mouse em Challenge-project-branching-looping-CSharp.main.zip e selecione Extrair tudo.
Selecione Mostrar arquivos extraídos quando concluído e, em seguida, selecione Extrair.
Anote o local da pasta extraída.
Copie a pasta ChallengeProject extraída para a pasta da área de trabalho do Windows.
Abra a nova pasta ChallengeProject no Visual Studio Code.

Abra o Visual Studio Code em seu ambiente de desenvolvimento.

No Visual Studio Code, no menu Arquivo , selecione Abrir pasta.

Navegue até a pasta Windows Desktop e localize a pasta "ChallengeProject".

Selecione ChallengeProject e, em seguida, selecione Select Folder.

O modo de exibição Visual Studio Code EXPLORER deve mostrar a pasta ChallengeProject e duas subpastas chamadas Final e Starter.

Agora você está pronto para começar os exercícios do projeto Desafio. Boa sorte!