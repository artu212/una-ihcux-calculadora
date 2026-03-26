# una-ihcux-calculadora
Microsoft Windows [versão 10.0.19045.6466]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\arthu>dotnet new console -n Calculadora -f net8.0
Erro: Opções inválidas:
-f net8.0
   'net8.0' não é um valor válido para '-f'. Os valores possíveis são:
      net10.0   - Net10.0 de destino

Para obter mais informações, execute:
   dotnet new console -h

Para obter detalhes sobre o código de saída, consulte https://aka.ms/templating-exit-codes#127

C:\Users\arthu>dotnet new console
O modelo "Aplicativo do Console" foi criado com êxito.

Processando ações pós-criação...
Restaurando C:\Users\arthu\arthu.csproj:
A restauração foi bem-sucedida.



C:\Users\arthu>dotnet new console -n Calculadora -f net8.0 cd calculadora
Erro: Opções inválidas:
cd
   'cd' não é uma opção válida.
calculadora
   'calculadora' não é uma opção válida.
-f net8.0
   'net8.0' não é um valor válido para '-f'. Os valores possíveis são:
      net10.0   - Net10.0 de destino

Para obter mais informações, execute:
   dotnet new console -h

Para obter detalhes sobre o código de saída, consulte https://aka.ms/templating-exit-codes#127

C:\Users\arthu>cd calculadora

C:\Users\arthu\Calculadora>git init
Reinitialized existing Git repository in C:/Users/arthu/Calculadora/.git/

C:\Users\arthu\Calculadora>git add .

C:\Users\arthu\Calculadora>git commit -m "Projeto Calculadora"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'arthu@DESKTOP-9RIAGDS.(none)')

C:\Users\arthu\Calculadora>
