# fullstack-spa-challenge
Python + VueJS SPA FullStack API Challenge

### Bem-vindo(a) ao desafio FullStack SPA da KNN!
Este desafio servirá como base para verificar seu conhecimento nas tecnologias utilizadas pelo time de Desenvolvimento KNN!

#### Objetivos gerais
Desenvolver um *ToDo App*, utilizando as seguintes linguagens/frameworks:
- Frontend: (TypeScript) Vue 2 + Vuetify;
- Backend: (Python) FastAPI + Uvicorn, com banco de dados PostgreSQL e ORM SQLAlchemy.

#### Objetivos específicos
- Cada ToDo deverá conter Título (até 20 caracteres) e descrição (até 100 caracteres);
- Utilização de requisições HTTP para o Backend, com 4 endpoints: *GET TASKS, CREATE TASK, UPDATE TASK, DELETE TASK*;
- Persistência dos dados através de banco de dados relacional **PostgreSQL**;
- Utilização de duas rotas no frontend: uma para a lista de tasks, e outra para criação/edição;
- Na lista de tasks, exibir botões para edição/exclusão dos registros;
- Além do title e description, crie uma coluna no banco de dados chamada origin_ip;
- Ao enviar um POST com uma nova Task, pegue o IP de quem está criando o form através de uma API (Sugestão Ipify) e envie junto na request.
- Ao editar um ToDo, o IP não pode ser editado.

#### O quê será avaliado
- Organização das árvores de arquivos;
- Sintaxe, código limpo e de fácil compreensão;
- [Frontend] Utilização das *v-directives*;
- [Frontend] Componentização e reutilização de código;
- [Frontend] Utilização de *interfaces* para tipagem e consistência;
- [Backend] Utilização concisa de ORM para comunicação com banco de dados;
- [Backend] Respostas das requisições retornando apenas o requerido (Uso de response_models);

#### Diferenciais
- Utilização de Docker & Docker-compose com os serviços propriamente programados;
- [Frontend] Utilização de Vue Router para gerenciar as rotas;
- [Frontend] Utilização de Vuex para gerenciamento de estado;

#### Como você deve enviar
- Crie um repositório público aqui no Github;
- Marque o user <a target="_blank" href="https://github.com/augustokemp">@augustokemp</a> na descrição, ou adicione-o ao repositório.

#### Considerações finais
- **Mais funcional, menos visual**: neste momento, não foque tanto em deixar o visual bonito. Faça a aplicação funcionar. Mas, se você é um artista, por favor, capriche!! 😊
- **Não precisa ficar perfeito**: nós entendemos, é um teste que demanda um bom tempo... Por isso, faça o quê conseguir!
- Na KNN, utilizamos o Vue com um *@Decorator* que facilita muito o desenvolvimento, <a target="_blank" href="https://class-component.vuejs.org/">seria legal se você o utilizasse!</a>

#### Boa sorte!
