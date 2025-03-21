## Descrição dos Dados

Este projeto utiliza uma base de dados fictícia presente na aba **"Bases"** para exemplificar a criação de dashboards e análises básicas relacionadas a assinaturas de um serviço. Os principais campos da base incluem:

- **ID do Assinante**: Identificação única para cada assinante.
- **Nome**: Nome do assinante.
- **Plano**: Tipo de plano (Ultimate, Core, Standard).
- **Data de Início**: Data de início da assinatura.
- **Renovação Automática**: Indica se a renovação automática está ativada.
- **Preço da Assinatura**: Valor do plano contratado.
- **Tipo de Assinatura**: Frequência do pagamento (Mensal, Trimestral, Anual).
- **Valores Relacionados**: Inclui descontos (como cupons), valor total da assinatura e status atual.
  
Além disso, a base contém dados complementares como a associação a passes de temporada (ex.: EA Play, Minecraft) e descontos associados.

## Possibilidades de Análise no Dashboard

A aba **"Dashboard"** apresenta um exemplo de painel com as seguintes análises possíveis:

1. **Visão Geral de Assinaturas**:
   - Quantidade total de assinantes.
   - Receita total e média por assinante.
   
2. **Assinaturas por Status**:
   - Distribuição entre assinantes ativos e inativos.
   - Assinantes classificados por tempo restante de atividade (menos de 7, 15 ou 30 dias, ou ativos por períodos mais longos).
   
3. **Receita por Tipo de Plano**:
   - Receita total agrupada por tipo de pagamento (Mensal, Trimestral ou Anual).
   
4. **Retenção e Renovação**:
   - Comparativo entre assinaturas com renovação automática ativada versus desativada.
   
5. **Distribuição de Receita e Percentual**:
   - Percentual de assinaturas ativas versus inativas.

Estas análises têm como objetivo oferecer insights estratégicos e informar decisões baseadas em dados.

## Observação Importante

Este arquivo é meramente ilustrativo para demonstrar a funcionalidade do dashboard e análises associadas. Para garantir que haja ao menos um caso de cada tipo de status ou assinatura, a **data "atual" foi fixada no dia 20/03/2025**.