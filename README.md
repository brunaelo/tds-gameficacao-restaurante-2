<h1>Sistema de Gerenciamento de Pedidos de Restaurante</h1>

Esta é a atividade 2 de gamificação que foi feita na disciplina de Tecnologia em Desenvolvimento de Sistemas da Universidade Tecnológica Federal do Paraná. Ela consiste em ter um projeto implementado na atividade 1 de gamificação, agora fazendo uso de dois projetos: um para a camada de apresentação, por meio do RAZOR PAGES, e outro com REST API.
<br>
Grupo: Bruna Eloisa Schvingel Tomaz, Isabella Gon e Lissa Takahashi.
<h2>Classes básicas:</h2>

* Mesa: representa as mesas do restaurante. Contém atributos como número da mesa e status da mesa (ocupada, livre), hora de abertura em caso de estar ocupada.
* Garçon: representa os garçons do restaurante. Contém atributos como nome, sobrenome, número de identificação e número de telefone.
* Categoria: representa as categorias de produtos disponíveis no restaurante. Contém atributos como nome e descrição.
* Produto: representa os produtos disponíveis no restaurante. Contém atributos como nome, descrição, preço e categoria.
* Atendimento: representa o atendimento de uma mesa por um garçon em um determinado momento. Contém atributos como a mesa atendida, o garçon responsável o horário do pedido e os produtos solicitados.

Associações: Um garçon pode atender várias mesas, registrando os produtos pedidos em cada atendimento. Uma mesa pode ser atendida por vários garçons.  Um produto pertence a uma categoria.

<h2>Instruções de como executar a aplicação</h2>

* Clone o repositório e abra ele no Visual Studio Code;
* Acesse ProjetoGerenciamentoRestaurante.API;
* Clique com o botão direito no arquivo Program.cs;
* Clique em "Open in Integrated Terminal";
* Digite "dotnet watch run" no terminal;
* Acesse ProjetoGerenciamentoRestaurante.RazorPages;
* Clique com o botão direito no arquivo Program.cs;
* Clique em "Open in Integrated Terminal";
* Digite "dotnet watch run" no terminal.