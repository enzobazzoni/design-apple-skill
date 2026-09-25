# Principios de referencia

Sintese autoral para aplicar a sites e interfaces. Fontes oficiais consultadas em 2026-09-25; use os links para confirmar orientacoes atuais em trabalhos nativos Apple.

## 1. Fundamentos humanos

As Apple Human Interface Guidelines apresentam oito lentes de decisao:

- **Proposito:** priorizar valor real e as tarefas que importam.
- **Agencia:** dar liberdade, informar o que acontece e facilitar recuperacao de erros.
- **Responsabilidade:** proteger seguranca, privacidade e confianca com transparencia.
- **Familiaridade:** aproveitar modelos mentais conhecidos e aplica-los de forma consistente.
- **Flexibilidade:** acolher diferentes pessoas, dispositivos, contextos e entradas.
- **Simplicidade:** retirar o desnecessario e organizar o restante com clareza.
- **Craft:** cuidar de detalhes, robustez, desempenho e evolucao continua.
- **Delight:** criar a emocao adequada como resultado do todo, nao como decoracao gratuita.

Fonte: [Design principles](https://developer.apple.com/design/human-interface-guidelines/design-principles)

## 2. Processo de ideia a interface

O processo apresentado pela equipe de Design Evangelism organiza a avaliacao em quatro frentes:

1. **Estrutura:** inventariar recursos e fluxos, compreender contexto de uso, eliminar excessos e agrupar o que pertence junto.
2. **Navegacao:** manter as pessoas orientadas, separar navegacao de acoes e usar nomes explicitos.
3. **Conteudo:** mostrar primeiro o necessario, revelar detalhes progressivamente e escolher lista, grade ou colecao conforme a natureza do conteudo.
4. **Visual:** usar hierarquia, tipo, imagem e cor para reforcar significado e personalidade sem sacrificar funcao.

Fonte: [Design foundations from idea to interface](https://developer.apple.com/videos/play/wwdc2025/359/)

## 3. Layout responsivo

- Agrupe relacoes por proximidade, espaco, superficie ou separadores.
- Reserve espaco suficiente para a informacao essencial.
- Adapte-se a redimensionamento, orientacao, texto maior, idioma e direcao de leitura.
- Preserve familiaridade entre contextos sem forcar a mesma composicao em toda tela.

Traducao web: use containers fluidos, `minmax()`, `clamp()`, grid/flex responsivos, ordem semantica estavel e breakpoints guiados pelo conteudo.

Fonte: [Layout](https://developer.apple.com/design/human-interface-guidelines/layout)

## 4. Tipografia e cor

- Tipografia deve sustentar legibilidade e hierarquia; evite pesos leves em textos pequenos e limite o numero de familias.
- Cores devem ter papeis semanticos consistentes, variantes adequadas por tema e contraste suficiente.
- Nao use cor como unico indicador de interatividade, foco, erro ou sucesso.
- Texto sobre imagem exige uma area de leitura confiavel; ajuste enquadramento, contraste ou superficie de apoio.

Fontes: [Typography](https://developer.apple.com/design/human-interface-guidelines/typography), [Color](https://developer.apple.com/design/human-interface-guidelines/color)

## 5. Acessibilidade e entradas

- Uma interface inclusiva deve ser intuitiva, perceptivel e adaptavel.
- Considere toque, ponteiro, teclado, voz e tecnologias assistivas quando relevantes.
- Suporte texto ampliado, zoom, foco visivel, nomes acessiveis e alternativas a informacao puramente visual.
- Para web, use WCAG atual como criterio verificavel de contraste e operacao; HIG e inspiracao complementar, nao substituta.

Fontes: [Accessibility](https://developer.apple.com/design/human-interface-guidelines/accessibility), [Gestures](https://developer.apple.com/design/human-interface-guidelines/gestures/)

## 6. Interacao, movimento e feedback

- Acoes principais devem ser reconheciveis, rotuladas com clareza e ter area de ativacao confortavel.
- Todo controle customizado precisa mostrar resposta ao pressionar e ao focar.
- Movimento deve explicar mudanca, relacao espacial, estado ou resultado; precisa ser opcional quando puder causar desconforto.
- Feedback deve comunicar estado, sucesso, falha, risco e recuperacao no nivel de destaque adequado.

Fontes: [Buttons](https://developer.apple.com/design/human-interface-guidelines/buttons), [Motion](https://developer.apple.com/design/human-interface-guidelines/motion), [Feedback](https://developer.apple.com/design/human-interface-guidelines/feedback)

## 7. Diferencas de contexto

Nao trate "responsivo" como uma miniatura de desktop:

- **Telefone:** foco estreito, uso em movimento, toque e alcance fisico; poucos controles simultaneos.
- **Tablet:** mudanca frequente de tamanho, toque mais teclado/ponteiro e composicoes com paineis quando houver espaco.
- **Desktop:** janelas redimensionaveis, maior densidade informacional, teclado, ponteiro, atalhos e hover.
- **Espacial:** conforto visual, profundidade e entradas por olhos/maos exigem regras proprias; nao simule isso na web apenas com vidro.

Indice oficial: [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)

## 8. Auditoria rapida

Use estas perguntas na revisao:

- A interface ajuda uma pessoa real a concluir a tarefa central?
- Ela sabe onde esta, o que pode fazer e para onde ir?
- A acao principal vence visualmente sem competir com varias equivalentes?
- A composicao ainda funciona com texto longo, dados vazios, erro e carregamento?
- Teclado, toque, foco e leitor de tela recebem informacao equivalente?
- A animacao explica algo e pode ser reduzida?
- O sistema visual expressa a marca do projeto em vez de imitar a Apple?
- O resultado foi conferido renderizado, nao apenas no codigo?
