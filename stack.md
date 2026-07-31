# Especialidade: Web Apps com Postgres

A área de tecnologia tem UMA especialidade, e todos os produtos nascem dela.
É essa restrição que permite 1 desenvolvedor por produto e times intercambiáveis.

## A stack

| Camada | Tecnologia | Papel |
|--------|-----------|-------|
| Backend | **Ash Framework + Phoenix** (Elixir) | Backend declarativo: domínios como recursos Ash, resto derivado |
| Banco | **PostgreSQL** | Único banco. Sem exceções por produto |
| Base | **Morfeu** (template próprio) | Clona-se e deriva-se um produto novo com a base difícil pronta |
| Infra | **VPS** | Produção em VPSs próprias — ver [assets.md](assets.md) |
| Deploy | **Coolify / Dokploy** | Para setups com mais de 1 VPS conectada |
| Rede | **Cloudflare** | Load balancer na frente das VPSs |
| Segredos | **Infisical** (self-hosted) | Gerenciamento de senhas e segredos — instância em https://infisical.softforge.com.br |

## Por que essa stack

1. **Declarativo escala uma pessoa.** Declaramos os domínios (macros Elixir → recursos
   Ash) e derivamos o backend inteiro. É por isso que 1 dev carrega 1 produto.
2. **Repetível.** Todo produto novo começa clonando o Morfeu. A base mais difícil se
   resolve uma vez e se reaproveita sempre.
3. **Operável.** VPS + Coolify/Dokploy + Cloudflare é infraestrutura que uma pessoa
   entende de ponta a ponta — sem dependência de especialista de cloud.

## Regras

- **Produto novo = essa stack.** Desvios só com decisão explícita do CTO, registrada aqui.
- **Referência**: docs em hexdocs.pm/ash* e github.com/ash-project. Consultar docs
  oficiais antes de implementar contra o framework.
- Setups de VPS única podem dispensar load balancer; a partir de 2 VPSs conectadas,
  Coolify/Dokploy + Cloudflare LB é o padrão.
