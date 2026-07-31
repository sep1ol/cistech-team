# Papel: Desenvolvedor

## Missão

Construir e operar UM produto de ponta a ponta. Na nossa realidade, um desenvolvedor
carrega um produto inteiro — a [stack](../stack.md) declarativa existe exatamente para
tornar isso possível.

## Responsabilidades

1. **Construir** — desenvolver o produto a partir do template [Morfeu](../assets.md):
   declarar os domínios como recursos Ash e derivar o backend. Frontend e integrações
   (ex.: WhatsApp) fazem parte do pacote.
2. **Operar em produção** — o desenvolvedor faz deploy e mantém o produto rodando na VPS
   (Coolify/Dokploy). Não existe "meu código funciona, produção é problema de outro" —
   aqui, quem constrói, opera.
3. **Testar** — TDD no desenvolvimento e verificação em produção. O produto à prova é
   princípio nº 1 da área.
4. **Dar visibilidade** — progresso comunicado ao Product Leader no dia a dia e
   demonstrado nas [reuniões de controle](../meetings.md).

## Dimensionamento

- **1 desenvolvedor por produto é o padrão** — e é suficiente, pelo desenho da stack.
- **2 ou 3 é ótimo** quando o produto cresce; **3 é o teto** por projeto.
- Mais que isso indica um problema de arquitetura ou de escopo, não de gente.
  Ver [team.md](../team.md).

## Relação com os outros papéis

- **Com o Product Leader**: recebe prioridade clara, devolve progresso e alternativas
  técnicas. Conversa diária e direta.
- **Com o CTO**: segue a stack e os princípios da área; escala decisões técnicas que
  fogem do padrão (nova dependência estrutural, mudança de infra).

## O que o papel NÃO é

- Não é executor de tickets — é dono técnico do produto.
- Não escolhe stack própria — a especialidade da área é uma só, e é isso que permite
  qualquer desenvolvedor pegar qualquer produto.
