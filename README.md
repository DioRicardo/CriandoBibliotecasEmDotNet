[ESTUDOS] - Projeto para estudos. Acompanhando o curso C# - criando bibliotecas em .NET, da plataforma Alura.

Pontos aprendidos durante o curso:

- Criar um projeto do tipo biblioteca de classes, que poderá ser utilizado em outras soluções;

- Referenciar um outro projeto dentro da solução no Visual Studio 2022, o que possibilita uma mesma solução conter vários projetos;

- Utilizar bibliotecas criadas por terceiros e adicioná-las e configurá-las ao nosso projeto usando os recursos do gerenciador de pacotes Nuget;

- Usar a biblioteca JsonConvert, do pacote NewtonSoft.Json, para fazermos a serialização de objetos no formato Json como uma nova funcionalidade do projeto;

- Utilizar a biblioteca System.Xml.Serialization, do .Net, para fazer a serialização de objetos no formato Xml como uma nova funcionalidade do projeto (Desafio concluído como exercício de fixação, sem passo-a-passo, através de pesquisas online nas documentações oficiais).

- Utilizar o nível de visibilidade internal para encapsular uma classe para que ela possa ser utilizada somente no contexto da biblioteca;

- Implementar uma melhoria na nossa biblioteca para facilitar a manutenção da lógica de validação de senha do sistema interno do ByteBank;

- Aplicar a combinação da visibilidade protected internal, que vai permitir acessar um membro na própria biblioteca e nas classes derivadas em outro projeto.

