# Análise de Cancelamentos de Clientes

Este projeto realiza uma análise das principais causas de cancelamento de mais de 800 mil clientes de uma empresa. O objetivo é identificar padrões e fatores críticos que levam ao cancelamento, oferecendo suporte para a tomada de decisões estratégicas.

## Importância da Análise de Dados

A análise de dados é fundamental para qualquer empresa que busca compreender melhor seus clientes e suas operações. Com a crescente quantidade de dados disponíveis, a capacidade de extrair informações úteis e tomar decisões baseadas em dados pode ser um diferencial competitivo. O Python, com suas poderosas bibliotecas de análise, como `pandas`, `numpy`, e `plotly`, torna esse processo acessível e eficiente, permitindo uma análise profunda e visualização dos dados com facilidade.

## Resultados da Análise

Utilizando este código, foi possível identificar alguns fatores críticos associados ao cancelamento de contratos:

- **Contratos Mensais**: Todos os clientes com contratos mensais cancelaram. Isso sugere que a empresa deveria considerar oferecer descontos em planos anuais ou trimestrais para reter esses clientes.
- **Atendimento ao Cliente**: Clientes que precisaram ligar mais de 4 vezes para o call center acabaram cancelando. Isso indica a necessidade de melhorar a eficiência do atendimento, resolvendo problemas em no máximo 3 ligações.
- **Atrasos no Pagamento**: Clientes que atrasaram o pagamento por mais de 20 dias também cancelaram. Uma política de gestão de atrasos mais rígida, talvez resolvendo pendências em até 10 dias, pode ajudar a reduzir esses cancelamentos.

Após aplicar essas considerações, o código filtra os dados para verificar o impacto das ações propostas.

## Como o Python Facilita a Análise de Dados

O Python é uma das linguagens mais utilizadas para análise de dados devido à sua versatilidade e à riqueza de bibliotecas disponíveis:

- **Pandas**: Facilita o trabalho com grandes volumes de dados, permitindo manipulação e análise eficientes.
- **Numpy**: Oferece suporte para operações matemáticas e manipulação de arrays.
- **Plotly**: Permite a criação de gráficos interativos para visualização de dados.
- **Openpyxl**: Facilita o trabalho com arquivos Excel.
- **Nbformat e IPykernel**: Suportam o uso de notebooks Jupyter, onde você pode criar e executar o código de forma interativa.

## Executando o Projeto

Para executar este projeto, siga os passos abaixo:

1. Instale as bibliotecas necessárias:
    ```sh
    pip install pandas numpy openpyxl nbformat ipykernel plotly
    ```

2. Baixe os arquivos de dados disponíveis no Google Drive (https://drive.google.com/drive/folders/1GLX9gpm7uu9E9gw6Ivqjm_k-Qo6LW1XY?usp=drive_link&pli=1):
    - `cancelamentos_sample.csv`: Um arquivo menor para testes rápidos.
    - `cancelamentos.csv`: O arquivo completo com todas as informações para análise detalhada.

3. Coloque os arquivos baixados na pasta de análise do projeto.

4. Execute o código disponível no arquivo `analise_cancelamentos.ipynb` para analisar os dados e visualizar os resultados.

## Conclusão

Este projeto demonstra como a análise de dados pode revelar informações cruciais sobre o comportamento dos clientes, permitindo que a empresa tome medidas proativas para reduzir o cancelamento de contratos. 
