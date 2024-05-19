# Projeto de Estatística com python: Quais Dívidas Valem o Esforço do Banco

Este projeto faz parte da coleção do site DataCamp. Posto esse projeto aqui como forma de compartilhar o meu estagio de desenvolvimento.
O projeto de estatística segue um processo de nove passos, enfatizando as análises estatísticas realizadas em cada etapa.

## 1. Regressão Descontínua: Recuperação Bancária

Nesta etapa, exploramos a estratégia de recuperação de dívidas de um banco após elas serem declaradas irrecuperáveis. Avaliamos se a implementação de diferentes estratégias de recuperação, com base no valor esperado de recuperação, resultou em um aumento significativo na recuperação de dívidas.

## 2. Análise Exploratória de Dados Gráficos

Aqui, analisamos graficamente os dados para entender como diferentes estratégias de recuperação estão associadas aos valores esperados de recuperação das dívidas.

## 3. Teste Estatístico: Idade vs. Valor de Recuperação Esperado

Realizamos um teste estatístico para determinar se há uma diferença significativa na idade dos clientes acima e abaixo do limite de valor esperado de recuperação de \$1000.

## 4. Teste Estatístico: Sexo vs. Valor de Recuperação Esperado

Analisamos estatisticamente se há uma diferença na distribuição de sexo entre os clientes acima e abaixo do limite de valor esperado de recuperação de \$1000.

## 5. Análise Gráfica Exploratória: Valor de Recuperação

Exploramos graficamente a relação entre o valor esperado de recuperação e o valor real de recuperação das dívidas para determinar se há uma descontinuidade em torno do limite de \$1000.

## 6. Análise Estatística: Valor de Recuperação

Realizamos testes estatísticos para verificar se há uma descontinuidade estatisticamente significativa no valor real de recuperação das dívidas acima e abaixo do limite de \$1000.

## 7. Modelagem de Regressão: Sem Limiar

Construímos um modelo de regressão para prever o valor real de recuperação com base no valor esperado de recuperação, sem considerar o limiar de \$1000.

## 8. Modelagem de Regressão: Adicionando o Verdadeiro Limiar

Adicionamos o limiar de \$1000 ao modelo de regressão para avaliar o impacto adicional na recuperação de dívidas devido à estratégia de recuperação mais alta.

## 9. Modelagem de Regressão: Ajustando a Janela

Ajustamos a faixa de valores esperados de recuperação para verificar se os resultados obtidos são consistentes, independentemente da faixa selecionada.

Este processo fornece uma estrutura abrangente para conduzir uma análise estatística completa em um projeto de recuperação bancária, permitindo a identificação de insights importantes e a tomada de decisões fundamentadas.

## Como Executar

### Pré-requisitos
- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib

### Passos

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/lucas-fonzo/Quais-Dividas-Valem-o-Esforco-do-Banco.git
   ```

2. **Navegue até o diretório do projeto:**
   ```bash
   cd Quais-Dividas-Valem-o-Esforco-do-Banco
   ```

3. **Instale as dependências:**
   ```bash
   pip install pandas numpy matplotlib
   ```

4. **Execute o Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

5. **Abra o arquivo `Quais-Dividas-Valem-o-Esforco-do-Banco.ipynb` no navegador que foi aberto.**

6. **Siga as instruções dentro do notebook para executar cada célula e analisar os resultados.**

Com esses passos, você poderá executar o projeto localmente em seu ambiente Jupyter Notebook. Se encontrar algum problema durante a execução, verifique se todas as dependências estão instaladas corretamente e se você está executando as células na ordem adequada.
