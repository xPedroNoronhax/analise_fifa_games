# 🎮 Análise de Dados da Franquia FIFA (EA Sports)

Este projeto analisa a franquia FIFA com base em um recorte específico do dataset `vgsales.csv`, que reúne dados de vendas globais de diversos jogos. Como jogadora da série FIFA, decidi investigar com mais profundidade apenas os títulos relacionados à franquia — explorando suas vendas, plataformas e evolução ao longo dos anos.

> ⚠️ **Aviso:** o arquivo `vgsales.csv` foi obtido no site Kaggle e os dados podem não representar informações 100% verídicas ou atualizadas. O objetivo do projeto é unicamente **praticar análise de dados** de forma exploratória e educativa.

---

## 🧠 Motivação

Ao explorar o dataset completo de jogos, percebi que poderia fazer uma análise mais rica e personalizada focando apenas na franquia FIFA. Assim, filtrei os dados exclusivamente dos títulos da série e aprofundei a investigação com gráficos e insights úteis para entender seu impacto na indústria dos games — tudo sob a perspectiva de alguém que jogou e acompanhou a evolução da franquia.

---

## 🧰 Ferramentas Utilizadas
- Python
- Pandas + pandasql
- Seaborn + Matplotlib
- Google Colab

---

## 📊 Principais Descobertas
- **FIFA 15** foi o jogo mais vendido da franquia. Isso possivelmente se deve ao fato de ter sido o primeiro título desenvolvido exclusivamente para a nova geração de consoles (PS4/Xbox One), despertando grande interesse nos fãs.
- A **popularidade** da série variou ao longo dos anos. Muitos fãs deixaram de comprar os lançamentos anuais devido à falta de inovação, já que os jogos traziam apenas atualizações de elenco e pequenas mudanças.
- A **maior concentração de vendas** ocorreu nos consoles da Sony (PlayStation).
- O número de lançamentos está fortemente ligado à **evolução dos consoles**.
- A **Europa** é a região com maior volume de vendas, o que pode ser explicado pela popularidade do futebol no continente e pelo papel central que ele exerce no cenário mundial.

---

## 📂 Estrutura do Projeto
- `fifa_analysis.ipynb`: notebook com o código e análises
- `vgsales.csv`: base de dados original com diversos jogos
- `fifa_games.csv`: subconjunto com dados apenas da franquia FIFA, extraído do `vgsales.csv`
- `fifa_graficos.pdf`: visualizações geradas no projeto

---

## 🚀 Como Executar
1. Clone o repositório:
```bash
git clone https://github.com/xPedroNoronhax/fifa-analysis.git
cd fifa-analysis
