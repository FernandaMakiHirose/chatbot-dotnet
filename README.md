<h1 align="center">Trabalhando com chatbots com .NET</h1>

<details open="open">
  <summary>Índice</summary>
  <ol>
    <li>
      <a href="#principais-estruturas">Executar o código</a>
    </li>
    <li>
      <a href="#principais-estruturas">Principais estruturas</a>
    </li>
    <li>
      <a href="#licença">Licença</a>
    </li>
    <li>
      <a href="#quiz">Quiz</a>
    </li>
  </ol>
</details>

## Executar o código
1. Abra o Visual Studio
2. Clique no arquivo do path `chatbot-dotnet\src\Functions\Chatbot.Functions`

## Requisitos
- Visual Studio
- Conhecimento em C# e .NET

## Principais estruturas
### DIALOG NODES
São caixas (nodes) de diálogo onde usamos as intenções e entidades identificadas na entrada do usuário, além da condição escrita, para interagir com o usuário, e por fim, fornecer uma resposta.

### $CONTEXT
São comandos que auxiliam na tomada de decisões durante a conversa, e que te salvam de algumas informações criando um contexto para serem reutilizadas posteriormente, classificando uma frase ou entrada de maneira singular. 

### TRIGGER
- É o que permite a entrada de um input em um Dialog Node, e pode ser demarcado por uma `#intenção`, uma `@entidade`, um `$contexto` ou seus !negativos. 
- `conversation_start` ou `welcome`: responsáveis por iniciar a conversa.
- `anything_else`: é para onde vai a conversa quando nenhum outro Dialog Node é capaz de compreender a frase do usuário.
- `true`: é um Dialog Node que aceita qualquer tipo de input para emitir sua resposta.

## Licença
Distribuido sob a licença MIT License. Veja `LICENSE` para mais informações.

## Quiz
### Qual o SKD necessário para a criação de um Chatbot em C#?
.NET Core.

### O que é a IBM Watson?
O Watson é uma plataforma aberta multi-cloud que permite automatizar e criar o ciclo de vida de IA, a qual pode ser utilizada para Chatbots.

### É possível utilizar banco de dados no desenvolvimento de Chatbots?
Sim, a utilização de Banco de Dados pode facilitar o armazenamento de informações e insights do negócio.

### O que são as Entidades?
É o substantivo relacionado ao desejo que foi detectado pelo chatbot. Por exemplo: Se a frase enviada pelo usuário for “gerar novo relatório”, a entidade poderia ser “relatório” ou “novo relatório”.

### Quais as principais estruturas dentro do Watson Assistant?
Dialog Nodes, Trigger e $Context.

### Como podemos fazer a base de conhecimento?
Pode ser feito manualmente, por APIs e por ferramentas como o IBM Discovery.

### Cite 3 plataformas de desenvolvimento de assistentes virtuais.
Watson Assistant, AlexaTollKit e DialogFlow.

### O que são as Intenções?
É o desejo que o chatbot perceberá que o usuário possui ao enviar uma mensagem específica. Por exemplo: ao enviar um “obrigado” a intenção do usuário é agradecer.

### O que são Functions?
São recursos que possibilitam uma computação sem servidor, provisionando infraestrutura por demanda.
