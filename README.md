📊 MiniGuia de Análise de Criptomoedas — Usando Colab + Análise Descritiva e Preditiva de Criptos

Este repositório contém um notebook completo em Python/Google Colab para coletar, analisar, visualizar e gerar relatórios de criptomoedas, combinando análise descritiva, visual e preditiva. Ele também inclui um mecanismo de leitura de PDFs sobre criptomoedas para gerar resumos, glossários, perguntas de revisão e áudios automaticamente.

➡️ Versão no Colab:
https://colab.research.google.com/drive/1X7hP890J5YbzyB0R5jesX3lLfTiLc3z-?usp=sharing

🧠 O que este projeto faz

Este notebook faz três grandes coisas:

🔹 1. Análise de PDFs sobre criptomoedas

Conecta ao Google Drive para acessar PDFs didáticos.

Lê texto dos documentos com pdfplumber.

Gera automaticamente resumos, glossários, perguntas de revisão.

Gera prompts para slides a partir dos resumos.

Converte os resumos em áudios narrados (usando edge-tts).

📈 2. Coleta de dados de mercado cripto

Utiliza a API pública do CoinGecko para:

✔ Obter preços atuais de uma lista de criptomoedas em USD e BRL.
✔ Obter histórico de preços dos últimos 180 dias por cripto.

Criptos analisadas (por padrão):

["bitcoin", "ethereum", "solana", "cardano", "dogecoin",
 "shiba-inu", "avalanche-2", "chainlink", "polkadot",
 "the-open-network", "render-token"]

📊 3. Análise Descritiva, Visual e Preditiva

O notebook calcula e mostra:

📉 Estatísticas descritivas dos dados históricos.

📊 Volatilidade anualizada (risco).

📉 Drawdown histórico e máximo (perdas desde picos).

📈 Retorno acumulado por cripto.

📈 Gráficos de tendências (histórico de preços).

📈 Médias Móveis (MA7 & MA30) para capturar tendência.

🔁 Retornos diários e distribuição (boxplot).

🔗 Heatmaps de correlação entre retornos.

📈 Comparação normalizada de performance de todas as criptos.

📊 Scatter Risco x Retorno (comparando risco vs performance).

📉 Drawdown detalhado por cripto ao longo do tempo.

🔍 4. Modelo Preditivo via Prophet

Gera previsão de preço de 30 dias para Bitcoin (exemplo).

Produz gráficos interativos com Plotly.

Permite expandir o modelo para outras moedas com ajustes.

📄 5. Geração de Relatório em PDF

Um relatório final é automaticamente gerado com:

✔ Tabelas resumidas
✔ Gráficos e análises visuais
✔ Notas interpretativas de significado e valor de cada métrica
✔ Comparações e rankings de performance
✔ Heatmaps, scatter de risco/retorno, drawdown detalhado

O PDF é ideal para apresentações, estudo ou relatórios de desempenho.

🚀 Como usar
🧩 Requisitos

O notebook foi feito para rodar no Google Colab com suporte a:

Python 3.x

Acesso ao Google Drive (para PDFs)

Conexão à internet (para CoinGecko e TTS)
