# Projeto: Organizador de Dados para Imposto de Renda

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático de Excel, com o objetivo de criar uma ferramenta para organizar informações financeiras e facilitar a preparação dos dados necessários para a Declaração do Imposto de Renda Pessoa Física (IRPF).

A planilha permite centralizar informações do contribuinte, informes de rendimentos bancários e registros de receitas, utilizando recursos do Excel para tornar o preenchimento mais organizado e eficiente.

## 🎯 Objetivos

- Organizar os dados cadastrais do contribuinte.
- Centralizar informações de diferentes instituições financeiras.
- Registrar receitas e entradas financeiras.
- Automatizar a soma dos valores dos informes bancários.
- Facilitar a consulta e organização dos documentos necessários à declaração.

## 📊 Estrutura da ferramenta

A planilha está dividida em quatro abas:

### 1. TÍTULAR
Área destinada ao cadastro das informações pessoais do contribuinte, incluindo:
- Nome e CPF;
- Data de nascimento;
- Endereço e CEP;
- Telefone e e-mail;
- Informações complementares da declaração.

### 2. INFORMES
Área destinada ao registro dos informes de rendimentos bancários:
- Instituição financeira;
- Valor informado;
- Referência ao documento anexo;
- Consolidação automática dos valores cadastrados.

**Recurso utilizado:** função `SOMA` para calcular o total dos valores registrados nos três campos bancários.

### 3. NOTAS
Área destinada ao registro das entradas financeiras ao longo do ano, contendo:
- Data da movimentação;
- Categoria da receita;
- Valor recebido.

Foram utilizadas listas suspensas para padronizar as categorias de lançamento, como HOLERITE, CNPJ e FREELANCE.

### 4. BANCOS
Base auxiliar com códigos e nomes de instituições financeiras, utilizada para apoiar a identificação dos bancos nos informes.

## 🛠️ Recursos do Excel utilizados

- Fórmulas de cálculo e consolidação;
- Função SOMA;
- Validação de dados;
- Listas suspensas;
- Organização de informações em abas;
- Formatação de células e campos de preenchimento.

## 🚀 Como utilizar

1. Baixe o arquivo Excel disponível neste repositório.
2. Abra a planilha no Microsoft Excel.
3. Preencha os dados cadastrais na aba TÍTULAR.
4. Informe os bancos e respectivos valores na aba INFORMES.
5. Registre as entradas financeiras na aba NOTAS.
6. Consulte a aba BANCOS para identificar as instituições financeiras.
7. Confira os valores consolidados e os dados preenchidos.

## 📁 Estrutura do repositório

```text
calculo-imposto-renda/
│
├── README.md
├── Cálculo Imposto de Renda.xlsx
│
└── images/
    ├── titular.png
    ├── informes.png
    ├── notas.png
    └── bancos.png
```

## 📸 Demonstração

As capturas de tela da ferramenta serão disponibilizadas na pasta `images`, apresentando as abas e os principais recursos utilizados no desenvolvimento.

## 📚 Aprendizados

O desenvolvimento deste projeto proporcionou a aplicação prática de recursos do Microsoft Excel, especialmente organização de dados, validação de informações, utilização de fórmulas e estruturação de uma ferramenta voltada ao controle financeiro.

## ⚠️ Observação

Esta ferramenta tem finalidade organizacional e educacional. Não substitui o programa oficial da Receita Federal, não realiza a apuração completa do imposto devido e não transmite declarações.

---

**Projeto desenvolvido para fins de aprendizado e prática de Excel.**
