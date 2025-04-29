# 📊 Dashboard de Análise das Despesas do Estado de Pernambuco (2022 - 2024)

![Foto inicial](https://github.com/user-attachments/assets/20e689a0-1e41-4089-a944-892f8e7a091b)

# Sobre o projeto

Este projeto é um dashboard interativo desenvolvido com Streamlit para análise das despesas do Estado de Pernambuco, utilizando dados públicos disponibilizados pela SCGE. A visualização abrange a série histórica de 2022 a 2024 e tem como objetivo facilitar a compreensão do padrão de alocação dos recursos públicos ao longo dos anos.

## Descrição
O projeto visa expor um racional lógico das alocações das despesas realizadas pelo Governo de Pernambuco ao longo do tempo, analisando variações por ano, unidade gestora, função, subfunção e modalidade de empenho.

#  Funcionalidades 🔍
 - 📂 Upload de Arquivos: Leitura automática de múltiplos arquivos CSV.
 - 🧹 Tratamento de Dados: Limpeza e conversão de valores monetários.
 - 🎛️ Filtros Interativos (na barra lateral):
 - 📌 Indicadores Principais: 🏢 Quantidade de Secretarias | 🔄 Quantidade de Transações | 💰 Valor Total das Despesas

![Info](https://github.com/user-attachments/assets/86b07ef2-77cf-4115-95c3-a9efc80682ab)

## Tecnologias Utilizadas 👨‍💻:
 - Python
 - Streamlit
 - Pandas
 - Plotly / Matplotlib 
 - NumPy

## Instalação apos Download do projeto
No terminal (recomenda-se o uso do VSCode), execute:

Lembre-se de baixar a base e alterar o caminho de leitura do .Csv
Base: 🔗 https://dados.pe.gov.br/dataset/todas-despesas-detalhadas

```bash
## Executando o projeto

$ streamlit run app.py

## License

[MIT licensed](LICENSE).
