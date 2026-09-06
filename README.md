# 🦁 LION APP

Planilha desenvolvida com o objetivo de **facilitar a organização das informações necessárias para a declaração do Imposto de Renda**.

O aplicativo permite que o usuário registre seus dados pessoais, saldos bancários, informes de rendimentos e notas, mantendo as informações organizadas para posterior envio ao contador ou para auxiliar o próprio usuário no preenchimento da declaração de Imposto de Renda.

O projeto é composto por três planilhas principais:

- **Titular**
- **Informes**
- **Notas**

Todas as planilhas possuem um **menu lateral de navegação**, permitindo acessar rapidamente qualquer uma das três áreas do aplicativo.

---

# 📋 Estrutura do Projeto

O LION APP está dividido nas seguintes áreas:

```text
LION APP
│
├── Titular
│   └── Dados pessoais e informações do titular
│
├── Informes
│   └── Informes de rendimentos bancários
│
└── Notas
    └── Lançamento de notas e extratos de holerites
```

---

# 👤 1. Titular

A planilha **Titular** é destinada ao cadastro das informações pessoais do contribuinte.

Nesta área, o usuário informa os principais dados necessários para sua identificação e organização das informações para a declaração.

## Dados pessoais

Podem ser cadastradas as seguintes informações:

- **Nome**
- **CPF**
- **Data de nascimento**
- **Título de eleitor**
- **Cônjuge**
- **Rua**
- **CEP**
- **Telefone**
- **Celular**
- **E-mail**

Além dos dados pessoais, a planilha possui três campos que devem ser preenchidos com **SIM** ou **NÃO**.

### Houve alterações da entrega anterior

Indica se houve alguma alteração nas informações do contribuinte em relação à declaração entregue anteriormente.

### Dependente Cônjuge

Indica se o cônjuge será considerado como dependente na declaração.

### Residente do Exterior

Indica se o titular possui a condição de residente no exterior.

---

# 🏦 2. Informes

A planilha **Informes** é destinada ao registro dos **informes de rendimentos bancários**.

Cada lançamento corresponde às informações de uma instituição bancária.

Para cada banco, o usuário deve informar:

| Campo | Descrição |
|---|---|
| **Banco** | Instituição bancária selecionada entre as opções disponíveis |
| **Valor atual** | Saldo ou valor informado pelo banco |
| **Anexo** | Nome do arquivo do informe que será enviado ao contador |

## Banco

O banco deve ser selecionado a partir das opções disponibilizadas na planilha.

Isso facilita a padronização dos lançamentos e evita a necessidade de digitação manual do nome da instituição.

## Valor atual

Campo destinado ao registro do valor ou saldo informado pela instituição bancária.

## Anexo

Campo utilizado para registrar o **nome do arquivo correspondente ao informe de rendimentos**.

Esse campo facilita a identificação dos documentos que deverão ser encaminhados posteriormente ao contador.

### Total

A planilha possui também o campo **TOTAL**, responsável por somar os valores informados nos lançamentos dos bancos.

Dessa forma, o usuário consegue visualizar o total dos valores registrados na seção de informes.

---

# 📝 3. Notas

A planilha **Notas** possui uma tabela destinada ao lançamento de informações provenientes de **notas bancárias ou extratos de holerites**.

A tabela possui as seguintes colunas:

| Data | Categoria | Valor |
|---|---|---:|
| Mês-Ano | Categoria do lançamento | Valor |

### Data

Registra o período do lançamento no formato **mês-ano**.

### Categoria

Identifica a categoria correspondente ao lançamento realizado.

### Valor

Registra o valor correspondente ao lançamento.

A organização dessas informações permite manter um histórico dos valores lançados, facilitando sua posterior consulta e utilização na preparação da declaração.

---

# 🧭 4. Menu de Navegação

Todas as planilhas do LION APP possuem um **menu lateral de navegação**.

O menu permite acessar as três áreas principais do aplicativo:

- **Titular**
- **Informes**
- **Notas**

Cada opção do menu possui um **link para a respectiva planilha**, permitindo navegar rapidamente entre as diferentes áreas do projeto.

A navegação funciona da seguinte forma:

```text
             ┌──────────────┐
             │   LION APP   │
             └──────┬───────┘
                    │
              MENU LATERAL
                    │
       ┌────────────┼────────────┐
       ▼            ▼            ▼
   TITULAR       INFORMES       NOTAS
       │            │            │
       ▼            ▼            ▼
    Dados       Informes      Notas e
   pessoais     bancários     lançamentos
```

O mesmo menu está disponível nas três planilhas, proporcionando uma navegação consistente em todo o aplicativo.

---

# 🎯 Objetivo do Projeto

O **LION APP** tem como principal objetivo facilitar a **organização das informações e documentos relacionados à declaração do Imposto de Renda**.

Com a utilização da planilha, o usuário pode:

- cadastrar seus dados pessoais;
- registrar informações do titular;
- informar dados relacionados ao cônjuge;
- indicar alterações em relação à declaração anterior;
- informar se é residente do exterior;
- registrar saldos e informações de diferentes bancos;
- identificar os arquivos dos informes de rendimentos;
- acompanhar o total dos valores registrados nos informes;
- registrar notas e informações provenientes de extratos de holerites;
- organizar os lançamentos por data, categoria e valor;
- reunir as informações em um único aplicativo;
- facilitar o envio das informações e documentos ao contador;
- utilizar os dados organizados como apoio para sua própria declaração de Imposto de Renda.

---

# ⚠️ Observação

O LION APP é uma ferramenta de **organização e controle de informações**.

A planilha tem como finalidade facilitar o levantamento e a organização dos dados necessários para a declaração do Imposto de Renda, não substituindo a orientação de um profissional especializado quando esta for necessária.