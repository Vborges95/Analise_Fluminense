# Análise Forense — Fluminense Football Club

**Exercícios 2023–2025 | Projeção 2026–2027 | Leitura da proposta SAF em discussão**

O Fluminense fechou 2025 com a maior receita bruta da sua história — R$ 1,022 bilhão — e entregou o quarto superávit contábil consecutivo. Mas a operação dia-a-dia perdeu R$ 256 milhões. O resultado positivo foi sustentado por três eventos não recorrentes (premiação FIFA Mundial, venda de três atletas e desconto da nova transação PGFN) que somaram R$ 654 milhões. A tese central desta análise é que o Flu não tem problema de solvência imediata, mas tem problema de modelo operacional: a operação recorrente queima entre R$ 250 e R$ 440 milhões por ano, e a sustentabilidade depende de manufaturar um terceiro ciclo consecutivo de eventos extraordinários nos próximos 24 meses.

*Para ler a tese central, vá ao Substack. Para a análise completa com premissas, ao PDF. Para testar cenários alternativos, à planilha.*

---

## Conteúdo do projeto

📋 **[Executive Summary em PDF](Executive_Summary_Fluminense.pdf)** — Filtro de leitura de 2-3 minutos com tese central, números-âncora, cenários compactos, riscos rankeados e implicações por público. Para quem precisa decidir se vai mergulhar no resto do material.

📰 **[Versão resumida no Substack]((https://substack.com/@vborges/note/c-263521716))** — Post de 7.895 caracteres com a tese principal e os cenários 2026-2027. Tom acessível para leitor amplo sem perder o rigor analítico.

📄 **[Análise completa em PDF](Analise_Fluminense_2025.pdf)** — Documento de 16 páginas com diagnóstico do triênio, projeção 2026-2027 nos três cenários, definição numérica de competitividade financeira, e leitura aprofundada dos dois caminhos (Continuidade vs. SAF). Anexo metodológico explicita todas as fontes e estimativas.

📊 **[Planilha consolidada](fluminense_modelo.xlsx)** — Modelo financeiro completo com 11 abas e 831 fórmulas. Inclui Balanço Patrimonial, DRE, DFC, decomposição de receita por categoria, análise operacional pura (EBITDA recorrente puro), painel de indicadores, e modelo de projeção 2026-2027 com três cenários totalmente editáveis pelo leitor.

📘 **[Manual da planilha em PDF](manual_planilha_fluminense.pdf)** — Guia operacional standalone para quem baixou o repositório e quer entender as convenções visuais, anatomia das abas, glossário das métricas-chave, limitações da análise e como adaptar a planilha para outros clubes brasileiros.

📁 **[dados_brutos/](dados_brutos/)** — PDFs originais das Demonstrações Financeiras auditadas e Relatório de Gestão do Fluminense Football Club, exercício 2025 (com comparativo 2024 reapresentado e 2023 reapresentado). Material público disponibilizado pelo próprio clube.

---

## Principais conclusões

- **EBITDA reportado de +R$ 191 milhões em 2025 vs. EBITDA recorrente puro de −R$ 256 milhões.** A distorção de R$ 447 milhões é o tamanho do filtro de leitura que separa a manchete do diagnóstico.

- **Em nenhum dos três exercícios (2023, 2024, 2025) a operação recorrente — sem cessão de atletas e sem premiação extraordinária — gerou caixa positivo.** O motor que produz os superávits anuais troca de combustível a cada ciclo. Nenhum dos combustíveis é renovável.

- **Auditoria BDO RCS mudou de opinião sem ressalvas (2024) para opinião com ressalvas (2025).** Três pontos identificados: conta bancária não circularizada (imaterial); provisão para contingências subdimensionada em R$ 34,2M; e classificação contestada da recompra de 10% dos direitos de transmissão (R$ 110,4M lançados como "Direito de Uso de Marca" no Intangível, amortizando em 50 anos).

- **Em todos os cenários 2026-2027, a geração orgânica de caixa é negativa.** Mesmo no cenário otimista (que replica a premissa de R$ 218M em vendas do Relatório de Gestão do próprio clube), o déficit acumulado de R$ 528 milhões precisará ser coberto por instrumentos não previstos.

- **Caminho A (continuidade) é trajetória, não solução de curto prazo.** As quatro condições de competitividade financeira definidas no estudo são atingíveis simultaneamente apenas em 2032-2035 sob hipóteses otimistas mantidas por 5-7 anos consecutivos.

- **Caminho B (proposta SAF LZ Esports/Lazuli Partners) resolve numericamente.** Aporte de R$ 6,9 bilhões em 10 anos por 65% do futebol implica valuation de R$ 10,6 bilhões — 10x acima do precedente brasileiro. Sete pontos críticos abertos: valuation, governança da minoria, composição dos R$ 870M de dívidas equacionáveis, garantia do aporte, tratamento da participação Fla-Flu, aprovação institucional, equacionamento das ressalvas do auditor.

---

## Metodologia

- **Validações cruzadas obrigatórias.** Ativo = Passivo + Patrimônio Líquido em todos os exercícios; Superávit DRE conciliado com variação do PL no BP em 2024 e 2025; Caixa final da DFC reconciliado com BP com diferença máxima de R$ 1 mil por arredondamento.

- **Separação granular entre receita recorrente e não recorrente.** Eventos extraordinários (Mundial FIFA 2025, Libertadores 2023, Recopa 2024) são desagregados individualmente, preservando como recorrente a premiação do calendário regular (Brasileirão, Carioca, Copa do Brasil, Sul-Americana em anos sem avanço). A diferença vs. a metodologia do próprio clube é documentada.

- **EBITDA Recorrente Puro como métrica analítica central.** Parte do EBITDA reportado e desconta sequencialmente os eventos não recorrentes de receita e os custos extraordinários associados, expondo a saúde operacional dia-a-dia.

- **Quatro condições numéricas de competitividade financeira:** cobertura operacional sem cessão de atletas; liquidez corrente ≥ 0,7; Dívida/EBITDA Recorrente Puro > 0; caixa final cobrindo ≥ 1 mês de folha. Cada uma com métrica específica derivada da planilha.

- **Tratamento das ressalvas do auditor:** valores publicados pelo clube são mantidos na planilha, com nota amarela indicando o ajuste proposto pelo auditor. Quem quiser modelar o cenário com os ajustes pode editar diretamente — o modelo recalcula automaticamente.

- **Atribuição explícita em proposta em discussão.** A leitura da SAF usa "proposta da LZ Esports/Lazuli Partners conforme reportagens disponíveis", "documento da proposta", "está em fase de avaliação". Nenhuma afirmação categórica sobre termos que ainda não foram tornados integralmente públicos.

---

## Série completa

Esta análise integra uma série de estudos forenses sobre clubes do Rio de Janeiro:

- ✅ **Vasco da Gama SAF** — publicado
- ✅ **Botafogo SAF** — publicado
- ✅ **Fluminense FC** — publicado (este repositório)
- ⏳ **Flamengo** — em preparação

A metodologia é consistente entre os estudos: mesmas convenções visuais, mesmas validações cruzadas, mesmas quatro condições de competitividade financeira (calibradas conforme as especificidades de cada clube), mesmo padrão de separação entre recorrente e não recorrente. Quem leu um dos posts anteriores encontra estrutura familiar aqui — o que muda é o caso clínico.

---

## Autor e contato

**Vinicius Borges** — profissional de Financial Planning & Analysis baseado no Rio de Janeiro. Escreve sobre a intersecção entre finanças e esportes no Substack e no LinkedIn.

- 📧 [Substack](LINK_SUBSTACK_AUTOR)
- 💼 [LinkedIn](LINK_LINKEDIN)

---

## Nota sobre os dados brutos

Os PDFs disponibilizados na pasta `dados_brutos/` são material público do Fluminense Football Club, disponibilizado pelo próprio clube em seu site oficial como parte da prestação de contas anual. Os direitos sobre os documentos originais pertencem ao Fluminense Football Club; este repositório agrega-os para facilitar a reprodutibilidade da análise por outros pesquisadores.

A análise, planilha, manual e demais materiais derivados neste repositório são de autoria própria. Reprodução parcial é permitida com atribuição. A análise não constitui recomendação de investimento, parecer jurídico ou aconselhamento financeiro — é leitura analítica de dados públicos para fins de divulgação informativa.# Analise_Fluminense
