# Papel: Engenheiro

## Missão

Construir e operar projetos de ponta a ponta. Na CIS não há separação entre quem pensa,
quem constrói e quem opera: o Engenheiro é dono técnico e de produto do que carrega.
A [stack declarativa](../stack.md) existe exatamente para tornar isso possível.

## Responsabilidades

1. **Construir** — desenvolver o projeto a partir do template [Morfeu](../projects/morfeu.md):
   declarar os domínios como recursos Ash e derivar o backend. Frontend e integrações
   fazem parte do pacote.
2. **Operar em produção** — deploy e manutenção do projeto rodando na VPS
   (Coolify/Dokploy). Não existe "meu código funciona, produção é problema de outro" —
   quem constrói, opera.
3. **Ouvir quem usa** — acompanhar os testadores/usuários do seu projeto e transformar
   feedback bruto em prioridade. Sem Product Leader na estrutura, essa responsabilidade
   é do Engenheiro do projeto.
4. **Testar** — TDD no desenvolvimento e verificação em produção. O produto à prova é o
   princípio nº 1 da área.
5. **Dar visibilidade** — apresentar seus projetos nas [reuniões de controle](../meetings.md):
   demo, progresso, feedback colhido e bloqueios.

## Dimensionamento

- **1 engenheiro por projeto é o padrão** — e é suficiente, pelo desenho da stack.
- **2 ou 3** quando o projeto justifica; **3 é o teto** por projeto.
- Um engenheiro senior pode carregar mais de um projeto (ver [alocação atual](../team.md)).

## Relação com os outros papéis

- **Com o CTO**: segue a stack e os princípios da área; escala decisões técnicas que
  fogem do padrão (nova dependência estrutural, mudança de infra, desvio de stack).
- **Com o CEO**: via reuniões de controle — progresso para lá, portas e recursos para cá.
- **Entre engenheiros**: conversa direta, sem intermediário. Código compartilhado
  (Morfeu, padrões) muda com alinhamento com o CTO.

## O que o papel NÃO é

- Não é executor de tickets — é dono do projeto.
- Não escolhe stack própria — a especialidade da área é uma só, e é isso que permite
  qualquer engenheiro pegar qualquer projeto.
