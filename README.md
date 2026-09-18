# Sistema de Gerenciamento de Intenções das Santas Missas
## Projeto Integrador II-B

**Pontifícia Universidade Católica de Goiás – PUC Goiás**
**Escola Politécnica e de Artes**
**Curso Tecnólogo em Análise e Desenvolvimento de Sistemas**

Integrantes:
Beatriz de Freitas Ribeiro Silva;
Eduardo Sales Sousa;
Helder de Almeida Santos;

##  Sobre o projeto

O projeto apresenta a proposta de um **Sistema de Gerenciamento de Intenções das Santas Missas**, desenvolvido para auxiliar a secretaria de uma paróquia na organização, consulta e gerenciamento das intenções encaminhadas para as celebrações.

O levantamento de requisitos foi realizado considerando a rotina da secretaria paroquial. As intenções são recebidas principalmente por **WhatsApp** e também presencialmente na secretaria. Atualmente, essas informações já são registradas em um sistema.

A proposta busca facilitar ainda mais a organização e a consulta das intenções, principalmente por meio da **identificação de nomes repetidos** e da visualização organizada das informações.

##  Objetivo geral

Propor um sistema informatizado para auxiliar a secretaria paroquial no gerenciamento e na organização das intenções das Santas Missas.

##  Objetivos específicos

* Facilitar o cadastro das intenções;
* Facilitar a consulta das intenções;
* Organizar as intenções de acordo com as respectivas missas;
* Permitir a identificação de nomes repetidos;
* Reduzir a possibilidade de erros nos registros;
* Facilitar o trabalho das secretárias paroquiais;
* Permitir o acesso por computador e dispositivos móveis;
* Contribuir para a organização digital das informações.

##  Levantamento de requisitos

O levantamento de requisitos foi realizado por meio de uma pesquisa com uma pessoa responsável pelas atividades da secretaria paroquial relacionadas às intenções das Santas Missas.

Foi utilizado um formulário com **10 perguntas** relacionadas ao recebimento, registro e organização das intenções.

### Principais resultados

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


##  Requisitos funcionais

O sistema deverá:

* Permitir que o usuário autorizado realize login;
* Permitir cadastrar uma nova intenção;
* Permitir informar o nome relacionado à intenção;
* Permitir associar a intenção à respectiva Santa Missa;
* Permitir consultar as intenções cadastradas;
* Permitir visualizar as intenções de uma determinada missa;
* Permitir pesquisar uma intenção pelo nome;
* Identificar nomes repetidos entre as intenções cadastradas;
* Permitir editar uma intenção cadastrada;
* Permitir excluir uma intenção cadastrada;
* Permitir visualizar as informações de maneira organizada por missa.

##  Requisitos não funcionais

O sistema deverá:

* Possuir uma interface simples e fácil de utilizar;
* Funcionar em computadores e dispositivos móveis;
* Permitir acesso somente a usuários autorizados;
* Armazenar as informações de forma segura;
* Apresentar as informações de maneira organizada;
* Possuir tempo de resposta adequado nas consultas;
* Possuir uma interface adaptável a diferentes tamanhos de tela.

##  Usuário do sistema

O principal usuário previsto é a **secretaria da paróquia**, representada pelas secretárias paroquiais responsáveis pela organização das intenções.

O usuário autorizado poderá:

* Acessar o sistema;
* Cadastrar intenções;
* Consultar intenções;
* Pesquisar nomes;
* Identificar nomes repetidos;
* Alterar informações;
* Excluir registros;
* Visualizar as intenções de determinada missa.

##  Protótipo

O projeto possui um protótipo de interface com cinco telas principais:

### 1. Tela de Login

Permite o acesso de usuários autorizados ao sistema.

**Elementos principais:**

* Campo de usuário;
* Campo de senha;
* Botão **Entrar**.

### 2. Tela Inicial

Apresenta um resumo das informações do sistema.

**Elementos principais:**

* Próximas Santas Missas;
* Quantidade de intenções cadastradas;
* Acesso ao cadastro de nova intenção;
* Acesso à lista de intenções;
* Aviso sobre nomes repetidos.

### 3. Tela de Cadastro de Intenção

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

### 4. Tela de Consulta das Intenções

Permite visualizar e localizar as intenções cadastradas.

A consulta poderá ser realizada por:

* Nome;
* Missa.

### 5. Tela de Nomes Repetidos

Permite identificar quando o mesmo nome aparece em mais de uma intenção cadastrada.

Essa funcionalidade foi incluída a partir da necessidade identificada durante o levantamento de requisitos.

## Modelagem

O projeto possui um **Diagrama de Caso de Uso**, representando as principais interações do usuário responsável pela secretaria com o sistema.

Entre as principais funcionalidades estão:

* Acesso ao sistema;
* Cadastro de intenção;
* Consulta de intenções;
* Gerenciamento das intenções;
* Identificação de nomes repetidos.

##  Sustentabilidade

A proposta considera o uso consciente de recursos por meio da organização digital das informações.

A utilização de um sistema pode contribuir para reduzir a necessidade de registros físicos e impressões desnecessárias, além de facilitar a consulta e o armazenamento das informações.



##  Validação do protótipo

Após a elaboração do protótipo, as telas deverão ser apresentadas ao responsável pela secretaria paroquial que participou do levantamento.

A validação será realizada por meio de três perguntas:

1. As telas são fáceis de entender e utilizar?
2. A visualização das intenções de cada missa seria útil para a secretaria?
3. A identificação de nomes repetidos ajudaria na organização das intenções?

As respostas serão utilizadas para verificar se o protótipo atende às necessidades identificadas durante a pesquisa.



## Documentação

O projeto contém a documentação referente ao levantamento e à especificação dos requisitos, incluindo:

* Introdução;
* Objetivos;
* Levantamento de requisitos;
* Requisitos funcionais;
* Requisitos não funcionais;
* Usuário do sistema;
* Diagrama de Caso de Uso;
* Protótipo de interface;
* Validação do protótipo;
* Sustentabilidade;
* Resultados esperados;
* Conclusão.

##  Estrutura sugerida do repositório

```text
Projeto-Integrador-II-B/
│
├── README.md
├── Documentação/
│   └── Projeto-Integrador-II-B.pdf
│
├── Protótipo/
│   ├── Tela-Login.png
│   ├── Tela-Inicial.png
│   ├── Tela-Cadastro.png
│   ├── Tela-Consulta.png
│   └── Tela-Nomes-Repetidos.png
│
└── Projeto-Integrador-II-B.zip
```
**Projeto:** Projeto Integrador II-B
**Ano:** 2026
