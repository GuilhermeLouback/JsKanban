# Js_Kanban

https://guilhermelouback.github.io/JsKanban/

O **Js_Kanban** é uma biblioteca JavaScript que permite criar quadros Kanban interativos em suas páginas da web. Com essa biblioteca, você pode gerenciar tarefas, projetos e fluxos de trabalho de forma eficiente, visualizando o progresso em diferentes etapas.

## Como Utilizar

Siga estas etapas simples para começar a usar o **Js_Kanban** em seu projeto:

1. **Incluir os arquivos necessários**

   Certifique-se de incluir os arquivos CSS e JavaScript do **Js_Kanban** em sua página HTML. Você pode fazer isso adicionando as seguintes linhas ao cabeçalho da sua página:

   ```html
   <link rel="stylesheet" href="/jkanban.min.css" />
   <link rel="stylesheet" href="/jkanban.css" />
   <script src="/jkanban.min.js"></script>
   <script src="/jkanban.js"></script>


2. **Criar um elemento HTML para o quadro Kanban**

   ```html
   <div id="myKanban"></div>
 

3. **Inicializar o quadro Kanban**

   ```html
   <script>
    var KanbanTest = new jKanban({
    element: "#myKanban",
    gutter: "10px",
    widthBoard: "450px",
    // ... (configurações adicionais)
    });
    </script>



4. **Personalização**

Personalize o quadro Kanban de acordo com o seu projeto, ajustando as opções, cores e estilos conforme necessário. Você pode adicionar mais colunas, configurar eventos de clique e muito mais.

No código fornecido, você pode ver exemplos de como adicionar tarefas, remover quadros e elementos, personalizar eventos de clique e contexto, entre outras funcionalidades. Este código de exemplo é um ponto de partida útil para explorar as capacidades do Js_Kanban em seu próprio projeto.
