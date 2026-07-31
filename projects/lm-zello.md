# Projeto: LM Zello

**Engenheiro:** Arthur (Senior · CTO)

## Visão

Um **sistema operacional para clínicas de cirurgia plástica**. Não é uma ferramenta pontual —
é a plataforma onde a clínica opera o dia a dia por completo. Produto **premium**: cobre
muitas áreas do contexto da clínica com profundidade.

## Pilares

### 1. WhatsApp como canal central
- Integração direta com o WhatsApp da clínica.
- Base de clientes comunicável no dia a dia para realizar o atendimento pela plataforma.
- Envio e recebimento de imagens, áudio, vídeos e documentos.

### 2. Jornada clínica completa
- Solicitações de exame.
- Assinatura de documentos.
- Consultas ao vivo, com prontuários sendo formados durante o atendimento.
- Recebimento de exames com anexação automática ao prontuário do paciente.

## Estratégia de evolução

O produto evolui exposto à realidade — ver [principles.md](../principles.md):

1. Sistema **em produção** nas VPSs — ver [assets.md](../assets.md).
2. Grupo seleto de testadores usando de verdade e devolvendo feedback.
3. Ciclo: desenvolver → publicar → enfrentar dificuldades reais → ajustar.

## Base técnica

- Stack padrão da área ([stack.md](../stack.md)), derivada do template
  [Morfeu](morfeu.md).

## Estado atual

- Em desenvolvimento por Arthur, preparando exposição a testadores.
- Próximo marco: sistema rodando em produção nas VPSs com grupo de teste ativo.
