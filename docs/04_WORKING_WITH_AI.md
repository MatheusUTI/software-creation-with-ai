# 04 — Trabalhando com IA

Trabalhar com IA para criar software não é apenas escrever prompts.

É conduzir um processo.

## O papel da IA

A IA pode ajudar em várias etapas:

- transformar ideias em especificações;
- revisar regras;
- sugerir arquitetura;
- gerar código;
- explicar erros;
- propor testes;
- revisar documentação;
- organizar próximos passos.

Mas a IA precisa de direção.

## O papel humano

A pessoa continua responsável por:

- entender o problema;
- decidir prioridades;
- validar o resultado;
- reconhecer quando a IA inventou algo;
- testar na prática;
- aceitar ou rejeitar mudanças;
- manter o projeto útil.

## Como pedir melhor

Um pedido ruim:

```txt
Crie um app de controle de tarefas.
```

Um pedido melhor:

```txt
Crie a primeira versão de um app de controle de tarefas domésticas.
Apenas cadastro, listagem e conclusão de tarefas.
Não implemente notificações ainda.
Use armazenamento local.
Inclua critérios de aceite.
```

## Como reduzir alucinação

Sempre separe:

- fatos;
- hipóteses;
- desconhecidos;
- riscos.

Exemplo:

```txt
FACTS: O app já possui cadastro de tarefas.
ASSUMPTIONS: A conclusão deve enviar a tarefa para histórico.
UNKNOWNS: Ainda não sabemos se tarefas excluídas devem aparecer no histórico.
RISKS: Alterar o modelo pode quebrar dados já salvos.
```

## Uma tarefa por ciclo

A IA tende a errar mais quando recebe tarefas amplas demais.

Prefira ciclos pequenos:

```txt
Corrigir restauração de tarefas arquivadas.
```

Em vez de:

```txt
Melhore todo o sistema de tarefas, histórico, notificações e recorrência.
```

## Documentar antes de continuar

Depois de cada ciclo, registre:

- o que foi feito;
- arquivos alterados;
- riscos;
- testes realizados;
- o que falta;
- próxima tarefa.

Isso permite continuar em outra sessão sem explicar tudo novamente.

## Como saber se está funcionando

Um bom sinal é quando os prompts ficam menores.

Exemplo de evolução:

```txt
Antes:
Prompt enorme explicando todo o projeto.

Depois:
Leia START_HERE.md.
Objetivo: CR13.
```

Isso significa que a documentação está carregando contexto.

## Erros comuns

- pedir sistemas inteiros de uma vez;
- aceitar código sem testar;
- deixar decisões apenas no chat;
- permitir que a IA invente regras;
- trocar stack sem motivo claro;
- refatorar tudo quando só precisava corrigir uma parte;
- não registrar handoff.

## Regra principal

```txt
A IA acelera.
Mas quem dirige é a pessoa.
```
