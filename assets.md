# Ativos

Recursos à disposição da área de tecnologia. Cada ativo existe para servir os
[princípios](principles.md).

## Infraestrutura

### VPSs (x2)
- Duas VPSs disponíveis para produção dos produtos.
- Propósito: enfrentar dificuldades reais de operação e expor os produtos aos testadores.
- Padrão de deploy: Coolify/Dokploy; com 2+ VPSs conectadas, load balancer na Cloudflare
  — ver [stack.md](stack.md).
- A definir/documentar: qual VPS roda o quê (produção vs. staging), acessos, provisionamento.

### Infisical (self-hosted)
- Instância própria em https://infisical.softforge.com.br para gerenciamento de senhas
  e segredos (credenciais de VPS, chaves de API, variáveis de ambiente dos produtos).
- Regra: segredo não vive em `.env` commitado, mensagem ou anotação — vive no Infisical.

## Gestão de trabalho

### Linear
- Ferramenta oficial de gestão de trabalho da CIS, usada por **CEO, CTO e Engenheiros**.
- **Filosofia: Linear registra estratégia, não implementação.** Issues descrevem O QUE
  será construído e o porquê, em linguagem de produto — sem código, sem jargão técnico.
- Hierarquia: épico > feature > task (sub-issues), com relações de dependência.
- As [reuniões de controle](meetings.md) têm suas saídas registradas no Linear.

Dois recursos dos projetos no Linear são instrumentos centrais do nosso processo:

- **Milestones** — a estrada até o que o projeto realmente é. Cada projeto declara seus
  milestones no Linear; eles dão a direção e são a régua das reuniões de controle.
- **Project updates** — o diário de bordo. O engenheiro do projeto registra updates
  **quase diariamente**: o que andou, o que travou, o que aprendeu. É assim que a
  atividade real do projeto fica visível para todos, todos os dias.
- Demais campos (status, priority, lead, members, datas, teams, labels) mantidos
  atualizados como consequência natural — o lead de cada projeto no Linear é o
  engenheiro dono declarado em `projects/`.

## Comunicação

### Slack
- Ferramenta oficial de comunicação do time — universal para times de software.
- Conversa do dia a dia entre engenheiros, CTO e CEO acontece lá, não em canais avulsos.
- Integração nativa com o Linear: project updates e notificações fluem para o Slack,
  mantendo todos informados sem esforço extra.

Mapeamento do workspace:

| Projeto da área | Linear |
|-----------------|--------|
| [LM Zello](projects/lm-zello.md) | Time Softforge (SFG) · projeto "LM Zello" |
| [Redirecionador](projects/redirecionador.md) | Time Softforge (SFG) · projeto "RedirecionadorPro" |
| [Morfeu](projects/morfeu.md) | Time Softforge (SFG) · projeto "AshBase App" |
| [IA Security](projects/ia-security.md) | Times "VMS IA Security" (VMS) e "IA Security" (IASEC) |

## Agentes e automação

### Hermes Agent
- Agente à disposição do time para uso criativo no dia a dia e em automações.
- Candidatos naturais: rotinas recorrentes, preparação das reuniões de terça/quinta,
  acompanhamento de feedback dos testadores.

## Templates e base de código

### Morfeu (Ash Framework)
- Projeto-template e base comum da área — detalhes em
  [projects/morfeu.md](projects/morfeu.md). Mantido pelo CTO.
