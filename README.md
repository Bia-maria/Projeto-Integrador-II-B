# Sistema de Gerenciamento de Intenções das Santas Missas

## Projeto Integrador II-B

**Pontifícia Universidade Católica de Goiás – PUC Goiás**
**Escola Politécnica e de Artes**
**Curso Tecnólogo em Análise e Desenvolvimento de Sistemas**

### Integrantes

* **Beatriz de Freitas Ribeiro Silva**
* **Eduardo Sales Sousa**
* **Helder de Almeida Santos**

**Goiânia – 2026**

---

## 1. Sobre o projeto

O projeto apresenta a proposta de um **Sistema de Gerenciamento de Intenções das Santas Missas** para utilização na secretaria de uma paróquia.

O objetivo é propor uma solução informatizada que auxilie as secretárias paroquiais na **organização, consulta e acompanhamento das intenções** encaminhadas para as celebrações.

O levantamento realizado identificou que as intenções são recebidas principalmente por meio do **WhatsApp** e também presencialmente na secretaria da paróquia. Atualmente, o registro das intenções é realizado em um sistema.

A proposta busca melhorar a organização e a consulta dessas informações, principalmente por meio da **identificação de nomes repetidos** e da visualização organizada das intenções.

---

## 2. Objetivo geral

Propor um sistema informatizado para auxiliar a secretaria paroquial no gerenciamento e na organização das intenções das Santas Missas.

---

## 3. Objetivos específicos

* Facilitar o cadastro das intenções;
* Facilitar a consulta das intenções;
* Organizar as intenções de acordo com as respectivas missas;
* Permitir a identificação de nomes repetidos;
* Reduzir a possibilidade de erros nos registros;
* Facilitar o trabalho das secretárias paroquiais;
* Permitir o acesso por computador e dispositivos móveis;
* Contribuir para a organização digital das informações.

---

## 4. Levantamento de requisitos

O levantamento de requisitos foi realizado por meio de uma pesquisa com uma pessoa responsável pelas atividades da secretaria paroquial relacionadas às intenções das Santas Missas.

Foi utilizado um formulário contendo **10 perguntas objetivas**, relacionadas ao processo de recebimento, registro e organização das intenções.

### Principais resultados da pesquisa

| Item                                 | Resultado                                   |
| ------------------------------------ | ------------------------------------------- |
| Recebimento das intenções            | WhatsApp e presencialmente na secretaria    |
| Registro atual                       | Sistema                                     |
| Informação necessária                | Nome da pessoa                              |
| Responsáveis pela organização        | Secretárias paroquiais                      |
| Ocorrência de erros ou esquecimentos | Sim                                         |
| Consulta das intenções de uma missa  | Considerada útil                            |
| Usuário do sistema                   | Secretaria da paróquia                      |
| Função considerada importante        | Identificação de nomes repetidos            |
| Dispositivos                         | Computador e celular                        |
| Utilidade de um sistema              | A entrevistada considera que ajudaria muito |

---

## 5. Requisitos funcionais

O sistema deverá:

* **RF01:** Permitir que o usuário autorizado realize login;
* **RF02:** Permitir cadastrar uma nova intenção;
* **RF03:** Permitir informar o nome relacionado à intenção;
* **RF04:** Permitir associar a intenção à respectiva Santa Missa;
* **RF05:** Permitir consultar as intenções cadastradas;
* **RF06:** Permitir visualizar as intenções de uma determinada missa;
* **RF07:** Permitir pesquisar uma intenção pelo nome;
* **RF08:** Identificar nomes repetidos entre as intenções cadastradas;
* **RF09:** Permitir editar uma intenção cadastrada;
* **RF10:** Permitir excluir uma intenção cadastrada;
* **RF11:** Permitir visualizar as informações de maneira organizada por missa.

---

## 6. Requisitos não funcionais

O sistema deverá:

* **RNF01:** Possuir uma interface simples e fácil de utilizar;
* **RNF02:** Funcionar em computadores e dispositivos móveis;
* **RNF03:** Permitir acesso somente a usuários autorizados;
* **RNF04:** Armazenar as informações de forma segura;
* **RNF05:** Apresentar as informações de maneira organizada;
* **RNF06:** Possuir tempo de resposta adequado nas consultas;
* **RNF07:** Possuir uma interface adaptável a diferentes tamanhos de tela.

---

## 7. Usuário do sistema

O principal usuário previsto para o sistema é a **secretaria da paróquia**, representada pelas secretárias paroquiais responsáveis pela organização das intenções.

O usuário autorizado poderá:

* Acessar o sistema;
* Cadastrar intenções;
* Consultar intenções;
* Pesquisar nomes;
* Identificar nomes repetidos;
* Alterar informações;
* Excluir registros;
* Visualizar as intenções de determinada missa.

---

## 8. Modelagem do sistema

O projeto possui um **Diagrama de Caso de Uso**, representando as principais interações do usuário responsável pela secretaria com o sistema.

As principais funcionalidades representadas incluem:

* Acesso ao sistema;
* Cadastro de intenção;
* Consulta de intenções;
* Gerenciamento das intenções;
* Identificação de nomes repetidos.

---

## 9. Protótipo de interface

O protótipo foi elaborado para representar visualmente as principais funcionalidades propostas para o sistema.

Foram definidas cinco telas principais:

### 9.1 Tela de Login

Permite que usuários autorizados tenham acesso ao sistema.

**Elementos:**

* Campo de usuário;
* Campo de senha;
* Botão **Entrar**.

### 9.2 Tela Inicial

Apresenta um resumo das informações mais importantes do sistema.

**Elementos:**

* Próximas Santas Missas;
* Quantidade de intenções cadastradas;
* Acesso ao cadastro de nova intenção;
* Acesso à lista de intenções;
* Aviso sobre nomes repetidos.

### 9.3 Tela de Cadastro de Intenção

Permite registrar uma nova intenção.

**Campos:**

* Nome da pessoa;
* Data da missa;
* Tipo de Intenção;
* Horário da missa;
* Observação.

**Tipos de intenção:**

* Aniversário;
* Alma;
* Pela saúde.

**Botão:**

* **Cadastrar Intenção**.

### 9.4 Tela de Consulta das Intenções

Permite visualizar e localizar as intenções cadastradas.

A consulta poderá ser realizada por:

* Nome;
* Missa.

### 9.5 Tela de Nomes Repetidos

Permite identificar quando o mesmo nome aparece em mais de uma intenção cadastrada.

Essa funcionalidade foi definida a partir da necessidade identificada durante o levantamento de requisitos.

---

## 10. Validação do protótipo

Após a elaboração do protótipo, as telas deverão ser apresentadas ao responsável pela secretaria paroquial que participou do levantamento.

A validação tem como objetivo verificar se as telas são compreensíveis e se as funcionalidades propostas estão de acordo com as necessidades identificadas durante a pesquisa.

### Perguntas utilizadas na validação

1. As telas são fáceis de entender e utilizar?
2. A visualização das intenções de cada missa seria útil para a secretaria?
3. A identificação de nomes repetidos ajudaria na organização das intenções?

As respostas obtidas serão utilizadas para verificar se o protótipo atende às necessidades levantadas e, caso necessário, realizar pequenos ajustes nas telas.

---

## 11. Sustentabilidade

A proposta considera a preocupação com a sustentabilidade e o uso consciente de recursos.

A organização digital das informações pode contribuir para reduzir a necessidade de registros físicos e impressões desnecessárias, além de facilitar a consulta e o armazenamento das informações.

Dessa forma, a proposta relaciona a sustentabilidade principalmente à **digitalização, organização das informações e redução do uso desnecessário de materiais físicos**.

---

## 12. Resultados esperados

Com a proposta do sistema, espera-se:

* Facilitar o trabalho das secretárias paroquiais;
* Melhorar a organização das intenções;
* Facilitar a consulta das informações;
* Permitir a visualização das intenções de cada missa;
* Identificar nomes repetidos;
* Diminuir a possibilidade de registros incorretos;
* Facilitar o acesso por computador e celular;
* Contribuir para a organização digital das informações.

---

## 13. Documentação

A documentação do projeto contém:

* Introdução;
* Objetivos;
* Levantamento de requisitos;
* Requisitos funcionais;
* Requisitos não funcionais;
* Usuário do sistema;
* Diagrama de Caso de Uso;
* Descrição do Caso de Uso Principal;
* Protótipo de interface;
* Validação do protótipo;
* Sustentabilidade;
* Resultados esperados;
* Conclusão.

---

## 14. Estrutura do repositório

```text
Projeto-Integrador-II-B/
│
├── README.md
│
├── Documentação/
│   └── Projeto-Integrador-II-B.pdf
│
├── Protótipo/
│   ├── Tela-Login.png
│   ├── Tela-Inicial.png
│   ├── Tela-Cadastro-de-Intenção.png
│   ├── Tela-Consulta-das-Intenções.png
│   └── Tela-Nomes-Repetidos.png
│
└── Projeto-Integrador-II-B.zip
```

---

## 15. Informações acadêmicas

**Instituição:** Pontifícia Universidade Católica de Goiás – PUC Goiás
**Escola:** Escola Politécnica e de Artes
**Curso:** Tecnólogo em Análise e Desenvolvimento de Sistemas
**Projeto:** Projeto Integrador II-B
**Ano:** 2026

---

## 16. Observação

Este projeto apresenta a **especificação dos requisitos e a prototipação de uma proposta de sistema**. O desenvolvimento do software não faz parte desta etapa do projeto.
