# Análise de Evasão de Clientes (Churn) - TelecomX
Este projeto tem como objetivo identificar os principais fatores que contribuem para a evasão de clientes (churn) em uma empresa de telecomunicações fictícia, a TelecomX. Através de técnicas de limpeza de dados, análise exploratória e visualização, buscamos oferecer insights estratégicos para aumentar a retenção de clientes.

## Objetivo
Compreender por que os clientes deixam a empresa e como minimizar a evasão através da análise de dados. A retenção de clientes é um fator crítico para empresas de serviços, especialmente no setor de telecomunicações, onde os custos de aquisição são altos.

## O que foi feito
* Importação de dados brutos (formato JSON) diretamente de um repositório remoto.

* Tratamento de colunas com estruturas aninhadas (dicionários como strings).

* Renomeação e seleção de variáveis relevantes.

* Conversão e limpeza de dados ausentes.

* Criação de novas variáveis (features) para enriquecer a análise.

* Análise exploratória de dados (EDA), com foco em:

  * Gênero

  * Idade (SeniorCitizen)

  * Tipo de contrato

  * Tipo de serviço de internet

  * Método de pagamento

  * Extração de insights acionáveis e recomendações práticas para retenção de clientes.

## Principais Conclusões
Gênero não é um preditor relevante para churn.

Clientes idosos apresentam taxa de evasão mais alta (41,68%) do que os não idosos (23,61%).

Contratos "Month-to-month" concentram maior risco de evasão.

O serviço "Fiber optic", amplamente utilizado por idosos, pode estar associado ao churn.

O método de pagamento "Electronic check" aparece frequentemente em clientes que cancelam o serviço.

## Recomendações Estratégicas
Desenvolver programas de retenção específicos para o público idoso.

Incentivar contratos de longo prazo (1 ou 2 anos) com benefícios exclusivos.

Avaliar a experiência com o serviço "Fiber optic", buscando melhorar sua qualidade e custo-benefício.

Promover métodos de pagamento automáticos, como débito automático ou cartão de crédito.

Criar programas de fidelidade com recompensas por permanência, especialmente focados no grupo de risco.

## Tecnologias Utilizadas
* Python 3.x

* Pandas

* NumPy

* Matplotlib
