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

## LL-008 — Múltiplas IAs melhoram a documentação

Durante a criação deste projeto, diferentes LLMs foram usados para analisar, criticar, revisar e melhorar o material.

Cada modelo contribuiu de uma forma diferente:

- ChatGPT ajudou com continuidade, síntese, arquitetura narrativa e registro no repositório.
- Gemini ajudou com refinamento editorial, escaneabilidade e apresentação profissional.
- Claude ajudou com estrutura, clareza e maturidade textual.
- Perplexity ajudou com pesquisa, posicionamento e comparação de mercado.
- DeepSeek ajudou com questionamentos práticos e riscos de adoção.
- Grok ajudou com crítica pragmática e sugestões de simplificação.

### Aprendizado

Usar múltiplas IAs não significa aceitar tudo sem critério.

Significa coletar perspectivas diferentes e decidir, humanamente, o que faz sentido para o projeto.

A combinação de modelos pode gerar documentação melhor do que depender de uma única IA isolada.

### Aplicação

Quando um documento for importante, usar mais de uma IA para:

- revisar clareza;
- encontrar lacunas;
- testar escaneabilidade;
- apontar exageros;
- sugerir estrutura;
- avaliar riscos.

A decisão final continua sendo humana.

## LL-009 — Encontrar pares pode exigir exposição

Ao refletir sobre a sensação de solidão intelectual, ficou claro que manter tudo privado protege o processo, mas também limita a chance de encontrar pessoas com inquietações parecidas.

Um repositório público não garante reconhecimento, conversa ou comunidade.

O resultado mais provável pode ser simplesmente nada acontecer.

Mesmo assim, tornar a documentação pública pode ser uma forma honesta de sinalizar:

```txt
Isto é o que estou investigando.
Se alguém pensa parecido, talvez não esteja sozinho.
```

### Aprendizado

Nem toda publicação precisa ter objetivo de viralizar, monetizar ou provar algo.

Às vezes, publicar é apenas abrir uma porta para que pessoas parecidas possam encontrar o caminho.

### Aplicação

Antes de publicar, o projeto deve preservar:

- honestidade;
- contexto;
- transparência sobre IA;
- ausência de promessa exagerada;
- cuidado com dados sensíveis;
- clareza de que o repositório é vivo e ainda está em construção.

## LL-010 — Código gerado não é engenharia

Uma reflexão importante surgiu ao ouvir discussões sobre IA, código, débito técnico e segurança.

A IA consegue gerar código cada vez mais rápido.

Mas gerar código não é o mesmo que construir software sustentável.

Código que funciona em uma demonstração pode ainda estar cheio de problemas:

- ausência de testes;
- regressões escondidas;
- regras duplicadas;
- falta de arquitetura;
- problemas de performance;
- falhas de segurança;
- vazamento de credenciais;
- ausência de rastreabilidade;
- risco jurídico e operacional.

A sintaxe está ficando mais barata.

A engenharia continua cara.

### Aprendizado

A responsabilidade pelo código gerado por IA continua sendo humana.

A IA pode acelerar a implementação, mas não substitui:

- validação;
- testes;
- arquitetura;
- revisão de segurança;
- compreensão do domínio;
- análise de riscos;
- manutenção de longo prazo.

O risco do desenvolvimento assistido por IA não é apenas a IA errar.

O risco é aceitar rapidamente um código que parece correto sem entender suas consequências.

### Aplicação

Em projetos reais, especialmente quando saem do protótipo, é preciso exigir mais do que "funcionou aqui".

Cada ciclo importante deve perguntar:

1. O que isso pode quebrar?
2. Que teste prova que continua funcionando?
3. Que dado sensível pode estar exposto?
4. Que comportamento pode falhar em escala real?
5. Que responsabilidade estou assumindo ao aceitar isso?

Essa lição reforça diretamente o propósito do AISDD:

```txt
A conversa com a IA é temporária.
O repositório deve ser a fonte da verdade.
```

E também reforça uma ideia central desta jornada:

```txt
A IA pode escrever código.
Mas software ainda exige engenharia.
```

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
