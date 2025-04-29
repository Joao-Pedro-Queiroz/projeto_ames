# Projeto Ames

## Descrição
Este repositório contém o _Projeto Ames_, cujo objetivo é prever o preço de venda de casas em Ames, Iowa (EUA) usando o _Ames Housing Dataset_. A abordagem inclui:

- Seleção e análise de variáveis (features) relevantes.
- Exploração de dados (_Exploratory Data Analysis_, EDA).
- Construção de pipelines de pré-processamento.
- Treinamento e avaliação de modelos de regressão (Linear, Ridge, Lasso, Random Forest).
- Otimização de hiperparâmetros com _RandomizedSearchCV_.

## Estrutura do Repositório
```
├── projeto_ames.ipynb     # Notebook principal do projeto
├── requirements.txt       # Lista de dependências Python
└── README.md              # Este arquivo
```

## Requisitos
- Python 3.7 ou superior
- Dependências (listadas em `requirements.txt`):
  - numpy
  - pandas
  - scikit-learn
  - seaborn
  - matplotlib
  - jupyter

## Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/projeto-ames.git
   cd projeto-ames
   ```
2. Crie e ative um ambiente virtual (opcional, mas recomendado):
   ```bash
   python -m venv venv
   source venv/bin/activate        # macOS/Linux
   venv\\Scripts\\activate       # Windows
   ```
3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Uso
1. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. No navegador, abra `notebooks/projeto_ames.ipynb`.
3. Execute as células na ordem, acompanhando a análise exploratória, pré-processamento, modelagem e avaliação.

## Principais Etapas
1. **Carregamento dos Dados:** Download e leitura do _Ames Dataset_.
2. **Entendimento do Negócio:** Descrição das variáveis e seu significado.
3. **Seleção de Features:** Escolha de 15 variáveis com maior relevância para `SalePrice`.
4. **EDA:** Gráficos e estatísticas para explorar relações entre variáveis.
5. **Pipeline de Pré-processamento:** Imputação, escalonamento e codificação de variáveis.
6. **Modelagem:** Treino de múltiplos modelos de regressão e busca de hiperparâmetros.
7. **Avaliação:** Cálculo de MSE e R² em validação cruzada e conjunto de teste.
8. **Conclusões:** Discussão dos resultados e sugestões de melhorias.

## Resultados
- O modelo que apresentou melhor desempenho foi o `<Nome do Modelo>` com R² de `<valor>` e MSE de `<valor>`.
- As variáveis mais influentes foram: `<variáveis>`.


## Autores
- João Pedro Queiroz
- Vitor Raia

