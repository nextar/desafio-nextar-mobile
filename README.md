# Desafio Nextar Mobile

Bem-vindo ao desafio mobile da Nextar.

Nesta etapa queremos ver suas habilidades técnicas. Este é o momento que você terá para pensar no problema a ser resolvido e em como você irá arquitetar seu app para isso. 

Quais dúvidas precisamos responder nesta etapa:

- Quais as camadas necessárias?
- Como será a separação entre elas?
- MVC? MVVM? Clean Code? etc...
- Quais as bibliotecas e frameworks a serem usados?
- Como você irá gerir o estado do seu app?


E para ajudá-lo a respondê-las, é importante que você na segunda etapa com as seguintes features já desenvolvidas: 

- Tela de splash
  - A sua Splash deve conter uma animação simples a sua escolha;

- Tela de login:
  - tentativas de login com sucessso e erro, informando para o usuário de forma agradável: login e senha inválidos, campos não preenchidos e requisito de senha inválidos (mínimo 6 caracteres)
  - Após login com sucesso, navegar para uma tela apenas para clientes logados;

- Tela da timeline
  - Exibir em tempo real e ordenada as vendas recebidas por uma conexão websocket. Devem constar nessa tela todas as vendas de todas as filiais no formato de lista infinita;

- Tela de clientes
  - Exibir em tempo real todos os clientes que estão efetuando compras. Os cards devem conter o nome do cliente e o valor total das compras.
  - Ordenação por A-Z, Z-A, maior e menor valor total de compras;


Obs: As vendas devem ser recebidas a partir do nosso simulador de vendas que pode ser acessado usando docker com o seguinte comando: docker run -p 8080:8080 nextar/vendasmock. O fluxo de vendas está no endpoint /sales.  Importante: este simulador de cotações não responde ao protocolo HTTP, apenas websocket.


## Requisitos
- O projeto deve ser publicado em um repositório público no github.com, bitbucket.org ou gitlab.com e compartilhado com o time da Nextar;
- README com instruções de como instalar as dependências do projeto, de como rodar a aplicação;
- Deve ser desenvolvido em Flutter;


## Critérios de Avaliação
Os seguintes critérios serão usados para avaliar o seu código:
- Legibilidade
- Cuprimento do escopo
- Organização do código (camadas bem definidas. Ex: apresentação não deve conter regras de negócio)
- Existência e quantidade de bugs e gambiarras
- Documentação
- Responsividade e comportamento em diversas telas
- Gestão de estado (BloC, Mobx, etc.)


### Bônus
- CI/CD
- Testes unitários;
- Contexto e cadência dos commits.
- Fazer efeitos de transição na tela de introdução


## Outras informações
- Dentro das pastas assets e telas colocamos alguns prints e recursos que podem ser usados em seu projeto. Fique a vontade para seguir com as nossas sugestões... ou não :relaxed:


## Dúvidas
Em caso de dúvidas entre em contato conosco pelo nosso email: desafio@nextar.com.br
Sugestões de telas na pasta
