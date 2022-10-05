# ⚛️ React Native: Utilizando uma Web API

Esse é o projeto do curso **Utilizando uma Web API** da formação em **React Native** estudado pelo Fábio Mori na [Alura](https://www.alura.com.br/).

## 📱 Projeto

O AluraHub é uma aplicação feita em React Native que permite salvar um perfil com informações como nome da pessoa e uma foto, e possibilita consultar um repositório que armazena dados.

Como ele funciona? O app consome uma API externa, no caso, a API pública do Github ou uma fake API com json-server.

Esse projeto é utilizado no curso 4 da formação base de React Native da plataforma da Alura.

<h1 align="center">
    <img alt="Demonstracao" title="Demonstracao" src=".images/ficando-online-newdesign.gif" width="200px" />
</h1>


## 🧑‍💻 Palavras-chave

As tecnologias e ferramentas ensinadas pela [Alura](https://www.alura.com.br/) no projeto são:

- Expo
- React Native
- API
- CRUD
- Insomnia
- Figma
- Fetch
- Axios


## 📲 O aprendizado do aluno Fábio Mori
### Deixa eu te contar uma história

Hoje em dia vivemos uma era onde o compartilhamento de dados, sua utilização e a forma como sabemos tirar informações relevantes deles é fundamental para o desenvolvimento e crescimento de qualquer negócio. Desta forma o aprendizado de trabalhar com APIs no projeto com React Native é uma parte super importante nesta formação, já que estamos aprendendo os conceitos e formas de conectar um banco de dados com o nosso aplicativo.

### O que eu aprendi?

- API (Application Programming Interface):
	- É a parte de conecta o ciclo de informação entre os dispositivos e os servidores, da seguinte forma:
		- O dispositivo faz uma REQUISIÇÃO para a API, que PROCESSA isso em um SERVIDOR. Por sua vez, o SERVIDOR retorna um RESULTADO para a API, que finaliza o ciclo de informação enviando a RESPOSTA para o dispositivo.
	- Ela pode mudar o dia a dia da empresa, agregando simplicidade, agilidade e automação dos sistemas.
	- Pode integrar diferentes sistemas para maior eficiência na hora do uso.
	- Tem uma função estratégica na rotina das empresas, já que existem diversos sistemas e aplicativos usados em negócios, onde todos os recursos interagem com outros softwares, nas APIs.
	- Uma API possui todo um código back-end por trás.
	- Fake API é uma simulação de uma API normal, muito usada durante o desenvolvimento de uma aplicação. As rotas de requisições já são pré-definidas e ela agiliza o processo de simulação de uma aplicação, facilitando os testes iniciais da criação de um App.
	- Web API é um serviço que conecta um aplicativo a um banco de dados, permitindo fazer requisições para ler, editar e apagar informações.

- Requisições CRUD:
	- Create
	- Read
	- Update
	- Delete
	
- JSON Viewer: é uma extensão para o navegador que colore as informações do arquivo JSON.

- Insomnia: é um aplicativo para computador que permite testar Web APIs e fazer vários tipos de requisições nelas.
	- É importante para testar as requisições na Web API para ver se todas as rotas estão funcionando como deveriam.
	- Muito utilizado por DEVs para fazer requisições e ver o resultado que cada chamada da API irá retornar.
	- Verifica se uma Web API está funcionando bem.
	- Nele é possível fazer todos os tipos de requisições, incluindo o CRUD.

- Figma: é uma ferramenta para ver o design, muito utilizada durante o desenvolvimento de uma aplicação.

- Axios: é uma biblioteca externa que pode ser baixada e instalada em projetos React-Native.
	- Já trata os dados que estão sendo recebidos, convertendo automaticamente para JSON.

- Fetch: é uma interface Java Script que permite, sem precisar instalar nada externo, acessar e manipular APIs http, fazendo requisições nelas.
	- Diferentemente do Axios, há um processo de 2 etapas entre receber e entregar os dados em JSON.

- Hook ``useEffect``: deve ser utilizado quando você quer que algo aconteça toda vez que você entra na tela.
	- IMPORTANTE: quando a página anterior carrega com esse Hook, ela vai carregar apenas quando formos para ela de forma direta e não, por exemplo, através de um comando tipo ``navigation.goBack``.

- Requisições:
	- GET: para buscar informações.
	- PUT: para editar informações.
	- POST: para criar informações.
	- DELETE: para deletar informações.

### ▶️ Rodando o Projeto

Precisa ter o Node.js instalado, para verificar instalação:
```
node -v
```
Instale o json-server:
```
npm install -g json-server
```
Com a pasta do projeto no computador no terminal, digite:
```
npm install
```
Agora, digite para iniciar o projeto:
```
npm start
```
