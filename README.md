# Ignite Pomodoro Timer

Durante o módulo "Aprofundando em Hooks" do curso de ReactJS da Rocketseat, aprendemos a desenvolver um temporizador no qual você configura o nome de um projeto ou uma tarefa em que deseja trabalhar e o tempo que deseja trabalhar nele. Ao inicializar o temporizador, é possível imterromper e começar outro projeto ou tarefa definindo uma nova duração. Indo para a aba de histórico, é possível acessar um histórico de todos os projetos e tarefas criadas e seus respectivos status (finalizado, interrompido ou em andamento).

## Aprendizados

Nesse projeto foram utilizados **styled-components**, aprendemos a criar styled components e aplicar cores definidas pelo tema proveniente do provider ThemeProvider, aprendemos a configurar tipagem de temas e aprendemos a aplicar estilos globais.

Também foi utilizado a biblioteca **react-router-dom** para criarmos páginas em diferentes rotas da nossa aplicação. Como o layout das telas não mudam muito independente da rota que o usuário acessa, foi utilizado o Outlet da biblioteca react-router-dom.

Passamos pelos conceitos de **controlled e uncontrolled components** identificando as ventagens e desvantagens de cada um dos métodos. Foi apresentado o hook **react-hook-form**, que reúne o melhor dos dois mundos, com integação com a biblioteca zod de validação de dados de formulário.

O **useEffect** foi outro hook que aprendemos durante o segundo módulo do curso de ReactJS da Rocketseat. Utilizado na funcionalidade de inicializar, decrementar e interromper o temporizador, foi mostrado as formar corretas e incorretas de se utilizar o useEffect para sempre optarmos pelo método mais performático e sempre seguindo as boas práticas.

Também foi explicado o conceito de **prop drilling** e como resolver esse problema com o **Context API**. Primeiramente, aprendemos como criar contextos para compartilhar informações entre componentes e, posteriormente, foi apresentado como compartilhar dados entre diferentes páginas e como podemos fazer a manipulação desses dados.

Por fim, foi apresentado o hook **useReducer** utilizado para manipular o estado que armazena os ciclos do temporizador. Ações como criar um novo ciclo, interromper e marcar como concluída foram definidas pelo hook tornando o código mais simples e limpo.