# 📊 Validador de Dados de Campanhas

Este projeto é uma aplicação completa que processa um arquivo CSV contendo dados de campanhas, valida cada linha usando Pydantic e exibe os resultados em uma interface interativa com Streamlit.

## 🚀 Estrutura do Projeto

📂 **src/**
- `aplicacao_completa.py` → Script principal que lê o arquivo CSV, valida os dados e exibe os resultados na interface Streamlit.
- `validador.py` → Define o modelo `PlanilhaVendas` utilizando Pydantic para validar os dados.
- `main.py` → Gera um relatório de perfil dos dados usando `ydata_profiling`.

📂 **data/** → Diretório onde o arquivo `data.csv` deve ser colocado.
📂 **output/** → Diretório onde o relatório de perfil dos dados será salvo.

## ✨ Funcionalidades

✅ **Validação Automática**: Cada linha do CSV é validada com `PlanilhaVendas`.
✅ **Interface Web Interativa**: Exibe os dados validados e os erros de validação em Streamlit.
✅ **Download de Dados Validados**: Permite exportar os dados tratados em formato CSV.
✅ **Relatório de Perfil dos Dados**: Geração automática de relatórios detalhados para análise exploratória.

## 🔧 Requisitos

- Python 3.7 ou superior
- Pandas
- Streamlit
- Pydantic
- ydata_profiling

## ⚡ Instalação

1️⃣ Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2️⃣ Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Uso

### 1️⃣ Executar a Aplicação Streamlit
- Certifique-se de que `data.csv` está no diretório `data/`.
- Execute o aplicativo:
  ```bash
  streamlit run src/aplicacao_completa.py
  ```

### 2️⃣ Gerar Relatório de Perfil
- Execute o script:
  ```bash
  python src/main.py
  ```
- O relatório será salvo em `output/output.html`.

## 🤝 Contribuição

Contribuições são bem-vindas! Caso tenha sugestões, abra uma issue ou envie um pull request. 


## 📬 Contato

Para mais informações, entre em contato com [joaovictorenock@gmail.com](mailto:joaovictorenock@gmail.com).
