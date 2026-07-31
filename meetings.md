# Reuniões de Controle

Duas reuniões por semana sustentam um ciclo de desenvolvimento saudável.
Elas são a cola que une a tecnologia ao resto da empresa — **inegociáveis**.

## Visão geral

| Reunião | Quando | Participantes | Pergunta que responde |
|---------|--------|---------------|----------------------|
| **Direção** | Terça | CEO + CTO + Engenheiros | "O que vamos fazer e por quê?" |
| **Progresso** | Quinta | CEO + CTO + Engenheiros | "O que ficou pronto e o que aprendemos?" |

Reuniões com testadores/usuários são à parte: qualquer dia, conforme necessidade,
conduzidas pelo engenheiro do projeto.

## A pauta vive no Linear

As reuniões de controle são discutidas **em cima do Linear**, não de memória:

- **Milestones guiam a direção.** Cada projeto tem seus milestones declarados no Linear —
  eles são a estrada até o que o projeto realmente é. Toda discussão de prioridade
  começa perguntando: "em que milestone estamos e o que falta para o próximo?"
- **Project updates são leitura prévia.** O engenheiro registra updates quase diários;
  CEO e CTO chegam na reunião **já lidos**. A reunião serve para decidir, não para
  relatar — relato é o que os updates já fizeram durante a semana.

---

## Terça — Reunião de Direção

**Objetivo:** alinhar prioridades da semana e destravar decisões que dependem do CEO.

**Formato (30–45 min), por projeto:**

1. **Estado em produção** (2 min) — o projeto está no ar? Algum incidente desde quinta?
2. **Feedback dos testadores** (10 min) — o que os usuários disseram/fizeram. Fatos, não
   impressões: o que usaram, onde travaram, o que pediram.
3. **Prioridades da semana** (10 min) — o que o engenheiro vai atacar até quinta e por quê,
   derivado do milestone atual do projeto. Máximo 3 prioridades por projeto.
4. **Decisões e bloqueios** (10 min) — o que precisa do CEO: dinheiro, contatos,
   decisões de negócio, acesso a clientes/testadores.

**Saída obrigatória:** prioridades da semana registradas no **Linear** (issues
priorizadas por projeto).

## Quinta — Reunião de Progresso

**Objetivo:** demonstrar o produto funcionando e prestar contas do que foi priorizado
na terça.

**Formato (30–45 min), por projeto:**

1. **Demo ao vivo** (15 min) — mostrar o que entrou no projeto **em produção, não em
   localhost**. Demo > slides, sempre.
2. **Prioridades da terça** (5 min) — o que foi concluído, o que não foi e por quê.
   Sem julgamento; o objetivo é calibrar o quanto cabe numa semana.
3. **Próximos passos para os testadores** (5 min) — o que será exposto aos usuários e
   que feedback queremos colher.
4. **Visão de frente** (5 min) — progresso no milestone atual: o que falta para
   cruzá-lo, e o que se desenha para a próxima semana (vira insumo da terça).

**Saída obrigatória:** Linear atualizado — issues entregues marcadas como Done, o que
rolou para a semana seguinte repriorizado.

---

## Como conversar nessas reuniões

- **Fatos antes de opiniões.** "3 testadores travaram no envio de exame" vale mais que
  "acho que está confuso".
- **Demo em produção é a prova.** Se não dá para demonstrar, não está pronto.
- **Quem apresenta o quê:** cada engenheiro apresenta os seus projetos — demo, técnico
  e feedback. O CTO conduz a reunião e fecha as prioridades; o CEO decide o que é de
  negócio.
- **Divergência é bem-vinda, na reunião.** Depois da reunião, a prioridade registrada
  é a prioridade — até a próxima terça.
- **Tudo que for decidido é registrado.** Decisão não escrita não existe: prioridade e
  trabalho vivem no **Linear**; regras e estrutura do time vivem nestes docs.
