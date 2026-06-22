# 07 — Evidências da Jornada

Este documento registra projetos, protótipos e experimentos que ajudaram a formar esta jornada.

Nem todo projeto aqui virou produto final.

Alguns foram tentativas, testes de ferramentas, mudanças de direção ou protótipos incompletos.

Mesmo assim, eles são importantes porque mostram o caminho real: tentativa, erro, pesquisa, ajuste e evolução.

## Por que registrar isso

É fácil olhar para um projeto atual e imaginar que ele nasceu pronto.

A realidade foi diferente.

A jornada passou por muitos experimentos.

Registrar esses projetos ajuda a mostrar que criar software com IA não é mágica.

É um processo de investigação contínua.

## O que estes repositórios provam

Eles mostram que houve experimentação real antes de existir um método claro.

A sequência não foi:

```txt
ideia perfeita → framework perfeito → produto perfeito
```

Foi mais próximo de:

```txt
dor real → tentativa → erro → pesquisa → nova ferramenta → novo protótipo → mais clareza → método
```

Isso importa porque o objetivo deste projeto não é vender uma imagem falsa de facilidade.

O objetivo é mostrar que pessoas comuns podem avançar quando transformam problemas reais em experimentos pequenos, validam o que funciona e registram o aprendizado.

---

## RouteWise

Repositório:

```txt
MatheusUTI/RouteWise
```

### Papel na jornada

O RouteWise representa uma fase inicial e ambiciosa da tentativa de transformar problemas logísticos reais em software.

Ele pode ser visto como um dos catalisadores da necessidade de um método mais estruturado.

### O que ele tentou resolver

- roteirização;
- operação logística;
- controle de entregas;
- dashboards;
- múltiplos módulos;
- experiência de sistema profissional.

### Aprendizado principal

O RouteWise mostrou que projetos reais crescem rápido demais para depender apenas de prompts longos e memória de conversa.

Ele ajudou a revelar a necessidade de:

- escopo mais controlado;
- documentação persistente;
- ciclos menores;
- continuidade entre sessões de IA;
- um método como o AISDD.

### Frase síntese

```txt
O RouteWise não foi apenas um software.
Foi o projeto que revelou a necessidade de um método.
```

---

## Projetos / Roteirizador Pro

Repositório:

```txt
MatheusUTI/Projetos
```

### Papel na jornada

Este repositório registra uma tentativa de criar um conjunto operacional para roteirização, triagem e gestão de entregas.

Ele combinava dois entregáveis:

- um aplicativo web SPA;
- uma planilha operacional complementar.

### O que ele tentou resolver

- importação de CSV;
- triagem de entregas;
- regras de ocorrência;
- dashboard de KPIs;
- montagem de rotas;
- mapa interativo;
- cadastro de frota;
- cálculo de custos;
- geração de manifestos;
- planilha operacional com fórmulas e formatação condicional.

### Aprendizado principal

Este projeto mostrou que a dor logística era real e que o domínio operacional já estava claro.

Também mostrou que uma solução útil precisaria integrar:

```txt
importação → triagem → roteirização → frota → custos → manifestos
```

Ele também mostra uma fase importante da jornada: tentar unir o mundo prático da planilha com uma interface web mais estruturada.

### Frase síntese

```txt
Este repositório mostra a fase em que a solução ainda era uma mistura de app web, planilha e experimentação operacional.
```

---

## Roteirizador_RCS

Repositório:

```txt
MatheusUTI/Roteirizador_RCS
```

### Papel na jornada

O Roteirizador_RCS representa uma fase de experimentação técnica mais algorítmica.

Ele usou Python, Streamlit, Pandas, geocodificação e mapas para testar uma abordagem diferente para a roteirização last-mile.

### O que ele tentou resolver

- ETL automático de dados do SSW;
- limpeza e sanitização de endereços;
- regras de agenda por cidade e dia;
- clientes Curva A / VIP;
- prevenção de sobrecarga;
- sugestão de corte de carga;
- geocodificação resiliente;
- fallback para endereços problemáticos;
- sequenciamento LIFO;
- mapas interativos;
- exportação de romaneio;
- logs operacionais.

### Aprendizado principal

Este projeto mostrou que a escolha da ferramenta muda a forma de pensar o problema.

Streamlit e Pandas aceleraram a prototipação, mas também revelaram complexidades:

- geocodificação em operação real é difícil;
- mapas são úteis, mas podem adicionar ruído;
- regras de carga física importam;
- LIFO não é apenas detalhe técnico, é operação real;
- o domínio vem antes da interface.

### Frase síntese

```txt
O Roteirizador_RCS mostra que eu experimentei ferramentas diferentes até entender melhor quais partes do problema realmente importavam.
```

---

## Roteirizador atual

Repositórios relacionados:

```txt
MatheusUTI/NewRouteWise
MatheusUTI/Roteirizador_RCS
MatheusUTI/RouteWise
MatheusUTI/Projetos
```

### Papel na jornada

O Roteirizador atual representa a consolidação progressiva dos experimentos anteriores.

Ele nasce de uma dor diária real de logística e vai incorporando, aos poucos, as lições dos protótipos anteriores.

### Aprendizado principal

O Roteirizador mostra que software útil nasce quando a pessoa que conhece o problema consegue transformar conhecimento operacional em regras, fluxos e validação.

A IA ajudou a implementar, mas o domínio logístico guiou o produto.

### Frase síntese

```txt
O Roteirizador é o ponto onde experiência operacional, pesquisa, IA e método começaram a se juntar.
```

---

## Casa em Dia

Repositório:

```txt
MatheusUTI/casaemdia
```

### Papel na jornada

O Casa em Dia funciona como laboratório Android.

Ele ensina outro tipo de complexidade: mobile, persistência local, notificações, testes, build e experiência de usuário.

### Aprendizado principal

O ritmo de desenvolvimento Android pode ser mais lento do que um sistema web ou protótipo operacional, porque envolve muitos detalhes implícitos da plataforma.

O Casa em Dia também funciona como laboratório de dogfooding do AISDD.

### Frase síntese

```txt
O Casa em Dia é o laboratório onde Android, testes e AISDD se encontram.
```

---

## AISDD

Repositório:

```txt
MatheusUTI/AISDD
```

### Papel na jornada

O AISDD nasceu como resposta à perda de contexto em projetos desenvolvidos com IA.

Ele organiza a continuidade usando documentos persistentes no repositório.

### Aprendizado principal

A conversa com IA é temporária.

O repositório precisa carregar a memória do projeto.

O AISDD não nasceu como teoria isolada.

Nasceu porque RouteWise, Roteirizador, Casa em Dia e outros experimentos mostraram que projetos reais precisam de continuidade, rastreabilidade e proteção contra alucinações.

### Frase síntese

```txt
AISDD é o método que nasceu da dor real de tentar construir software com IA sem perder contexto.
```

---

## Padrão observado

Olhando para esses projetos, existe uma linha clara:

```txt
problema real
↓
experimento simples
↓
protótipo maior
↓
ferramentas diferentes
↓
perda de contexto
↓
necessidade de método
↓
AISDD
↓
documentação da jornada
```

## Conclusão provisória

Esses repositórios antigos não são apenas sobras.

Eles são evidências.

Mostram que a jornada não começou com um framework pronto.

Começou com tentativas reais de resolver problemas reais.

Eles também mostram uma mensagem importante para outras pessoas:

```txt
Você não precisa acertar a ferramenta de primeira.
Você precisa continuar investigando o problema.
```
