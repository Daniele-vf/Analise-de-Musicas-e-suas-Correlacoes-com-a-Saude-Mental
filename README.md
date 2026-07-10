# Análise Exploratória: Hábitos Musicais e Saúde Mental 

Projeto prático desenvolvido como trabalho de conclusão para a disciplina de **Introdução à Ciência de Dados** na pós-graduação da **UTFPR** (Universidade Tecnológica do Paraná).

O objetivo deste projeto foi investigar como os hábitos de consumo musical de diferentes indivíduos se correlacionam com seus níveis autoavaliados de condições de saúde mental, como Ansiedade, Depressão, Insônia e TOC.

---

## Objetivo do Projeto

Através do dataset público *Music & Mental Health Survey Results*, busquei responder a perguntas de pesquisa como:
* Determinados gêneros musicais estão associados a níveis mais altos ou baixos de ansiedade, depressão, insônia e TOC?
* Pessoas que percebem uma melhora da saúde mental com o efeito da música possuem um quadro condizente?

---

## Metodologia e Processo KDD
Para transformar dados brutos em conhecimento, apliquei as etapas do processo **KDD (Knowledge Discovery in Databases)** utilizando Python no próprio Kaggle:

1. **Seleção e Compreensão dos Dados:** Filtro e mapeamento das variáveis demográficas, hábitos musicais e escalas de saúde mental.
2. **Pré-processamento (Limpeza):** Identificação e tratamento de valores nulos (NaN) e remoção de dados inconsistentes para garantir a qualidade da análise.
3. **Transformação:** Conversão e adequação de variáveis categóricas e numéricas para viabilizar as plotagens estatísticas.
4. **Data Mining & Visualização:** Geração de gráficos de distribuição, correlação e cruzamento de dados para identificar padrões e tendências.

---

## Tecnologias e Abordagem Utilizada
* **Linguagem:** Python
* **Bibliotecas:** Pandas, Matplotlib e Seaborn.
* **Abordagem Dev-AI:** O projeto foi desenvolvido utilizando ferramentas de **Inteligência Artificial Generativa** como copiloto para otimização da sintaxe do código, tratamento de dados e refinamento dos gráficos, sob minha curadoria lógica, validação de regras analíticas e interpretação de negócios.

---

## Principais Insights Obtidos
* Identifiquei que dentre os gêneros citados e autoanálise sobre a questão da saúde mental, o gênero **"LoFi"** é aquele que se destaca em pessoas com maior gravidade de sintomas nas questões mentais. O **"Folk"** é o gênero com maior índice de ansiedade e o **"Gospel"** o com o menor índice de gravidade, somando os quatro transtornos mentais.
* O efeito da música causa melhora ou piora de acordo com a gravidade dos transtornos mentais: os que possuem baixo índice realmente apresentam uma melhora significativa; os que já possuem um certo agravamento apresentam uma melhora subjetiva e os que relatam a piora dos sintomas ao ouvirem música de fato têm um quadro mais agravado.

---

## Aprendizados e Conclusões
Este projeto foi fundamental para iniciar meu entendimento no ciclo inicial de um projeto de dados. Mais do que escrever o código, o grande desafio e aprendizado foi formular as hipóteses corretas, limpar os dados com rigor analítico e traduzir gráficos estatísticos em insights compreensíveis sobre o comportamento humano.

---

## Links Úteis
* Dataset original: [Music & Mental Health Survey Results (Kaggle)](https://www.kaggle.com/datasets/catherinerasgaitis/mxmh-survey-results)
