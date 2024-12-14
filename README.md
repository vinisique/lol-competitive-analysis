# Análise Competitiva do Cenário de eSports - League of Legends (LoL)

Este é um projeto de análise de dados que explora o cenário competitivo do jogo League of Legends (LoL). Ele demonstra aplicações de técnicas de Data Science e Machine Learning para extração de insights sobre o comportamento de equipes e jogadores no competitivo.

## Estrutura do Projeto

- **LoL-Competitive-Analysis.ipynb**: Notebook principal contendo a análise exploratória, modelagem e visualização de dados.
- **bans.csv**: Informações sobre banimentos de campeões durante as partidas.
- **kills.csv**: Dados de eliminações por jogo e jogador.
- **matchinfo.csv**: Informações gerais das partidas, incluindo equipes e resultados.
- **monsters.csv**: Estatísticas sobre monstros neutros eliminados.
- **structures.csv**: Dados sobre estruturas destruídas (torres e inibidores).
- **settings.json**: Configurações do ambiente de trabalho.

## Objetivo

Explorar e analisar dados do cenário competitivo de LoL para identificar padrões, gerar insights e treinar um modelo de previsão de resultados de partidas, enfatizando habilidades como:

- Análise exploratória de dados
- Visualização e interpretação de resultados
- Modelagem preditiva utilizando Machine Learning
- Trabalho em equipe e gerenciamento de projetos

## Tecnologias e Bibliotecas Utilizadas

- Python (Jupyter Notebook)
- Pandas, NumPy, Matplotlib, Seaborn (Análise e visualização)
- Scikit-learn (Modelagem preditiva)

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/vinisique/lol-competitive-analysis.git
   ```

2. Instale as dependências necessárias:
   ```bash
   pip install -r requirements.txt
   ```

3. Baixe os arquivos CSV e coloque-os na mesma pasta do notebook (se aplicável, inclua o link para download dos datasets originais).

4. Abra o notebook:
   ```bash
   jupyter notebook LoL-Competitive-Analysis.ipynb
   ```

5. Execute as células do notebook sequencialmente.

## Análise Exploratória e Modelagem

Durante o projeto, realizamos as seguintes etapas:

1. **Importação e limpeza de dados:**
   - Carregamos datasets sobre banimentos, eliminações, monstros, estruturas e informações gerais das partidas.

2. **Análise exploratória:**
   - Criamos histogramas e gráficos para entender distribuições e correlações.

3. **Modelagem preditiva:**
   - Treinamos modelos de Machine Learning para prever resultados de partidas.
   - Avaliamos a performance usando cross-validation e matriz de confusão.

## Insights Desenvolvidos

- Campeões com altas taxas de banimento, como "Zac", indicam estratégias específicas baseadas na visão do mapa.
- O lado do campo influencia significativamente a performance em certos aspectos, como a eliminação de monstros neutros.
- Identificamos padrões únicos que ajudam equipes a adaptar suas estratégias para melhorar o desempenho.

## Resultados Visuais

Inclua aqui algumas capturas de tela ou links para visualizações relevantes do projeto, como:

- Gráficos de distribuição de taxa de vitórias
- Visualização de correlações entre banimentos e resultados

## Contribuições e Aprendizados

- Desenvolvimento de habilidades analíticas e técnicas.
- Melhor compreensão de ferramentas de visualização e modelagem.
- Colaboração eficaz em um ambiente de prazos curtos.

## Licença

Este projeto é de uso livre para fins educacionais. Para outros usos, entre em contato pelo [GitHub](https://github.com/vinisique).

---
Se tiver sugestões ou dúvidas, fique à vontade para abrir uma issue ou enviar um pull request.

