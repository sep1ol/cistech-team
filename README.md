# CIS — Tech Team

Este repositório declara como funciona a área de tecnologia da **CIS**: quem faz parte,
o que cada papel faz, como os projetos se organizam, no que somos especialistas e como
prestamos contas. Assim como no Ash Framework, declaramos os domínios e derivamos a
operação a partir deles.

## Estrutura

| Documento | Declara |
|-----------|---------|
| [roles/cto.md](roles/cto.md) | O papel do CTO |
| [roles/engineer.md](roles/engineer.md) | O papel do Engenheiro |
| [team.md](team.md) | Topologia: engenheiros, projetos e alocação atual |
| [stack.md](stack.md) | Nossa especialidade: Web Apps com Postgres |
| [meetings.md](meetings.md) | As 2 reuniões de controle semanais |
| [principles.md](principles.md) | Princípios que guiam decisões |
| [assets.md](assets.md) | Ativos: infra, agentes e templates |
| [projects/ia-security.md](projects/ia-security.md) | IA Security — Kleverson |
| [projects/redirecionador.md](projects/redirecionador.md) | Redirecionador — Arthur |
| [projects/lm-zello.md](projects/lm-zello.md) | LM Zello — Arthur |
| [projects/morfeu.md](projects/morfeu.md) | Morfeu (base comum) — Arthur |

## Como operar

1. Toda decisão relevante deve ser coerente com [principles.md](principles.md).
   Se não for, ou a decisão está errada, ou o princípio precisa ser atualizado — explicitamente.
2. Cada pessoa opera dentro do seu papel declarado em `roles/`. Dúvida sobre
   responsabilidade = ler o doc do papel. Se o doc não responde, o doc está incompleto.
3. Todo projeto tem um doc em `projects/` com engenheiro dono declarado. Projeto sem
   doc ou sem dono não existe para a área.
4. As [reuniões de controle](meetings.md) são o esqueleto do tempo. O desenvolvimento
   preenche o resto.
5. Estes documentos são vivos: quando a realidade mudar, a declaração muda junto,
   no mesmo commit em que a mudança acontece.
