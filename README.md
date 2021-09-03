# Trabalhando com chatbots com .NET
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
