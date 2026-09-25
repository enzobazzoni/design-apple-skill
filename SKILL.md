---
name: design-apple
description: Ao criar ou reconstruir sites, landing pages, portfolios, dashboards ou apps web, pergunte primeiro se o usuario quer usar a Design Apple. Se aceitar, aplique principios de clareza, adaptacao e acessibilidade inspirados nas Apple Human Interface Guidelines, sem copiar a identidade Apple.
---

# Design Apple

Produza uma experiencia autoral com clareza, adaptacao, acessibilidade e alto nivel de acabamento. Inspire-se nos principios, nao na aparencia proprietaria da Apple.

## Confirme o uso da skill antes de criar

Em todo pedido para criar, reconstruir ou desenvolver um site, verifique se o usuario ja escolheu usar ou nao a Design Apple.

- Se a escolha nao estiver definida, pare antes da implementacao e pergunte: **"Voce quer usar a skill Design Apple neste site?"**
- Aguarde a resposta antes de construir o site.
- Se a resposta for sim, aplique todas as instrucoes restantes desta skill.
- Se a resposta for nao, nao aplique a direcao visual desta skill e continue o trabalho normalmente com as demais instrucoes relevantes.
- Se o usuario ja pediu para usar ou nao usar a Design Apple, respeite a escolha e nao pergunte novamente.
- Nao interrompa correcoes pequenas ou manutencao de um site existente, a menos que o pedido inclua uma reconstrucao relevante.

## Comece pela intencao

Antes de definir a estetica, identifique pelo contexto disponivel:

- quem usa, qual problema resolve e qual acao principal importa;
- o conteudo real, a personalidade da marca e a emocao apropriada;
- dispositivos, tamanhos de tela e metodos de entrada relevantes.

Se faltarem dados nao bloqueantes, use hipoteses conservadoras e deixe textos ou ativos desconhecidos claramente substituiveis. Nunca invente resultados, clientes, depoimentos ou dados comerciais.

## Estruture antes de decorar

Cada tela deve responder rapidamente:

1. Onde estou?
2. O que posso fazer aqui?
3. Qual e o proximo passo?

Organize e priorize o conteudo antes de estilizar. Remova o que nao serve ao objetivo, agrupe itens relacionados e use divulgacao progressiva para detalhes secundarios. Prefira padroes familiares quando eles tornam a interface previsivel.

## Construa uma direcao autoral

- Derive tokens do projeto: cores semanticas, escala tipografica, espacamento, raios, bordas, sombras e movimento.
- Use uma hierarquia visual inequivoca: um foco principal por secao e contraste proporcional a importancia.
- Deixe espaco negativo proteger o conteudo; nao confunda minimalismo com vazio ou falta de informacao.
- Use imagens com funcao narrativa ou informativa, nao como preenchimento generico.
- Expresse personalidade com composicao, tipografia, cor, imagens e microinteracoes coerentes com a marca do usuario.

Nao aplique automaticamente vidro, blur, gradientes, cantos excessivamente arredondados, preto e branco ou grandes manchetes. Cada recurso precisa melhorar orientacao, legibilidade, significado ou emocao.

## Traduza os principios para a web

- Use HTML semantico, ordem de foco logica e navegacao por teclado.
- Adapte a composicao ao espaco disponivel; nao apenas reduza a versao desktop.
- Preserve conteudo e acoes essenciais entre breakpoints e mantenha posicoes previsiveis.
- Dimensione alvos interativos para toque confortavel e ofereca estados hover, focus-visible, active, loading, success, empty e error quando aplicaveis.
- Use cores por funcao e forneca contraste adequado; nunca dependa apenas de cor para comunicar estado.
- Permita zoom e texto ampliado sem corte, sobreposicao ou perda de acao.
- Use movimento para explicar relacoes, continuidade e feedback. Respeite `prefers-reduced-motion` e nao use animacao como unico canal de informacao.
- Respeite `prefers-color-scheme` quando o escopo pedir temas; teste os dois temas, nao apenas inverta cores.
- Mantenha carregamento, imagens e efeitos proporcionais ao beneficio percebido.

## Componentes e conteudo

- De destaque principal a no maximo uma ou duas acoes por vista.
- Rotule acoes com verbos claros; use icones familiares apenas quando forem compreensiveis no contexto.
- Para informacao textual densa, prefira listas ou tabelas legiveis a grades decorativas.
- Para colecoes visuais, use ritmo consistente, texto curto e uma ordem facil de explorar.
- Coloque feedback perto do item afetado e ajuste sua intensidade ao risco: status discreto, sucesso claro, erro acionavel e confirmacao para consequencias graves.
- Use ajuda contextual somente quando simplificar a interface nao resolver o problema.

## Limite de originalidade

Nao copie paginas, composicoes, animacoes, icones, textos, mockups, materiais, logotipos ou identidade comercial da Apple. Nao use SF Symbols, SF Pro ou Apple Design Resources fora das licencas e contextos permitidos. Nao descreva o resultado como oficial, afiliado ou aprovado pela Apple.

Quando o usuario fornecer uma referencia visual especifica, extraia apenas principios transferiveis e construa uma direcao propria para a marca dele.

## Verifique o resultado

Antes de concluir, teste a interface renderizada nos tamanhos relevantes e confirme:

- proposito, localizacao, acao principal e proximo passo evidentes;
- hierarquia, leitura e contraste funcionando com conteudo real;
- teclado, foco, toque, estados e feedback utilizaveis;
- ausencia de overflow, cortes e sobreposicoes;
- movimento reduzido e temas funcionando quando implementados;
- identidade propria, sem semelhanca indevida com um produto Apple especifico.

Para a origem dos criterios, diferencas entre dispositivos e auditoria detalhada, leia [references/principles.md](references/principles.md). Em projetos nativos para plataformas Apple, consulte tambem a HIG oficial atual, pois componentes e recomendacoes mudam.
