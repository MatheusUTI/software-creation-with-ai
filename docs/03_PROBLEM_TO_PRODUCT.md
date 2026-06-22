# 03 — Do Problema ao Produto

Criar software com IA não começa pedindo código.

Começa entendendo o problema.

## Fluxo básico

```txt
Problema real
↓
Contexto
↓
Usuários
↓
Regras
↓
Exemplos
↓
MVP
↓
Especificação
↓
Implementação com IA
↓
Validação
↓
Evolução
```

## 1. Problema real

Descreva a dor antes de pensar na solução.

Perguntas úteis:

- O que está difícil hoje?
- Quem sofre com isso?
- Com que frequência acontece?
- Quanto tempo ou esforço isso consome?
- O que acontece quando dá errado?

## 2. Contexto

Explique o ambiente onde o problema acontece.

Exemplos:

- operação logística;
- rotina doméstica;
- controle financeiro;
- expedição;
- atendimento;
- estoque;
- agenda;
- relatórios.

Sem contexto, a IA tende a criar soluções genéricas.

## 3. Usuários

Defina quem vai usar.

Não precisa ser complexo.

Exemplo:

```txt
Usuário principal: supervisor operacional.
Usuário secundário: auxiliar de expedição.
Usuário indireto: motorista.
```

## 4. Regras

Regras são mais importantes do que telas bonitas.

Exemplos:

- quando algo pode ser concluído;
- quais campos são obrigatórios;
- quais exceções existem;
- o que não pode ser alterado;
- quando um status muda;
- o que deve ficar no histórico.

## 5. Exemplos reais

A IA entende melhor com exemplos concretos.

Em vez de dizer:

```txt
Preciso controlar entregas.
```

Explique:

```txt
Quando uma carga é roteirizada, preciso saber cidade, motorista, veículo, quantidade de entregas, peso, custo e pendências.
```

## 6. MVP

MVP não é o produto completo.

É a menor versão útil.

Pergunta principal:

```txt
Qual é a menor solução que já reduz a dor real?
```

## 7. Especificação

Antes de implementar, escreva:

- objetivo;
- escopo;
- fora de escopo;
- regras;
- critérios de aceite;
- riscos;
- arquivos prováveis;
- testes esperados.

Essa especificação guia a IA.

## 8. Implementação com IA

A IA deve receber uma tarefa pequena.

Evite:

```txt
Crie o sistema inteiro.
```

Prefira:

```txt
Implemente o cadastro básico de veículos conforme a especificação.
Não altere outras áreas.
Atualize a documentação afetada.
```

## 9. Validação

Nunca aceite apenas porque a IA disse que terminou.

Valide:

- build;
- testes;
- comportamento real;
- dados salvos;
- fluxos principais;
- regressões.

## 10. Evolução

Depois de validar, registre:

- o que mudou;
- o que funcionou;
- o que falhou;
- o que ficou pendente;
- qual é a próxima tarefa.

É assim que um projeto deixa de depender da memória do chat.

## Regra principal

```txt
Se você não consegue explicar o problema,
a IA não deveria começar a implementar.
```
