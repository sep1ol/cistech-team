# Princípios da Área de Tecnologia

Princípios em ordem de precedência. Em conflito, o de número menor vence.

## 1. O produto vai à prova, sempre
Software que só existe na máquina de desenvolvimento não é produto. Produção nas VPSs +
testadores reais é o padrão, não a exceção. Todo ciclo de trabalho deve aproximar o
produto da realidade.

## 2. Feedback real guia a evolução
O grupo de testadores é a fonte primária de direção. Dificuldades enfrentadas em produção
valem mais que hipóteses. Evolução saudável = ciclos curtos contra usuários reais.

## 3. Declarar antes de derivar
Vale para código (recursos Ash → backend derivado) e para o time (estes documentos →
operação derivada). A base difícil se resolve uma vez (Morfeu) e se reaproveita sempre.

## 4. Times pequenos, uma especialidade
1 engenheiro por projeto, teto de 3. Uma stack única ([stack.md](stack.md)) para
todos os projetos. Restrição é o que nos dá velocidade e intercambialidade.

## 5. Comunicação é parte do trabalho, não interrupção
O que não é comunicado não existe para o resto da empresa. As
[reuniões de controle](meetings.md) de terça e quinta são inegociáveis, e decisão não
escrita não existe.

## 6. Premium se constrói com profundidade
Melhor cobrir uma área de ponta a ponta (e testá-la em produção) do que dez áreas pela
metade.

## 7. Alavancagem via automação e software interno
Hermes Agent e automações existem para multiplicar o time. Tarefa recorrente feita
manualmente duas vezes é candidata a automação na terceira. O mesmo vale para a
empresa inteira: qualquer área da CIS pode ser multiplicada por software interno
([CIS OS](projects/cis-os.md)) — e o que provar valor no uso interno é candidato
a virar produto.
