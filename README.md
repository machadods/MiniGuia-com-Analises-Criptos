📊MiniGuia de Análise de Criptomoedas

Google Colab · PDFs · IA · Áudio · Relatórios

Este repositório contém um notebook em Python executado no Google Colab para estudo estruturado de criptomoedas, combinando:

leitura e análise crítica de PDFs

uso de IA como assistente de interpretação

geração de slides, áudios e relatório final

O foco é aprendizado, análise conceitual e organização do conhecimento, não investimento.

🧠 O que este projeto faz

O notebook executa três funções principais:

🔹 1. Análise de PDFs sobre criptomoedas

Conecta ao Google Drive para acessar livros e materiais em PDF

Extrai texto dos documentos com pdfplumber

Exibe trechos selecionados para análise

Guia a leitura por perguntas estruturadas:

tese central

tipo de texto (introdutório, técnico ou ideológico)

premissas implícitas

o que está obsoleto em 2026

o que permanece válido em 2026

As respostas ficam organizadas em um dicionário único (respostas).

🔹 2. Consolidação do conhecimento com IA

A IA integrada ao Colab é usada apenas como assistente, com base nos trechos exibidos

Gera:

resumos didáticos

glossários

prompts prontos para slides educacionais

⚠️ A IA não inventa conteúdo externo e não substitui leitura crítica.

🔹 3. Geração de artefatos finais

A partir das respostas consolidadas, o notebook gera automaticamente:

📊 Prompts de slides para apresentações

🎧 Áudios narrados com perguntas e respostas (Q&A)

📄 PDF final estruturado, contendo toda a análise por documento

Esses materiais podem ser usados para estudo, aulas ou revisão.

⚙️ Tecnologias utilizadas

Python

Google Colab

pdfplumber

gTTS (Text-to-Speech)

reportlab (geração de PDF)

pandas / numpy / matplotlib (base analítica)

⚠️ Limitações explícitas

Não faz recomendações de investimento

Não prevê preços automaticamente

A qualidade da análise depende do conteúdo dos PDFs

Textos ideológicos exigem leitura crítica humana

🎯 Objetivo do projeto

Transformar leitura passiva de PDFs em compreensão ativa e estruturada, usando IA como ferramenta — não como autoridade.

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
