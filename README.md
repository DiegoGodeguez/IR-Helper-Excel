# 📊 Gerenciador e Pré-Preenchedor de Imposto de Renda (IR) em Excel

Ferramenta desenvolvida em **Microsoft Excel** para simplificar, organizar e centralizar todas as informações necessárias para a Declaração do Imposto de Renda Pessoa Física (IRPF). 

A aplicação funciona como um painel central onde o usuário pode cadastrar dados pessoais, gerenciar contas e informes de rendimentos bancários, registrar entradas de holerites/notas e vincular comprovantes e recibos em PDF.

---

## 🚀 Principais Funcionalidades

* **📋 Dados do Titular e Dependentes:** Organização completa de informações cadastrais (CPF, Título de Eleitor, endereço, dados de cônjuge, etc.).
* **🏦 Informes de Rendimentos Bancários:** Seleção de instituições financeiras via lista suspensa dinâmica, consolidação de saldos e acompanhamento de anexos.
* **🧾 Gestão de Holerites e Notas:** Registro mensal de entradas e receitas com categorização por CNPJ, fonte pagadora e valores.
* **🖇️ Gestão de Anexos:** Estrutura para controle e organização de comprovantes e recibos de pagamento em formato PDF.
* **⚙️ Tabela de Apoio e Validação:** Base padronizada com códigos de instituições bancárias e listas suspensas (Data Validation) para evitar erros de digitação.

---

## 🛠️ Recursos Técnicos Utilizados no Excel

* **Validação de Dados (`Data Validation`):** Listas suspensas dinâmicas para seleção rápida de bancos e categorias.
* **Fórmulas e Funções de Agregação:** Soma e consolidação automática de saldos de informes bancários.
* **Formatos de Data e Moeda:** Padronização visual para facilitar a visualização e auditoria antes do preenchimento no programa da Receita Federal.
* **Estruturação Multiabas:** Separação lógica em abas (*Titular*, *Informes*, *Notas* e *Tabela_Apoio*).

---

## 📁 Estrutura do Repositório

```text
├── App de IR.xlsx         # Arquivo principal do projeto em Excel
└── README.md              # Documentação do repositório
