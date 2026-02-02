# Case de Análise de Dados | Petlove 2026

Este repositório contém a resolução do case técnico para o processo seletivo de estágio. O projeto consiste em uma análise exploratória e estratégica sobre o comportamento de cancelamento e retenção de clientes de planos de saúde pet.

## Resumo 
A análise identificou que o fator determinante para a retenção não é o preço, mas o uso efetivo do plano e dos serviços do ecossistema.

* **Correlação de Uso:** Clientes que utilizam serviços adicionais apresentam uma taxa de retenção de 73%, significativamente superior à média.
* **Risco Financeiro no Segmento VIP:** O grupo de maior ticket médio apresenta a maior taxa de cancelamento (40%). Na amostra analisada, isso representa um risco de perda de receita anual projetada em R$ 7.200,00.

## Estratégias Propostas
Com base nos dados, foram sugeridas ações focadas em ROI e LTV:

1.  **Downgrade Preventivo:** Implementação de oferta ativa de migração para planos básicos em perfis de "Alto Custo e Baixo Uso", visando preservar o fluxo de caixa em vez de perder o cliente total.
2.  **Transitividade de Planos:** Estratégia de upgrade para "heavy users" do plano básico e reposicionamento do Plano Avançado.
3.  **Estratégia de Aquisição:** Parcerias para oferecer o "1º Banho Grátis", incentivando a criação do hábito de uso desde o primeiro mês de assinatura.

## Stack 
* **Linguagem:** Python 3
* **Manipulação de Dados:** Pandas, Numpy
* **Visualização:** Matplotlib, Seaborn
* **Metodologias:** Análise de Cohort (Sobrevivência), Cálculo de LTV e Simulação Financeira.

---
Desenvolvido por Marcus Santiago.
