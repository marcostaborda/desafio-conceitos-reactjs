## :rocket: Sobre o desafio

Nesse desafio, desenvolvi uma aplicação que irá armazenar repositórios de um portfólio comunicando-se com o que foi desenvolvido no [back-end](https://github.com/marcostaborda/desafio-conceitos-nodejs) utilizando o Node.js.

###  Comandos necessários para:

- Instalar as dependência `yarn`.
- Executar os testes `yarn test`.
- Rodar a aplicação no navegador `yarn start`.

### Requisitos: 

- Manter o [back-end](https://github.com/marcostaborda/desafio-conceitos-nodejs) rodando.

### Funcionalidades da aplicação

- **`Listar os repositórios API`**: Criação de uma lista com o campo **title** de todos os repositórios que estão cadastrados na API.

- **`Adicionar um repositório API`**: Adiciona um novo item na API através de um botão com o texto **Adicionar** e, após a criação,  exibi o nome dele na listagem após o cadastro.

- **`Remover um repositório API`**: Cada item da lista, possui um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do frontend e da API.

### Específicação dos testes

Para esse desafio tem os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, a aplicação deve permitir que um repositório seja adicionado ao backend e listado no frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, a aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem e da API.

## :memo: Licença

Esse projeto está sob a licença MIT.

---

Criação do teste 💜 by Rocketseat :wave: [Entre na nossa comunidade!](https://discordapp.com/invite/gCRAFhc)

Desenvolvido por Marcos Taborda
