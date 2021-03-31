## Criar novo Projeto

`dotnet new console -n DIO.bank`

###### Para abrir o Projeto no VS Code

digite no prompt o comando: `code DIO.Bank`

O VS code irá exibir uma mensagem no canto inferior esquerdo da tela pedindo para confirmar se é um projeto C#, clique em YES e automaticamente será criada a pasta .vscode com os arquivos launch.json e tasks.json

Se desejar que ao executar o Run a aplicação rode em um terminal externo ao VS Code insira o seguinte código no arquivo launch.json nas últimas linhas de comando das configurations do arquivo 

altere: `"console": "internalConsole"` para `"console": "externalTerminal",`
insira: `"internalConsoleOptions": "openOnSessionStart"`

Para facilitar a implementação das classes em C#, caso não tenha adicionado, adicione no VS Code as extensões C# for Visual Studio Code e C# Extensions

Na aba Explorer do VS Code onde está as pastas do projeto clique sobre a pasta DIO.Bank e clique em criar nova pasta e coloque o nome de Classes Em seguida clique na pasta Classes com o botão direito e selecione criar nova classe C# e dê a essa classe o nome de Conta.cs

No arquivo Conta.cs para estruturação desse projeto na 1ª linha de código namespace, deixe a linha apenas com o código namespace DIO.bank

Na aba Explorer do VS Code onde está as pastas do projeto clique sobre a pasta DIO.Bank e clique em criar nova pasta e coloque o nome de Enums Em seguida clique na pasta Enums com o botão direito e selecione criar novo arquivo e dê a essa arquivo o nome de TipoConta.cs
