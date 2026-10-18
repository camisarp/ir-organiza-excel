# IR Organiza | Organizador de Informações para Imposto de Renda

**Uma ferramenta em Excel para centralizar dados e acompanhar a organização dos documentos necessários à preparação da declaração do Imposto de Renda.**

O **IR Organiza** foi desenvolvido com foco em **usabilidade, consistência dos registros e visualização de informações**. Em vez de espalhar dados entre anotações e arquivos diferentes, o usuário dispõe de uma pasta de trabalho com formulários estruturados, validações, indicadores e navegação entre as etapas.

> **Atenção:** este projeto apoia a organização de informações; **não calcula o imposto devido, não substitui o programa oficial da Receita Federal e não constitui orientação tributária**.

## Objetivo

O objetivo do IR Organiza é reunir, em um único arquivo Excel, as informações cadastrais, financeiras e documentais necessárias à preparação da declaração do Imposto de Renda. A ferramenta oferece preenchimento orientado, acompanhamento de pendências e uma visão consolidada dos registros.

O projeto foi criado como parte de um desafio prático da **DIO**, com desenvolvimento e personalização da interface, dos registros e dos painéis para compor meu portfólio.

## Funcionalidades

- **Interface de navegação:** acesso às principais áreas da pasta de trabalho por meio de uma aba inicial e links entre seções.
- **Dados organizados por categoria:** cadastro do titular, contas bancárias, rendimentos, pagamentos, bens e direitos e documentos.
- **Validação de dados:** listas suspensas para padronizar categorias e reduzir inconsistências de digitação.
- **Acompanhamento de pendências:** campos de situação calculados a partir das informações registradas.
- **Indicadores e painéis:** consolidação de valores e acompanhamento visual dos registros e documentos.
- **Proteção de células:** separação entre campos editáveis e áreas com fórmulas ou elementos de apresentação.
- **Links rápidos:** acesso a referências e perfis relacionados ao projeto.

## Estrutura da pasta de trabalho

| Aba | Finalidade |
| --- | --- |
| **INÍCIO** | Tela de apresentação, navegação e visão geral de indicadores. |
| **TITULAR** | Registro de informações cadastrais do titular e de dependentes. |
| **BANCOS** | Organização de contas, saldos e informações bancárias. |
| **RENDIMENTOS** | Lançamento de fontes pagadoras, valores recebidos e imposto retido. |
| **PAGAMENTOS** | Registro de despesas, valores pagos e eventuais reembolsos. |
| **BENS E DIREITOS** | Relação de bens, suas características e valores informados. |
| **DOCUMENTOS** | Controle dos comprovantes e acompanhamento do recebimento. |
| **RESUMO** | Indicadores consolidados e gráficos para acompanhamento. |
| **TABELA** | Listas auxiliares que alimentam validações e categorias de preenchimento. |

## Recursos do Excel aplicados

O desenvolvimento explora:

- **Fórmulas e referências entre planilhas** para consolidar dados e calcular indicadores;
- **Funções condicionais** para definir situações e sinalizar pendências;
- **Tabelas estruturadas, filtros e formatação de dados** para organizar lançamentos;
- **Validação de dados e intervalos nomeados** para disponibilizar listas de seleção;
- **Formatação condicional e indicadores visuais** para facilitar a leitura;
- **Gráficos e dashboards** para transformar lançamentos em uma visão gerencial;
- **Hiperlinks e recursos de navegação** para melhorar a experiência de uso;
- **Bloqueio seletivo de células e proteção de planilhas** para preservar a estrutura durante o preenchimento.

## Como utilizar

1. Baixe o arquivo Excel disponível neste repositório.
2. Abra-o preferencialmente no **Microsoft Excel para desktop**, para uma experiência mais consistente com os recursos de formatação e navegação.
3. Comece pela aba **INÍCIO** e avance para **TITULAR**.
4. Preencha os campos liberados em **BANCOS**, **RENDIMENTOS**, **PAGAMENTOS**, **BENS E DIREITOS** e **DOCUMENTOS**.
5. Consulte a aba **RESUMO** para acompanhar os indicadores e os registros pendentes.
6. Salve uma cópia própria da planilha antes de inserir informações pessoais.

> **Privacidade:** não inclua CPF, dados bancários ou documentos reais ao compartilhar arquivos de demonstração publicamente. Os exemplos destinados ao portfólio devem usar dados fictícios.

## Demonstração visual

Capturas de tela das principais áreas serão organizadas na pasta `images/`, incluindo a interface inicial, uma área de lançamentos e o painel de resumo.

## Decisões de desenvolvimento

A solução foi estruturada em abas com responsabilidades distintas: **entrada de dados**, **listas auxiliares** e **consolidação de resultados**. Essa separação facilita o uso, a manutenção e a identificação de informações ausentes.

Os campos destinados ao usuário são diferenciados das áreas calculadas. As validações orientam o preenchimento e os painéis ajudam a identificar o que já foi registrado e o que ainda exige atenção.

## Aprendizados

O principal aprendizado foi transformar recursos isolados do Excel em uma **ferramenta integrada**, priorizando não apenas fórmulas e formatação, mas também a clareza do fluxo de uso, a consistência dos dados e a documentação técnica.

O desafio reforçou a importância de testar a interação entre abas, manter a lógica dos cálculos organizada e apresentar o resultado de forma compreensível para quem não participou do desenvolvimento.

## Autoria

**Desenvolvido por Camila Ribeiro Pinto**

- Projeto desenvolvido para fins de **aprendizado e portfólio**, no contexto de um desafio de projeto da **DIO**.

---

*IR Organiza — organização de informações para uma preparação mais prática da declaração de Imposto de Renda.*
