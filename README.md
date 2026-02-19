SOFTWARE DE GESTÃO DA PRODUTIVIDADE INDUSTRIAL: Implementação de automação com Arduino

O arquivo "Gestao_Produtividade_Industrial.sln" de Solução do Projeto, abre toda estrutura visual/código fonte/classes no VS;
A pasta "Gestao_Produtividade_Industrial" contém os arquivos completos do Projeto C#, para abrir na Solution Explorer do VS;
A pasta "Gestao_Maquina_Arduino" contém o Projeto de código fonte, do Arduíno IDE (.ino);
A pasta "MachineSensorControl" contém os arquivos para troca de dados entre os sistemas (script aspx e json). Diretório padrão: "C:\MachineSensorControl" para criar o Site no IIS;
A Porta padrão definida no código fonte Arduíno é a 80 (HTTP). Essa porta precisa estar no Web server do Site IIS. Outras portas precisa ser liberado no Firewall Windows.

🏭 SOFTWARE DE GESTÃO DA PRODUTIVIDADE INDUSTRIAL
Implementação de Automação com Arduino

Sistema desenvolvido para monitoramento e controle da produtividade industrial por meio da integração entre um software em C# (.NET) e um microcontrolador Arduino, permitindo a coleta e visualização de dados em tempo real.

📌 Objetivo do Projeto

Desenvolver um software capaz de:

📊 Monitorar contagem de peças em tempo real

⚙️ Simular velocidade de esteira

🔄 Integrar dados entre Arduino e aplicação desktop

📈 Exibir informações estatísticas e gráficos de produtividade

🖥️ Automatizar processos industriais

🛠️ Tecnologias Utilizadas

💻 C# (.NET Framework)

🔌 Arduino (C++ - IDE Arduino)

🌐 ASP.NET (ASPX)

📄 JSON

🖥️ IIS (Internet Information Services)

🔥 Windows Firewall

📦 Projeto
 ┣ 📂 Gestao_Produtividade_Industrial
 ┃ ┗ Arquivos completos do projeto C#
 ┣ 📂 Gestao_Maquina_Arduino
 ┃ ┗ Código fonte Arduino (.ino)
 ┣ 📂 MachineSensorControl
 ┃ ┗ Scripts ASPX + JSON para troca de dados
 ┗ 📄 Gestao_Produtividade_Industrial.sln


 📁 Descrição das Pastas
🔹 Gestao_Produtividade_Industrial.sln

Arquivo de solução do projeto.
Abra este arquivo no Visual Studio para carregar toda a estrutura do sistema (Forms, Classes, Controllers, etc.).

🔹 Gestao_Produtividade_Industrial

Contém todos os arquivos do projeto C#.
Pode ser aberto diretamente pela Solution Explorer do Visual Studio.

🔹 Gestao_Maquina_Arduino

Projeto do Arduino contendo o código fonte .ino responsável por:

Leitura de sensores

Contagem de peças

Comunicação HTTP com o servidor

🔹 MachineSensorControl

Responsável pela troca de dados entre Arduino e aplicação C#.

Contém:

Script ASPX

Arquivos JSON

📍 Diretório padrão para publicação no IIS:
C:\MachineSensorControl

