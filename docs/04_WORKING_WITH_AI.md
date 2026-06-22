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

## Código gerado não é automaticamente software pronto

A IA pode produzir código que compila, abre uma tela ou passa em uma demonstração simples.

Isso não significa que o software esteja pronto.

Ainda é necessário verificar:

- se funcionalidades antigas continuam funcionando;
- se há testes ou critérios de aceite claros;
- se dados sensíveis estão protegidos;
- se credenciais não foram expostas;
- se a solução funciona com dados reais, não apenas exemplos pequenos;
- se existe risco de concorrência, duplicidade ou inconsistência;
- se a arquitetura continua compreensível;
- se a manutenção futura será possível.

A IA pode acelerar a implementação.

Mas aceitar a mudança continua sendo uma decisão humana.

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
- não registrar handoff;
- confundir código que funciona uma vez com software validado;
- ignorar segurança, privacidade e dados sensíveis;
- colocar em produção algo que não foi entendido.

## Regra principal

```txt
A IA acelera.
Mas quem dirige é a pessoa.
```

E, quando o assunto é software real:

```txt
A IA pode escrever código.
Mas software ainda exige engenharia.
```
