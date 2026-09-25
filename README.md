# Design Apple

Skill portátil para agentes de programação. Transforma princípios públicos das Apple Human Interface Guidelines em critérios para criar interfaces web modernas, acessíveis e autorais. Antes de criar ou reconstruir um site, o agente pergunta: “Você quer usar a skill Design Apple neste site?” Só aplica a direção visual se você aceitar.

Projeto independente, sem afiliação, aprovação ou patrocínio da Apple Inc. Não distribui marcas, fontes, ícones ou templates proprietários.

## Instalação

A mesma pasta com SKILL.md e references/principles.md funciona em agentes compatíveis com Agent Skills. Copie os dois itens, preservando a estrutura, para o local adequado:

| Agente | Pessoal / todos os projetos locais | No repositório |
| --- | --- | --- |
| Codex | ~/.agents/skills/design-apple/ ou ~/.codex/skills/design-apple/ | .agents/skills/design-apple/ |
| Claude Code | ~/.claude/skills/design-apple/ | .claude/skills/design-apple/ |
| Antigravity 2.0 / IDE | ~/.gemini/config/skills/design-apple/ | .agents/skills/design-apple/ |
| Antigravity CLI | ~/.gemini/antigravity-cli/skills/design-apple/ | .agents/skills/design-apple/ |

agents/openai.yaml é metadado opcional para Codex; outros agentes podem ignorá-lo. No Windows, ~ representa sua pasta de usuário. Após instalar, reinicie ou abra uma nova sessão se a skill não aparecer.

### Codex Cloud e Claude na nuvem

A instalação pessoal nesta máquina não é enviada automaticamente para sessões na nuvem. Para disponibilizar a skill em um projeto remoto, inclua a pasta em .agents/skills/design-apple/ (Codex Cloud) ou .claude/skills/design-apple/ (Claude Code cloud) e publique esses arquivos no repositório do projeto. No Claude, também é possível usar skills sincronizadas pela conta, se esse recurso estiver habilitado.

Este repositório é a fonte da skill; publicá-lo sozinho não instala a skill em todos os seus outros projetos ou contas.

## Pergunta automática em novos sites

A descrição da skill permite ativação implícita, mas nenhum agente promete acerto em 100% das solicitações. Para tornar a pergunta uma regra persistente, adicione a linha abaixo às instruções do agente:

> Ao receber um pedido para criar ou reconstruir um site, pergunte “Você quer usar a skill Design Apple neste site?” antes de implementar. Se a resposta for sim, leia e aplique a skill design-apple; se for não, prossiga sem ela. Não repita a pergunta se a escolha já estiver explícita.

Locais de regra: ~/.codex/AGENTS.md no Codex local; AGENTS.md no projeto Codex Cloud; ~/.claude/CLAUDE.md ou CLAUDE.md no projeto Claude; ~/.gemini/GEMINI.md ou GEMINI.md no projeto Antigravity. A regra lembra de perguntar; a skill ensina a criar a interface quando autorizada.

## Uso manual

- Codex: $design-apple
- Claude Code e Antigravity: /design-apple

Exemplo: “Crie uma landing page para minha empresa.” O agente deve perguntar sobre a Design Apple antes de construir. Se você já disser “use a Design Apple”, ele segue sem perguntar de novo.

## Conteúdo

- SKILL.md: fluxo e critérios de implementação.
- references/principles.md: síntese dos princípios e fontes oficiais.
- agents/openai.yaml: nome e descrição na interface Codex.

## Fontes

- https://developer.apple.com/design/
- https://developer.apple.com/design/human-interface-guidelines/
- https://developers.openai.com/codex/skills/
- https://developers.openai.com/codex/guides/agents-md/
- https://code.claude.com/docs/en/skills
- https://antigravity.google/docs/skills
- https://antigravity.google/docs/rules/
