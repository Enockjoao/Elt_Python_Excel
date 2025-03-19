# Validador de Dados de Campanhas

Este projeto é uma aplicação completa que lê um arquivo CSV contendo dados de campanhas, valida cada linha usando um modelo definido com Pydantic, e exibe os resultados em uma interface web utilizando Streamlit.

## Estrutura do Projeto

- **src/aplicacao_completa.py**: Script principal que lê o arquivo CSV, valida os dados e exibe os resultados na interface Streamlit.
- **src/validador.py**: Define o modelo `PlanilhaVendas` usando Pydantic para validação dos dados.
- **src/main.py**: Gera um relatório de perfil dos dados usando `ydata_profiling`.
- **data/**: Diretório onde o arquivo `data.csv` deve ser colocado.
- **output/**: Diretório onde o relatório de perfil dos dados será salvo.

## Funcionalidades

- **Validação de Dados**: Valida cada linha do CSV usando o modelo `PlanilhaVendas`.
- **Interface Web**: Exibe os dados validados e os erros de validação em uma interface web interativa.
- **Download de Dados Validados**: Permite o download dos dados validados em formato CSV.
- **Relatório de Perfil**: Gera um relatório de perfil dos dados para análise exploratória.

## Requisitos

- Python 3.7 ou superior
- Pandas
- Streamlit
- Pydantic
- ydata_profiling

## Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. **Executar a Aplicação Streamlit**:
   - Coloque o arquivo `data.csv` no diretório `data/`.
   - Execute o aplicativo:
     ```bash
     streamlit run src/aplicacao_completa.py
     ```

2. **Gerar Relatório de Perfil**:
   - Execute o script para gerar o relatório:
     ```bash
     python src/main.py
     ```
   - O relatório será salvo em `output/output.html`.

