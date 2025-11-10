# 📚 Insights Literários: Uma Análise de Dados de Livros com Python

Projeto de análise exploratória de dados desenvolvido em Python, utilizando um dataset público de **bestsellers** da Amazon.  
O objetivo foi extrair insights sobre autores, gêneros, avaliações e tendências de leitura.

---

## 👩‍💻 Autores
Gabriel Aguiar, Júlia Oliveira, Lucas de Arruda, Maria Clara Estevam e **Maria Luiza Pessoa**

---

## 🎯 Objetivo do Projeto
Explorar e compreender padrões de popularidade e avaliação em livros best-sellers:
- Quais autores têm mais livros acima da média de avaliação?
- Quais gêneros são mais populares entre os leitores?
- Existe relação entre ano de publicação e avaliação média?

---

## 🧩 Ferramentas e Bibliotecas
- **Python 3**
- **Pandas** — manipulação e limpeza de dados  
- **NumPy** — cálculos e operações vetoriais  
- **Matplotlib** e **Seaborn** — visualização e gráficos estatísticos  
- **Google Colab** — ambiente de execução  

---

## 📊 Etapas do Projeto
1. **Importação e inspeção do dataset**
   - `bestsellers with categories.csv`
   - 550 registros e 7 colunas (`Name`, `Author`, `User Rating`, `Reviews`, `Price`, `Year`, `Genre`)
2. **Limpeza e análise inicial**
   - Verificação de dados nulos e estatísticas descritivas
3. **Cálculo de médias e filtros**
   - Livros com avaliação acima da média global (`User Rating > média`)
4. **Visualizações**
   - Gráfico de pizza: distribuição de livros por gênero  
   - Gráfico de barras: livros acima da média por ano  
5. **Principais Insights**
   - O gênero **Fiction** domina o número de publicações com avaliações acima da média.  
   - Nem todos os autores com mais títulos são os mais bem avaliados.  
   - Alguns anos apresentam concentração de livros com notas mais altas, sugerindo tendências de mercado.

---

## 💡 Conclusão
A análise demonstrou como dados literários podem revelar padrões de preferência dos leitores e ajudar a entender o comportamento do mercado editorial.  
Este projeto foi essencial para praticar **análise exploratória, visualização e storytelling com dados**.

## 🔗 Not👉 [Acesse o notebook no Google Colab](https://colab.research.google.com/drive/1Rr6wuJaYZ6UkrbX5HpVQlQrEeaVaeSym?authuser=0)

---
