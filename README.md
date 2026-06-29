# Case NPS - Analista de Planejamento

Case analitico de NPS com foco em indicadores de atendimento, visoes por produto, supervisor, agente e exploracao de comentarios por nuvem de palavras.

## Objetivo

Transformar uma base de respostas de NPS em indicadores acionaveis para acompanhamento de experiencia do cliente e performance operacional.

## O que o projeto demonstra

- Leitura e tratamento de dados a partir de Excel.
- Analise de NPS por periodo, produto, supervisor e agente.
- Construção de visoes diaria e mensal.
- Segmentacao por quadrantes e dimensoes de negocio.
- Processamento textual simples com NLTK e WordCloud.
- Visualizacoes com Plotly, Matplotlib e WordCloud.

## Stack

- Python
- Pandas e NumPy
- Plotly e Matplotlib
- NLTK
- WordCloud
- Jupyter Notebook / Google Colab

## Arquivos

| Arquivo | Descricao |
| --- | --- |
| `Case_Nps_Planejamento_2.ipynb` | Notebook principal com tratamento, indicadores e analise textual. |

## Como executar

1. Abra o notebook no Google Colab ou Jupyter.
2. Disponibilize o arquivo Excel usado no case no caminho esperado ou ajuste a celula de leitura.
3. Execute as celulas em ordem, incluindo os downloads de recursos do NLTK quando necessario.

## Pontos fortes para portfólio

O projeto e relevante porque combina metricas de negocio, segmentacao operacional e analise textual. Ele mostra capacidade de transformar feedback de cliente em indicadores para gestao.

## Limitações atuais

- O dataset de entrada nao esta incluido nem documentado.
- O notebook depende de upload manual no Colab.
- Algumas regras de negocio, como quartis e quadrantes, precisam de definicao formal.
- Nao ha validacao automatica de campos, datas e categorias.
- A analise textual ainda e exploratoria e nao forma um pipeline reutilizavel.

## Próximas melhorias recomendadas

- Criar dicionario de dados e definicao formal das metricas de NPS.
- Separar calculos de indicadores em funcoes testaveis.
- Adicionar tratamento de texto reprodutivel com stopwords documentadas.
- Persistir tabelas finais em CSV ou Parquet.
- Criar dashboard ou relatorio executivo com principais alertas.
