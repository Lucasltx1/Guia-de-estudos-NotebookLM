#  Guia de Estudos - NotebookLM: Investimentos e Gestão Financeira

Este repositório documenta o processo de estudo e extração de conhecimento utilizando o NotebookLM, com foco em educação financeira, renda fixa e variável.

##  Índice
- [Contexto e Objetivos](#-contexto-e-objetivos)
- [Curadoria de Fontes](#-curadoria-de-fontes)
- [Engenharia de Prompts e Cicatrizes](#-engenharia-de-prompts-e-cicatrizes-troubleshooting)
- [Miniguia de Estudo](#-miniguia-de-estudo)
- [Glossário de Conceitos](#-glossário-de-conceitos)
- [Prompts Reutilizáveis](#-prompts-reutilizáveis-cheat-sheet)

---

## Contexto e Objetivos

**Assunto de Interesse:**
O foco deste caderno temático é a construção de uma base sólida em educação financeira, explorando desde a matemática por trás dos rendimentos até a aplicação prática em ativos de renda fixa e variável.

**Objetivos de Estudo:**
- Compreender os mecanismos de funcionamento e a rentabilidade dos títulos públicos (Tesouro Direto).
- Desmistificar o investimento na Bolsa de Valores, focando em estratégias de longo prazo e gestão de risco.
- Aplicar conceitos de Matemática Financeira (como juros compostos e valor no tempo do dinheiro) para projetar e analisar o crescimento de patrimônio.
- Desenvolver critérios técnicos para monitorar, avaliar e rebalancear uma carteira de investimentos.

---

## Curadoria de Fontes

Os materiais abaixo foram selecionados para fundamentar este projeto, mesclando teoria matemática governamental com guias práticos de mercado:

1. **[YouTube - Busca: Investindo na Bolsa de Valores](https://www.youtube.com/results?search_query=investindo+na+bolsa+de+valores)**: Vídeos educativos sobre os primeiros passos e estratégias na renda variável.
2. **[Guia Investidor Tesouro Direto (ENAP)](https://repositorio.enap.gov.br/bitstream/1/6248/1/Guia_Investidor%20TD.pdf)**: Documento oficial detalhando o funcionamento, as taxas e os tipos de títulos da dívida pública federal.
3. **[Matemática Financeira (CAPES)](https://educapes.capes.gov.br/bitstream/capes/204422/2/MATEM%C3%81TICA%20FINANCEIRA.pdf)**: Material acadêmico sobre cálculo de juros, taxas equivalentes e amortização.
4. **[Mercado Pago - Como analisar seus investimentos](https://www.mercadopago.com.br/blog/como-analisar-seus-investimentos)**: Guia prático sobre indicadores de performance e avaliação de portfólio.

---

## Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Registro do raciocínio estratégico utilizado para extrair as melhores informações das fontes durante a pesquisa com Inteligência Artificial:

### Tentativa 1 (Prompt Inicial)
* **Prompt:** *"Qual é melhor para investir: Tesouro Direto ou Bolsa de Valores segundo as fontes?"*
* **Resultado obtido:** A resposta foi genérica e evasiva ("depende do seu perfil de investidor"), sem trazer dados matemáticos ou técnicos das fontes enviadas.
* **Dificuldade (Cicatriz):** Faltou delimitar um cenário comparativo exato. A IA tende a dar respostas seguras e superficiais sobre dinheiro se não for forçada a usar a matemática.

### Tentativa 2 (Refinamento e Sucesso)
* **Prompt Estratégico:** *"Atuando como um Analista Financeiro Quantitativo e usando as fórmulas do documento 'Matemática Financeira (CAPES)', explique a diferença do impacto dos juros compostos no longo prazo (10 anos) entre um título do Tesouro IPCA+ (documento ENAP) e uma carteira teórica de ações. Não dê conselhos financeiros, apenas demonstre a mecânica matemática do risco vs retorno."*
* **Resultado obtido:** Resposta altamente técnica. A IA extraiu as fórmulas de montante composto e explicou a previsibilidade da curva de juros do Tesouro contra a volatilidade e o prêmio de risco exigido na Bolsa de Valores.

> **Lição Aprendida:** Ao lidar com finanças, é fundamental exigir que a IA atue com um "papel técnico" (Analista Quantitativo) e cruze documentos diferentes (a fórmula de um PDF com o conceito do outro) para gerar insights de alto valor.

---

## Miniguia de Estudo

* **Renda Fixa (Tesouro Direto):** Funciona como um empréstimo do investidor para o Governo Federal. Oferece alta segurança e diferentes indexadores: prefixados (taxa definida no ato), atrelados à Selic (ideal para reserva de emergência) ou atrelados à inflação (IPCA+, que protege o poder de compra no longo prazo).
* **Renda Variável (Bolsa de Valores):** Envolve a compra de frações de empresas (ações) ou fundos imobiliários. Não há garantia de retorno, e o saldo oscila diariamente (marcação a mercado extrema). O foco deve estar na análise dos fundamentos das empresas e na consistência dos aportes para diluir o risco através do tempo e da diversificação.
* **Análise de Investimentos:** Avaliar uma carteira vai além de olhar o saldo. É preciso acompanhar a rentabilidade real (acima da inflação), comparar os ativos com benchmarks adequados (ex: Renda Fixa x CDI; Bolsa x Ibovespa) e rebalancear os percentuais da carteira anualmente para manter o nível de risco sob controle.

---

## Glossário de Conceitos

* **Juros Compostos:** O "juro sobre juro". É a força motriz do crescimento exponencial do patrimônio ao longo do tempo.
* **Liquidez:** A facilidade e a velocidade com que um ativo (um título ou uma ação) pode ser convertido em dinheiro em conta sem perda significativa de valor.
* **Marcação a Mercado:** A atualização diária do preço de um ativo (mesmo na renda fixa) caso o investidor decida vendê-lo antes do prazo de vencimento.
* **Benchmark:** Um índice de referência utilizado para avaliar a performance de um investimento (ex: a taxa Selic ou CDI para renda fixa).

---

## Prompts Reutilizáveis (Cheat Sheet)

Guarde e utilize os prompts estratégicos abaixo para futuras revisões ou para extrair novos conhecimentos do NotebookLM:

```text
Crie um problema matemático prático de cálculo de juros compostos baseado no material da CAPES, envolvendo aportes mensais de R$ 500, e depois forneça a resolução passo a passo.
Aja como um gestor de risco. Com base no material sobre o Tesouro Direto (ENAP) e no artigo do Mercado Pago, liste 3 erros comuns que investidores iniciantes cometem ao tentar analisar o rendimento de suas carteiras.
