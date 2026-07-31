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

## Agentes e automação

### Hermes Agent
- Agente à disposição do time para uso criativo no dia a dia e em automações.
- Candidatos naturais: rotinas recorrentes, preparação das reuniões de terça/quinta,
  acompanhamento de feedback dos testadores.

## Templates e base de código

### Morfeu (Ash Framework)
- Projeto-template da área: clona-se e deriva-se novos produtos rapidamente, com a base
  mais difícil já implementada.
- Backend declarativo: macros em Elixir declaram recursos do Ash Framework (domínios)
  e todo o resto do backend é derivado.
- É a base técnica do LM Zello e de qualquer produto futuro. Mantido pelo CTO.
