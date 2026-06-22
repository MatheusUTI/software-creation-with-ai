# 05 — Lições Aprendidas

Este documento registra aprendizados práticos da jornada.

As lições devem nascer de experiências reais, não de teoria solta.

## LL-001 — Prompt gigante não escala

No começo, é comum tentar colocar tudo no prompt:

- contexto;
- regras;
- arquitetura;
- alertas;
- arquivos;
- decisões antigas;
- próximos passos.

Isso funciona por pouco tempo.

Depois o projeto cresce e o prompt vira um peso.

### Aprendizado

O contexto importante precisa sair da conversa e ir para o repositório.

## LL-002 — Domínio importa mais que sintaxe

A IA pode escrever código.

Mas ela não conhece a operação real como a pessoa que vive o problema.

No Roteirizador, o avanço veio muito mais do entendimento logístico do que da escolha de tecnologia.

### Aprendizado

Quem entende profundamente o problema tem vantagem, mesmo sem ser programador tradicional.

## LL-003 — Uma tarefa por ciclo reduz regressões

Quando a IA recebe várias tarefas ao mesmo tempo, a chance de quebrar algo aumenta.

### Aprendizado

Trabalhar em ciclos pequenos ajuda a validar, corrigir e continuar.

## LL-004 — Handoff pode ficar defasado

Durante o dogfooding do Casa em Dia, `04_NEXT_TASK.md` foi atualizado, mas `07_HANDOFF.md` ficou para trás.

### Aprendizado

Documentos persistentes também precisam de sincronização.

A fonte de execução deve ser clara.

Exemplo:

```txt
NEXT_TASK é autoridade da tarefa.
HANDOFF é contexto de continuidade.
```

## LL-005 — Android evolui em ritmo diferente

O Casa em Dia evolui mais devagar que o Roteirizador.

Isso não significa fracasso.

Android envolve:

- estado;
- navegação;
- persistência;
- permissões;
- notificações;
- testes;
- ciclo de build;
- detalhes de plataforma.

### Aprendizado

Projetos diferentes têm ritmos diferentes.

Comparar velocidade sem considerar complexidade gera frustração.

## LL-006 — Ferramenta não substitui processo

Ter acesso a bons LLMs não basta.

Sem processo, a IA perde contexto, inventa regras e pode quebrar funcionalidades existentes.

### Aprendizado

A qualidade do resultado depende da combinação:

```txt
problema real + domínio + especificação + IA + validação + documentação
```

## LL-007 — Transparência sobre IA é necessária

Esconder o uso de IA reforça preconceitos e cria insegurança.

### Aprendizado

Este projeto deve declarar abertamente que usa IA como ferramenta de escrita, organização e construção.

O valor está na experiência, direção, validação e utilidade do resultado.

## Como adicionar novas lições

Use este formato:

```txt
## LL-XXX — Título

Contexto.

### Aprendizado

Conclusão prática.

### Aplicação

Como usar essa lição no futuro.
```
