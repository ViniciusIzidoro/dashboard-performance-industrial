# Análise de Performance Industrial (Excel/BI)

## 🎯 Objetivo do Projeto
Este projeto visa analisar a eficiência produtiva, o volume de refugo e o impacto de paradas em uma planta industrial, utilizando um dashboard interativo para suporte à tomada de decisão.

## 🛠 Tecnologias e Ferramentas
*   **Excel:** Ferramenta principal para modelagem e visualização.
*   **Power Query:** Utilizado para ETL (Extração, Transformação e Carga), normalização de bases e tratativas de tabelas.
*   **Power Pivot/Modelagem:** Estruturação de **Star Schema** (tabelas fato e dimensão) para garantir a integridade dos dados.
*   **Lógica Analítica e Fórmulas:** 
    *   Criação de medidas avançadas utilizando **DAX**.
    *   Uso estratégico de funções **SOMASE** (para cálculos condicionais robustos) e **SEERRO** (para tratamento de exceções e limpeza visual de indicadores).
    *   Implementação de *INFODADOSTABELADINÂMICA* para KPIs dinâmicos.

## ⚙️ Principais Desafios Técnicos
*   **Normalização de Dados:** Conversão de bases operacionais em um modelo relacional (Star Schema) para evitar redundância e erros.
*   **Interatividade:** Implementação de KPIs que respondem automaticamente à segmentação de dados.
*   **Automação:** Criação de um fluxo de dados onde novas inserções na base são refletidas no dashboard com atualização das conexões.

## 📈 Dashboard
![Visão Geral](Painel%20industrial%202026.PNG)
![Exemplo Interativo](Painel%20industrial%202026%20-%20interativo.PNG)
![Estrutura do Modelo](Relações.PNG)

## 💡 O que este projeto demonstra?
*   Capacidade de transformar dados brutos em insights estratégicos.
*   Domínio de técnicas de modelagem que vão além de planilhas simples.
*   Visão de negócio voltada para a melhoria de processos e redução de desperdícios.

## 🚀 Como utilizar
1. Faça o download do arquivo `Dashboard_Performance_Industrial_V1.xlsx`.
2. Habilite o conteúdo ao abrir no Excel.
3. Utilize os filtros de "Linha" para explorar os dados.
