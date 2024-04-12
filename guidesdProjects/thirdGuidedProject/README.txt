A especificação do projeto
Para os novos recursos do aplicativo Contoso Pets, a especificação de design fornece detalhes para a pesquisa de cães e recursos de doação sugeridos:

Pesquisa de atributos do cão

Coletar informações para o termo de pesquisa de características do animal de estimação
Percorra a matriz de animais e identifique "cães"
Para cada cão, combine as descrições físicas e de personalidade para pesquisar
Pesquisar na descrição combinada a correspondência do termo de entrada
Saída dos cães que têm uma correspondência de termo
Dados de doação sugeridos

Definir suggestedDonation string
Expanda a ourAnimals matriz para conter suggestedDonation e preencher dados de exemplo para suggestedDonation
Garantir todo o uso de contas de ourAnimals matriz para os dados adicionados suggestedDonation
Produção suggestedDonation com símbolo de moeda regional ($, €, ¥,... )
Visão geral do código inicial
O desenvolvimento inicial do código inicial está concluído.

O projeto Starter para este módulo de projeto guiado inclui um arquivo Program.cs que fornece os seguintes recursos de código:

O código declara variáveis usadas para coletar e processar dados PET e seleções de itens de menu

o código declara a matriz ourAnimals

o código usa um loop for em torno de uma if--else ifelse construção para preencher a matriz ourAnimals com um conjunto de dados de exemplo

O código exibe as seguintes opções do menu principal para a seleção do usuário:

1. List all of our current pet information
2. Display all dogs with a specified characteristic

Enter menu item selection or type "Exit" to exit the program

O código lê a seleção de itens de menu do usuário e exibe uma mensagem ecoando sua seleção

apenas seleção "1. Liste todas as nossas funções atuais de informações sobre animais de estimação usando o código inicial

Seu objetivo é atualizar o código existente para desenvolver os recursos do aplicativo descritos anteriormente. As principais características:

Adicionar pesquisa de atributos de cão
Incluir dados de doação sugeridos
Você usa o Visual Studio Code como seu ambiente de desenvolvimento e testa seu aplicativo em cada estágio do processo de desenvolvimento.

Configurar
Use as etapas a seguir para se preparar para os exercícios guiados do projeto.

Faça o download de um arquivo zip contendo as pastas de código para o projeto guiado.

Em um navegador, navegue até Guided-project-Work-with-variable-data-in-CSharp.zip para baixar o arquivo zip.
Descompacte os arquivos baixados localmente (ou na área restrita se você não estiver usando um ambiente de desenvolvimento local)

Na sua máquina local, navegue até a pasta de downloads.
Clique com o botão direito do rato no ficheiro Guided-project-Develop-conditional-branching-and-looping-structures-in-CSharp.zip e, em seguida, selecione Extrair tudo.
Use o botão Procurar para especificar a pasta da Área de Trabalho do Windows como o local de extração e selecione Selecionar pasta.
Selecione Mostrar arquivos extraídos quando concluído e, em seguida, selecione Extrair.
Anote o local da pasta extraída.
Abra a pasta extraída Guided-project-Work-with-variable-data-in-CSharp-main no Visual Studio Code

Abra o Visual Studio Code localmente (ou abra a área restrita do MS Learn e abra o Visual Studio Code se não estiver usando um ambiente de desenvolvimento local)

No Visual Studio Code, no menu Arquivo , selecione Abrir pasta

Navegue até a pasta que contém seus arquivos extraídos, expanda a estrutura de pastas para localizar a pasta chamada "GuidedProject".

Selecione Guided-project-Work-with-variable-data-in-CSharp-main e, em seguida, selecione Select Folder

O modo de exibição Visual Studio Code EXPLORER deve mostrar duas subpastas chamadas Final e Starter.
Agora você está pronto para começar os exercícios do projeto Guiado. Boa sorte!