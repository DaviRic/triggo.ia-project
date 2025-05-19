# 📊 Análise de Dados do E-commerce Brasileiro - Desafio Técnico Triggo.ia

Este projeto foi desenvolvido como parte do desafio técnico da Triggo.ia para vagas de Engenharia de Dados e DataOps. Utilizamos o dataset público da Olist, disponível no Kaggle, para realizar uma análise completa, desde a preparação dos dados até a construção de dashboards interativos.

---

## 🧰 Tecnologias e Bibliotecas Utilizadas

- Python 3.10+
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- JupyterLab (ou VS Code com a extensão do Jupyter)

---

## ⚙️ Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/DaviRic/triggo.ia-project.git
   cd triggo.ia-project

2. **Crie um ambiente virtual:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   venv\Scripts\activate     # Windows

3. **Instale as dependências:**
   ```bash
   pip install -r requirements.txt

4. **Inicie o JupyterLab**
   ```bash
   jupyter lab
   ```
   4.1 Outra opção é abrir o Jupyter pelo **VS Code**
      - Instale a extensão: ``Jupyter``
5. **Abra o notebook princial**:
   - Navegue até a pasta ``notebooks/`` e abra o arquivo principal do projeto (o arquivo ``main.ipynb``).

## 📁 Estrutura do Projeto
```
├── data/                # Arquivos CSV do dataset original
├── notebooks/           # Notebook principal com toda a análise
    └── main.ipynb       # Notebook com todas as análises e gráficos
├── requirements.txt     # Lista de dependências do projeto
└── README.md            # Instruções e explicações do projeto
```

## 📌 Objetivos do Projeto
- Explorar e preparar os dados do e-commerce brasileiro
- Realizar análise exploratória e identificação de padrões
- Clusterizar os clientes como base em comportamento de compra
- Avaliar a correlação entre a avaliação dos clientes e variáveis logísticas
- Criar dashboards e visualizações interativas para apoiar decisões de negócio


## 📈 Principais Resultados
### Análise de satisfação
- **Tempo de Entrega x Avaliação**: Correlação negativa moderada (-0.30). Quanto maior o tempo de entrega, menor tende a ser a nota de avaliação.
- **Valor do Pedido x Avaliação**: Correlação praticamente nula (~0.00).
- **Frete x Avaliação**: Correlação fraca negativa (-0.03), indicando que fretes mais altos tendem a levemente reduzir a nota dada pelo cliente.

### Clusteriazação
- Clientes foram agrupados em 4 clusters no frete médio, tempo de entrega e categorias mais compradas.
- ``Cluster 0``:
   - Número de clientes: 44835
   - Frete médio: R$20,09
   - Tempo médio de entrega: 10,97 dias
   - Destaque para produtos de: Beleza e Saúde e Cama, mesa e banho

- ``Cluster 1``:
   - Número de clientes: 37606
   - Frete médio: R$13,50
   - Tempo médio de entrega: 6,83 dias
   - Destaque para produtos de: Cama, mesa e banho e Beleza e Saúde

- ``Cluster 2``:
   - Número de clientes: 4027
   - Frete médio: R$75,76
   - Tempo médio de entrega: 14,66 dias
   - Destaque para produtos de: Moveis e Decoração e Utilidade Domésticas

- ``Cluster 3``:
   - Número de clientes: 9988
   - Frete médio: R$23,02
   - Tempo médio de entrega: 31,55 dias
   - Destaque para produtos de: Cama, mesa e banho e Beleza e Saúde

### Dashboards Criados
1. Evolução das vendas ao longo do tempo
   - Gráfico interativo com filtros por estado 
2. Mapa de calor por estado
   - Visualização da concentração de pedidos por região do Brasil
3. Avaliação vs tempo de entrega
   - Plot dos gráficos que ilustram a relação entre tempo de entrega e review

## 🧠 Conclusão
O projeto demonstrou como a análise de dados pode fornecer insights de valor sobre a logística, o comportamento do consumidor, visões para tomadas de decisões de estragégias de marketing, etc. Os dashboards permitem uma visualização dos dados e auxiliam na tomada de decisão orientada por dados.

## ✍️ Candidato
### Davi Cruvel
[LinkedIn](https://www.linkedin.com/in/davicruvel/)

