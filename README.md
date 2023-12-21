# Desafio Nextar Mobile Flutter

Boas-vindas ao desafio mobile da Nextar.

Nesta etapa queremos ver suas habilidades técnicas. Este é o momento que você terá para pensar no problema a ser resolvido e em como você irá arquitetar seu app para isso. 


## O App

Este app deverá conter uma representação de cadastro de produtos. Deve ser possível que se adicione, edite e remova itens da lista de produtos. Todos os dados devem ser salvos no Firebase. O layout é livre, dê asas a sua criatividade 🪂!

Abaixo seguem as diretrizes das telas a serem implementadas.

- Splash:
  - A sua Splash deve conter uma animação simples a sua escolha;
  - Se o usuário já tiver feito login anteriormente após a splash ele deve ser redirecionado direto pra home;

- Login:
  - Informar para o usuário de forma agradável: login e senha inválidos, campos não preenchidos e requisito de senha inválidos (mínimo 6 caracteres);
  - Após login com sucesso, persistir os dados de login localmente e navegar para a home;

- Home:
  - Exibir os cards de produtos já adicionados pelo usuário em questão;
  - Opção de filtrar por: Data, preço e ordem alfabética;
  - Ao clicar em algum card navegar para a tela de edição do mesmo;
  - Opção de adicionar um produto;
  - Opção de deltar o produto direto pelo card;

- Edição / Criação:
  - Os dados do produto são: Nome (campo de preenchimento obrigatório), preço, quantidade em estoque e código (campo de preenchimento obrigatório);
  - O botão de salvar só deve ser habilitado após o preenchimento dos campos obrigatórios;
  - Opção de deletar o produto caso seja uma edição;
  - Imagens dos produtos;


## Requisitos
- Deve ser desenvolvido em Flutter;
- O projeto deve ser publicado em um repositório no github.com, bitbucket.org ou gitlab.com e compartilhado com time da Nextar;
- README com instruções de como instalar as dependências do projeto, qual versão do Flutter utilizar e quaisquer outras instruções pertine;


## Critérios de Avaliação
Os seguintes critérios serão usados para avaliar o seu código:
- Legibilidade;
- Cuprimento do escopo;
- Organização do código (camadas bem definidas. Ex: apresentação não deve conter regras de negócio);
- Existência e quantidade de bugs e gambiarras;
- Documentação;
- Responsividade e comportamento em diversas telas;
- Arquitetura: MVC, MVVM, Clean...;
- Gestão de estado;


### Bônus
- TDD;
- Contexto e cadência dos commits;
- Paginação da lista de produtos da home;


## Dúvidas
Em caso de dúvidas entre em contato conosco pelo email: matheus.macari@nextar.com.br ou joaopedro@nextar.com.br
