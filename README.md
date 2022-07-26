# Repositório de Projetos e Ideias


1. [Identificação de processos de gentrificação a partir da análise de dados urbanos.](#identificação-de-processos-de-gentrificação-a-partir-da-análise-de-dados-urbanos)
2. [Identificar candidatos mais mencionados (positivamente e negativamente) no Twitter para as eleições 2022](#identificar-candidatos-mais-mencionados-positivamente-e-negativamente-no-twitter-para-as-eleições-2022)
3. [Análise das diferenças salariais entre atletas do gênero masculino e feminino](#análise-das-diferenças-salariais-entre-atletas-do-gênero-masculino-e-feminino)
4. [Prever a quantidade de aviões que serão necessários nos próximos 10 anos.](#prever-a-quantidade-de-aviões-que-serão-necessários-nos-próximos-10-anos)
5. [Análise de investimento em campanhas eleitorais com o número de votos](#análise-de-investimento-em-campanhas-eleitorais-com-o-número-de-votos)
6. [Traçar o perfil de diversidade em empresas brasileiras](#traçar-o-perfil-de-diversidade-em-empresas-brasileiras)
7. [Fatores chave para o sucesso de uma música](#fatores-chave-para-o-sucesso-de-uma-música)
8. [Construir uma plataforma de descrição de imagens / texto](#construir-uma-plataforma-de-descrição-de-imagens--texto)
9. [Identificação de um idioma a partir do som](#identificação-de-um-idioma-a-partir-do-som)
10. [Outras ideias (fique à vontade para destrinchar)](#outras-ideias-fique-à-vontade-para-destrinchar)

### Identificação de processos de gentrificação a partir da análise de dados urbanos.

**Definir o escopo de trabalho:**

* Local ex: São Paulo? Rio de Janeiro (datalake)?
* Projeto urbano (metrô? obras das Olimpíadas? pedágios...)

**Levantar os dados necessários**

* Dados demográficos, IBGE, PNAD; dados abertos do município
* Requisitar via LAI (IPTU?)

**Caracterizar gentrificação** 
* que indicadores existem nos dados?
* Variação da renda da população
* Preço do m² dos imóveis; IPTU?
* Composição racial da população
* Abrangência do saneamento básico.
* Variação da população da região e de regiões no entorno.
* Variações na oferta de transporte público.

**Trabalhos futuros:**
* Encontrar possíveis candidatos - locais com perfis similares - à gentrificação no futuro próximo.

**Referências**

* https://outracidade.com.br/estudo-identifica-gentrificacao-partir-de-check-ins-em-redes-sociais/

<a href="#top">Voltar ao topo</a>

---------- 

### Identificar candidatos mais mencionados (positivamente e negativamente) no Twitter para as eleições 2022

**Definir escopo**
* Candidatos a que cargo? Qual o(s) período(s) das menções?

**Levantamento dos dados**
* Conseguir acesso à API do Twitter; armazenar os dados.
* Pesquisas de intenção de votos

**Caracterizar**

* O que é menção? Apenas @? Nome na Urna? Apelidos?
* Quais as queries específicas para o Twitter?
* O que é menção positiva e negativa? 
* Usar APIs (Google?) ou classificar manualmente?

**Ideias**
* Filtrar bots? Usar os dados de bots?
* Categorizar menções: imprensa, seguidores, famosos…
* Análise de redes
* Influência na intenção geral de votos.
* Usar as datas de divulgação das pesquisas de intenção.

**Referências**
* [Análise de sentimentos](https://cloud.google.com/natural-language/docs/analyzing-sentiment?hl=pt-br )
* Análise sobre o voto impresso
* Gephi


<a href="#top">Voltar ao topo</a>

--------


### Análise das diferenças salariais entre atletas do gênero masculino e feminino

**Definir escopo:**
* Esporte; 
* campeonato; 
* Como diferenciar valor “em carteira” de “direito de imagem”.

**Levantamento dos dados**

* Onde encontrar os dados? Parece um desafio.

**Como comparar?**

* Coeficiente de idade e desempenho nos jogos.
* Valor recebido pelo atleta e valor arrecadado pelo clube; arrecadação por partida.
* Quantidade de trocas de clube (aquisição de atleta).
* Quantidade de seguidores do atleta x salário;
* Diferença entre salários mais altos e mais baixos por gênero.

**Sugestões**

* Liga de basquete americana pode possuir os dados.
* Comparar diferentes países; diferentes campeonatos.
* Analisar notícias

<a href="#top">Voltar ao topo</a>

--------

### Prever a quantidade de aviões que serão necessários nos próximos 10 anos.

**Definir escopo**

* Voos domésticos ou internacionais? Local e rotas?

**Levantamentos dos dados**

* Site da IATA; Kaggle. (mercado americano)

**Analisar**

* Dados sócio-econômicos; quantidade de aeroportos na região.
* Faixa etária que mais viaja? Previsão demográfica
* Quantidades de operadoras de linhas aéreas;
* Frequência de passageiros nos últimos anos; volume de voos; idade das aeronaves.

**Sugestões**

* Análise de séries temporais

**Referências**

* https://www.faa.gov/data_research/aviation 

<a href="#top">Voltar ao topo</a>

--------

### Análise de investimento em campanhas eleitorais com o número de votos

**Definir escopo**
* Qual eleição? 
* Que cargo? 

**Levantamento dos Dados**
* Dados abertos do TSE

**O que analisar**
* Qual o custo do voto para cargo X por localidade [estado, município, região]?
* Custo de candidatos específicos?
* Será que pros cargos no Legislativo este indicador é mais determinante?
* Com o que se gasta? Materiais impressos, internet etc.

**Sugestões**
* Analisar se os custos de campanha cresceram acima da inflação.
* O que há nos outliers que se elegeram?
* Análise por gênero.

<a href="#top">Voltar ao topo</a>

--------

### Traçar o perfil de diversidade em empresas brasileiras


**Definir Escopo**
* Escolher um ou alguns segmentos.

**Caracterizar diversidade**
* mapear “perfis”

**Levantamento dos dados**
* Instituto Ethos; 
* CEERT; 
* Organização Internacional do Trabalho.

**O que analisar**
* Analisar relação dos cargos com perfil de diversidade.
* Criar indicador de diversidade.
* Agrupar empresas com base em perfil de diversidade.

**Sugestões**
* Em que segmentos as empresas têm um indicador de diversidade mais favorável

**Referências**
* https://www.mckinsey.com/business-functions/people-and-organizational-performance/our-insights/delivering-through-diversity?cid=soc-web
* https://smartlabbr.org/diversidade/ 

<a href="#top">Voltar ao topo</a>

--------

###  Fatores chave para o sucesso de uma música

**Definir Escopo**
* O que é uma música bem sucedida? 
* Quando (período no tempo)? 
* Nicho?

**Levantamento dos dados**
* Rankings de streaming (Spotify…)
* listas de referências (Billboard…)
* API do Spotify. 
* TikTok, redes sociais…

**O que analisar**
* É um som viral e momentâneo ou dura ao longo do tempo?
* Reproduções totais x por ouvinte único. 
* Presença em playlists.
* Features: ritmo; dançável etc; valência, duração, idade da música, etc
* Há uma concentração em torno de poucos artistas?

**Sugestões**
* Analisar fatores como divulgação, perfil dos artistas, rádio etc.

<a href="#top">Voltar ao topo</a>

--------

### Construir uma plataforma de descrição de imagens / texto


**Definir Escopo**
* Ferramenta de acessibilidade com descrição de uma imagem em texto automatizada
* Que tipos de imagens? Animais? Lugares? Humanos?

**Levantamento de dados**
* Kaggle; 
* Coco Dataset; 
* Visual Data.
* Dados categorizados

**Abordagem sugerida**
* Colocar um modelo pré-treinado em execução (deep learning).
* Estudar o artigo correspondente.
* Implementar um modelo de base ou testar “fine-tuning” do modelo escolhido.

**Referências**
* Paperswithcode
* PyimageSearch
* Seeing AI on the App Store (apple.com)
* https://thenextweb.com/news/microsofts-image-captioning-ai-is-pretty-darn-good-at-describing-pictures-like-a-human 
* Aprendizado “””multitask””” - aprender mais de uma tarefa. 
* Componente de visão computacional - redes convolucionais
* Componente de Processamento de Linguagem Natural - redes recorrentes, transformers

<a href="#top">Voltar ao topo</a>

--------

### Identificação de um idioma a partir do som

**Definir Escopo**
* Usar Speech to Text (STT)
* Relacionar sinal de áudio com idioma?
* Quais idiomas? 

**Levantamento de Dados**
* Buscar base de dados de artigos científicos

**Estratégia**
* Começar com 2 idiomas bem diferentes; incrementar aos poucos.
* Buscar modelos pré-treinados.
* Caracterizar o desempenho do modelo em relação a nativos e estrangeiros.

**Referências**
* SLURP: A Spoken Language Understanding Resource Package | Papers With Code

**Sugestão**
* Incrementar um modelo já treinado com uma nova língua.

<a href="#top">Voltar ao topo</a>

--------

###  Outras ideias (fique à vontade para destrinchar)

* Construção de um dataset de libras com imagens sintéticas.
* Análise do perfil das empresas cadastradas no Brasil.
* Identificação de linguagem de programação a partir de prints.
* Filtro anti-treta para tweets.
* Características dos atacantes mais bem sucedidos do campeonato brasileiro
* Formação tática mais vitoriosa dos principais campeonatos do mundo
* Num contexto de esportes individuais, os campeões mundiais e olímpicos juvenis tornam-se campeões mundiais e olímpicos na categoria adulta?
* Padrão de batida de pênaltis em Copas do Mundo
* Qual melhor jogador de futebol de todos os tempos?
* Qual valor de uma medalha olímpica?
* Análise dos gastos dos parlamentares durante todo o mandato
* Fraldas baratas: um identificador de preços mais baixos do que o usual
* Identificação de reclamações dos usuários nos comentários do Google Play
* Amplificador inteligente - corrige notas musicais na amplificação do som de um instrumento deixando sempre harmônica
* Tradutor de periquito - esse pássaro emite muitos sons diferentes
* Chat bot com inteligência artificial para fazer um teste de Turing