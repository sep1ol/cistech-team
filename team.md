# Topologia do Time

Como a área de tecnologia se organiza. Somos **engenheiros trabalhando em projetos**:
times pequenos, donos claros, uma especialidade só.

## A unidade: o projeto

Cada projeto tem 1 a 3 engenheiros — nunca mais que isso:

- **1 engenheiro por projeto é o padrão.** A [stack declarativa](stack.md) foi desenhada
  para isso: a base difícil já está resolvida no Morfeu, o backend se deriva da
  declaração de domínios.
- **2 ou 3 engenheiros**: ótimo, quando o projeto justifica.
- **3 é o teto por projeto.** Acima disso o problema não se resolve com gente.
- Um engenheiro senior pode carregar mais de um projeto.

## Organograma

```
CEO (Rafael) ─── CTO (Arthur)
         ├── Base comum (Morfeu, infra, padrões)
         ├── IA Security ──── Kleverson
         ├── Redirecionador ─ Arthur
         ├── LM Zello ─────── Arthur
         └── Morfeu ────────── Arthur
```

## Alocação atual

| Pessoa | Cargo | Projetos |
|--------|-------|----------|
| **Arthur** | Engenheiro Senior · CTO | [Redirecionador](projects/redirecionador.md), [LM Zello](projects/lm-zello.md), [Morfeu](projects/morfeu.md) |
| **Kleverson** | Engenheiro Senior | [IA Security](projects/ia-security.md) |

## Como o time cresce

1. **Projeto novo** = 1 engenheiro dono, clonando o Morfeu. Nunca nasce sem dono.
2. **Projeto crescendo** = +1 engenheiro (até o teto de 3).
3. Engenheiros são intercambiáveis entre projetos porque a stack é uma só — realocação
   é decisão do [CTO](roles/cto.md).

Escalar = adicionar projetos com donos, nunca inchar um projeto além do teto.

## Comunicação

- **Dia a dia**: no **Slack** — canal oficial do time, com integração do Linear
  (ver [assets.md](assets.md)).
- **Entre engenheiros**: diária e direta, sem intermediário.
- **Atividade dos projetos**: project updates quase diários no Linear.
- **Com o CEO / entre projetos e empresa**: nas [reuniões de controle](meetings.md).
- **Regra**: o que não está escrito nos docs ou dito em reunião de controle não é
  decisão — é conversa.
