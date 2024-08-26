<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Monthly Pattern Analyzer

## Description

The **Monthly Pattern Analyzer** is a project designed to identify and analyze performance patterns of stocks based on the months of the year. This algorithm examines historical data to determine if there are recurring trends or behaviors in specific months, such as January, February, March, and so on. The goal is to identify months that exhibit higher gains or losses in stock performance.

## Features

- **Data Import**: Retrieves historical market data using the MetaTrader5 library.
- **Pattern Analysis**: Assesses stock performance for each month of the year.
- **Outlier Handling**: Filters outliers to enhance the accuracy of monthly pattern analysis.
- **Visualization and Export**: Consolidates results into a DataFrame and exports them to an Excel file for detailed analysis and review.

## Workflow

1. **Import Libraries**: Load the necessary libraries for data processing and analysis.
2. **Create Asset List**: Define the assets to be analyzed, which may include specific stocks or indices.
3. **Set Start Date**: Establish the start date for analyzing historical data.
4. **Calculate Results**: Implements a function to:
   - Initialize the MetaTrader5 connection.
   - Retrieve historical data for the specified time periods.
   - Calculate performance metrics for each month of the year.
   - Remove outliers for more accurate pattern analysis.
   - Aggregate data by month and calculate relevant statistics.
5. **Process Data**: Execute the calculation function for all specified assets and time periods, consolidating the results into a DataFrame.
6. **Export Results**: Export the analyzed data to an Excel file for easy review and detailed analysis.

## Usage

1. **Install Dependencies**: Ensure all necessary libraries are installed.
2. **Define Asset List**: Configure the list of assets for analysis, including specific stocks or indices.
3. **Run the Script**: Execute the script to analyze stock performance by month.
4. **Review and Export Results**: Results will be consolidated and exported to an Excel file for detailed review and analysis.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to add new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).



# Analisador de Padrões Mensais

## Descrição

O **Analisador de Padrões Mensais** é um projeto desenvolvido para identificar e analisar padrões de desempenho das ações com base nos meses do ano. Este algoritmo examina dados históricos para determinar se há tendências ou comportamentos recorrentes em determinados meses, como janeiro, fevereiro, março, e assim por diante. O objetivo é identificar meses que apresentam maiores altas ou baixas no desempenho das ações.

## Funcionalidades

- **Importação de Dados**: Obtém dados históricos do mercado usando a biblioteca MetaTrader5.
- **Análise de Padrões**: Avalia o desempenho das ações para cada mês do ano.
- **Tratamento de Outliers**: Filtra outliers para melhorar a precisão da análise dos padrões mensais.
- **Visualização e Exportação**: Consolida os resultados em um DataFrame e exporta para um arquivo Excel para análise e revisão detalhadas.

## Fluxo de Trabalho

1. **Importar Bibliotecas**: Carrega as bibliotecas necessárias para processamento e análise de dados.
2. **Criar Lista de Ativos**: Define os ativos que serão analisados, podendo incluir ações específicas ou índices.
3. **Definir Data Inicial**: Estabelece a data inicial para análise dos dados históricos.
4. **Calcular Resultados**: Implementa uma função para:
   - Inicializar a conexão com o MetaTrader5.
   - Recuperar dados históricos para os períodos de tempo especificados.
   - Calcular métricas de desempenho para cada mês do ano.
   - Remover outliers para uma análise mais precisa dos padrões.
   - Agregar dados por mês e calcular estatísticas relevantes.
5. **Processar Dados**: Executa a função de cálculo para todos os ativos e períodos de tempo definidos, consolidando os resultados em um DataFrame.
6. **Exportar Resultados**: Exporta os dados analisados para um arquivo Excel para fácil revisão e análise.

## Uso

1. **Instalar Dependências**: Certifique-se de que todas as bibliotecas necessárias estejam instaladas.
2. **Definir Lista de Ativos**: Configure a lista de ativos para análise, incluindo ações ou índices específicos.
3. **Executar o Código**: Execute o script para analisar o desempenho das ações por mês.
4. **Visualizar e Exportar Resultados**: Os resultados serão consolidados e exportados para um arquivo Excel para revisão e análise detalhadas.

## Contribuições

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou quiser adicionar novos recursos, sinta-se à vontade para abrir um problema ou enviar um pull request.

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).
