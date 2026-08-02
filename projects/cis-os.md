# Projeto: CIS OS *(nome provisório)*

**Engenheiro:** Arthur (Senior · CTO)

## Visão

O software onde a CIS roda. Cada pessoa da empresa tem sua conta, seu próprio agente
de IA, suas tarefas e suas formas de escrever e organizar o dia a dia. A empresa
opera **dentro** dele.

## A aposta

- **Usar software é alavancagem.** A área de tecnologia não existe só para construir
  propriedade intelectual vendável: toda pessoa e toda área da CIS pode ser
  multiplicada por software. Esse benefício, que hoje é natural para engenheiros,
  é levado para o resto da empresa.
- **Dogfooding → produto.** Funcionalidades nascem de pedidos reais das pessoas da
  CIS, para o dia a dia delas. Se a adoção e o feedback mostrarem valor de verdade,
  uma funcionalidade — ou o software inteiro — pode virar produto por si só.

## Forma (decisão de partida)

Uma **plataforma única, organizada em torno de pessoas** — não um software por área,
nem um software por pessoa:

- Um software só, sobre a base comum do [Morfeu](morfeu.md).
- **Pessoa como unidade**: conta própria, agente de IA próprio, tarefas e escrita
  como primitivas básicas.
- **Área como agrupamento de funcionalidades**, não como produto separado: features
  específicas de cada área crescem por demanda real, dentro da mesma plataforma.

Por quê: base única aproveita a alavancagem do Morfeu; pessoa como unidade faz o
valor aparecer no dia a dia de cada um; e nada impede que um módulo de área se
destaque e vire produto depois. **Esta forma é hipótese de partida — adoção e
feedback podem mudá-la.**

## Método

1. **Ouvir cada pessoa/área**: o que consome tempo hoje que software poderia remover?
2. **Construir a menor funcionalidade útil para UMA pessoa** — não a plataforma
   inteira de uma vez.
3. **Medir adoção real** — uso no dia a dia, não opinião.
4. O que for útil de verdade vira candidato a produto.

## Ideias registradas

### 1. Devlog — acompanhamento visual do desenvolvimento *(primeira candidata)*

Um software para o próprio processo de desenvolvimento de software, derivado do Morfeu:

- **Upload de mídia**: imagens, fotos e vídeos de gravação de tela do que está sendo
  construído.
- **Reviews semanais** postadas lá, mostrando a evolução do produto através de vídeos
  e fotos ao longo do tempo — a linha do tempo visual de cada projeto.
- **Feedback da empresa** acompanhado no mesmo lugar: comentários sobre o que foi
  mostrado, direto na review.
- Alavanca o processo de desenvolvimento e a **comunicação CTO ↔ CEO**: a demo de
  quinta ganha um lar permanente e consultável, em vez de existir só ao vivo.

## Estado atual

- Projeto iniciado em agosto/2026. Primeiro passo: levantamento pessoa a pessoa.

## Campos em aberto

- [ ] Nome definitivo
- [ ] Team/projeto no Linear
- [ ] Primeiras conversas de levantamento (Rafael, Kleverson)
