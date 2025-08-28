# Costs - Gerenciador de Projetos 💰

Aplicação web desenvolvida em React para o gerenciamento de orçamentos de projetos. Crie projetos, defina um orçamento e adicione serviços, controlando os custos de forma simples e eficaz.

![Página inicial do projeto Costs](https://user-images.githubusercontent.com/103129996/165330718-d9b18c6d-514b-42e6-a1d8-c1f92f3b3c94.png)

## ✨ Funcionalidades

* **Criar Projetos:** Cadastre novos projetos com nome, orçamento total e categoria.
* **Listar e Visualizar:** Veja todos os seus projetos em um layout de cards.
* **Editar e Excluir:** Gerencie seus projetos, podendo atualizá-los ou removê-los.
* **Adicionar Serviços:** Dentro de um projeto, adicione serviços com nome, custo e descrição.
* **Controle de Orçamento:** O sistema valida se o custo de um novo serviço não ultrapassa o orçamento restante do projeto.
* **Layout Responsivo:** Interface adaptável para diferentes tamanhos de tela.

## 🛠️ Tecnologias Utilizadas

* **[ReactJS](https://reactjs.org/)**: Biblioteca para construção da interface de usuário.
* **[React Router Dom](https://reactrouter.com/)**: Para gerenciamento das rotas da aplicação.
* **[React Hooks](https://reactjs.org/docs/hooks-intro.html)**: (`useState`, `useEffect`) para gerenciamento de estado e ciclo de vida dos componentes.
* **[JSON Server](https://github.com/typicode/json-server)**: Para simular uma API RESTful completa para o frontend.
* **CSS Modules**: Para estilização dos componentes de forma escopada.

## 🚀 Como Executar o Projeto Localmente

Para rodar este projeto, você precisará ter o [Node.js](https://nodejs.org/en/) e o [Git](https://git-scm.com/) instalados em sua máquina.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/EdsonAkaves/projeto-costs-reactjs
    ```

2.  **Acesse o diretório do projeto:**
    ```bash
    cd nome-do-repositorio
    ```

3.  **Instale as dependências do projeto:**
    ```bash
    npm install
    ```

4.  **Inicie a API com o JSON Server:**
    *O projeto utiliza o `json-server` para simular o backend. Execute o comando abaixo em um terminal para iniciar o servidor na porta 5000.*
    ```bash
    npm run backend
    ```
    *(**Observação:** Você talvez precise adicionar o script `"backend": "json-server --watch db.json --port 5000"` ao seu arquivo `package.json`)*

5.  **Inicie a aplicação React:**
    *Em outro terminal, execute o comando para iniciar o servidor de desenvolvimento do React.*
    ```bash
    npm start
    ```

6.  Abra seu navegador e acesse `http://localhost:3000` para ver a aplicação.

## 🖼️ Screenshots

| Página de Projetos | Criando um Novo Projeto |
| :---: | :---: |
| ![Página de listagem de projetos](https://user-images.githubusercontent.com/103129996/165331296-ac355ad7-2153-4dd4-bd3b-17d76c6777fe.png) | ![Página de criação de um novo projeto](https://user-images.githubusercontent.com/103129996/165330904-72d201d5-5336-467a-8ad3-8255dd327890.png) |

| Detalhes do Projeto | Adicionando um Serviço |
| :---: | :---: |
| ![Página de detalhes de um projeto](https://user-images.githubusercontent.com/103129996/165331038-0fb41c5f-242f-4d54-b726-00d2402ff00d.png) | ![Formulário para adicionar um novo serviço](https://user-images.githubusercontent.com/103129996/165331168-00c8ee61-4166-46b8-aa8d-5656194213a5.png) |
