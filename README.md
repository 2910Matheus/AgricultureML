# AgricultureML🌾

Este repositório contém uma análise exploratória, descritiva e construção de modelos preditivos utilizando um dataset com informações de condições de solo e clima, como parte da atividade prática do capítulo 14 da instituição FIAP. O objetivo é prever a melhor cultura agrícola a ser plantada com base nas características analisadas.

## 📂 Estrutura do Projeto

```
.
├── data/
│   └── Atividade_Cap_14_produtos_agricolas.csv  # Dataset utilizado na análise
├── notebooks/
│   └── AgricultureML.ipynb  # Notebook principal com as análises e modelos
├── README.md  # Documentação do projeto
└── requirements.txt
```

## 📝 Objetivo

1. **Análise exploratória e descritiva dos dados**:
   - Identificar padrões e tendências.
   - Construir no mínimo cinco gráficos informativos.

2. **Perfil ideal de plantio**:
   - Determinar condições ideais de solo e clima para diferentes culturas.

3. **Modelagem preditiva**:
   - Construir e avaliar cinco modelos preditivos diferentes.
   - Comparar a performance dos modelos.

## 📊 Dataset

O dataset contém as seguintes variáveis:
- **N**: Quantidade de nitrogênio no solo.
- **P**: Quantidade de fósforo no solo.
- **K**: Quantidade de potássio no solo.
- **temperature**: Temperatura média (°C).
- **humidity**: Umidade média do ar.
- **pH**: pH do solo.
- **rainfall**: Precipitação (mm).
- **label**: Tipo de cultura plantada.

O dataset está disponível na pasta `data/`.

## 🔧 Tecnologias Utilizadas

- Python
- Bibliotecas:
  - Pandas
  - NumPy
  - Matplotlib/Seaborn
  - Scikit-learn

## 📈 Gráficos e Análises

Os gráficos incluem:
1. Distribuição das variáveis numéricas.
2. Correlação entre variáveis climáticas e condições de solo.
3. Gráficos de dispersão entre variáveis.
4. Comparação dos tipos de cultura com o perfil ideal.
5. Importância das variáveis nos modelos preditivos.

## 🤖 Modelos Preditivos

Os seguintes algoritmos foram utilizados para prever o tipo de cultura agrícola:
1. Decision Tree
2. Random Forest
3. K-Nearest Neighbors
4. Support Vector Machine
5. Logistic Regression

### Métricas de Avaliação
- Accuracy
- Precision
- Recall
- F1-Score

## 🚀 Como Utilizar

1. Clone este repositório:
   ```
   git clone https://github.com/seuusuario/seuprojeto.git
   ```
2. Instale as dependências necessárias:
   ```
   pip install -r requirements.txt
   ```
3. Execute o Jupyter Notebook:
   ```
   jupyter notebook notebooks/AgricultureML.ipynb
   ```

## 📌 Contribuições

Contribuições são bem-vindas! Siga os passos:
1. Fork o projeto.
2. Crie uma branch para a nova feature:
   ```
   git checkout -b minha-nova-feature
   ```
3. Commit suas mudanças:
   ```
   git commit -m "Adiciona nova feature"
   ```
4. Faça um push para a branch:
   ```
   git push origin minha-nova-feature
   ```
5. Abra um Pull Request.

## 📜 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
