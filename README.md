# Análise de Mercado de Jogos na Steam

## Grupo:
- Filipy Tavares dos Santos
- Luiz Otavio Machado Seles
- Naum Calebe Felix Sarti

---

A base de dados encontra-se [aqui](https://www.kaggle.com/datasets/artermiloff/steam-games-dataset) ou na aba 'Releases' deste repositório.

---

## Sobre o Projeto
Este projeto apresenta uma pesquisa de mercado focada no desenvolvimento e desempenho de jogos na plataforma Steam. O objetivo principal é segmentar o mercado e identificar padrões de sucesso. A análise utiliza técnicas de **agrupamento (*clustering*)** para traçar perfis comerciais dos jogos e **regras de associação** para entender como a identidade técnica (gêneros e *tags*) impacta as avaliações, retenção e vendas.

## Tecnologias Utilizadas
* **Linguagem:** Python
* **Processamento:** Pandas, Scikit-learn (PCA, StandardScaler)
* **Agrupamento:** K-Means
* **Associação:** Mlxtend (Apriori, TransactionEncoder)
* **Visualização:** Matplotlib, Seaborn

## Metodologia
O projeto divide-se em duas abordagens complementares de mineração de dados:
1. **Agrupamento (Clustering):** Limpeza dos dados de mercado, redução de dimensionalidade (PCA) e uso de algoritmos (como K-Means) para dividir os jogos em perfis baseados em volume, popularidade e monetização.
2. **Regras de Associação:** Uso do algoritmo **Apriori** para tratar os gêneros e *tags* de cada jogo como um "cesto de compras". Isso gera regras lógicas de causa e consequência (ex: se o jogo possui as características A e B, a chance de atingir a meta C é de X%).

## Principais Áreas de Pesquisa
Os grupos e padrões descobertos foram organizados para orientar desenvolvedores e estúdios:
* **Segmentação de Mercado:** Divisão do catálogo, separando grandes sucessos do volume massivo de jogos comuns.
* **Sinergias de Desenvolvimento:** Quais mecânicas funcionam melhor quando combinadas.
* **Poder de Precificação e Ecossistema Gratuito:** O que justifica cobrar valores *Premium* ou adotar o modelo *Free-to-Play*.
* **Receita da Aclamação e Engajamento:** Fatores de design que maximizam a satisfação, retenção e potencial viral.

## Conclusão
O estudo demonstra que o sucesso comercial na plataforma não ocorre por acaso. A união do agrupamento vetorial com as regras de associação comprova que a viabilidade de um jogo depende de um alinhamento rigoroso entre a estrutura mecânica escolhida, o público-alvo pretendido e o modelo de negócios adotado.
