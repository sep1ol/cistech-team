# Topologia do Time

Como a área de tecnologia se organiza. Regra geral: **times pequenos, por produto,
com papéis claros**.

## A unidade: o time de produto

Cada produto tem um time mínimo e autossuficiente:

```
Produto
├── 1 Product Leader   (direção, testadores, domínio)
└── 1–3 Desenvolvedores (construção e operação)
```

- **1 desenvolvedor por produto é o padrão.** A [stack declarativa](stack.md) foi
  desenhada para isso: a base difícil já está resolvida no Morfeu, o backend se deriva
  da declaração de domínios.
- **2 ou 3 desenvolvedores**: ótimo, quando o produto justifica.
- **3 é o teto por projeto.** Acima disso o problema não se resolve com gente.

## O CTO na topologia

O CTO está acima dos times de produto, não dentro deles:

```
CTO
├── Base comum (Morfeu, infra, padrões)
├── Time LM Zello ── Product Leader + Dev(s)
└── Time <futuro>  ── Product Leader + Dev(s)
```

- Aloca pessoas, define a stack, mantém a base comum.
- Exceção atual (modo fundador): o CTO acumula o papel de desenvolvedor do LM Zello.

## Como o time cresce

A ordem de contratação é derivada da topologia:

1. **Product Leader do LM Zello** — a primeira lacuna real. Hoje não há voz do cliente
   dedicada.
2. **+1 Desenvolvedor** — libera o CTO do acúmulo e dá ao LM Zello um dono técnico
   dedicado.
3. **Novos produtos** = novo time mínimo (1 PL + 1 dev), clonando o Morfeu.

Escalar = adicionar times pequenos, nunca inchar um time existente além do teto.

## Comunicação entre papéis

- **Dentro do time**: Product Leader ↔ Desenvolvedor, diária e direta, sem intermediário.
- **Entre times e empresa**: via CTO, nas [reuniões de controle](meetings.md).
- **Regra**: o que não está escrito nos docs ou dito em reunião de controle não é
  decisão — é conversa.
