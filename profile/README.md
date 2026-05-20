# Projeto JL Serralheria

Organização criada para centralizar os repositórios do projeto desenvolvido na disciplina de Arquitetura e Projeto de Software da Universidade Católica de Santos.

## Sobre o projeto

O projeto consiste no desenvolvimento de um aplicativo para apoiar uma serralheria no cadastro de clientes, produtos, serviços e orçamentos.

A aplicação tem como objetivo permitir que a serralheria organize seus dados principais, crie orçamentos com produtos, serviços e itens manuais, calcule valores automaticamente e gere um PDF do orçamento para envio ao cliente.

## Repositórios da organização

| Repositório | Descrição |
|---|---|
| projeto-jl-serralheria | Aplicativo principal desenvolvido em Flutter |
| modelo-uml | Repositório com os diagramas UML do projeto |

## Organização do projeto

O projeto está dividido em repositórios para separar o código-fonte da aplicação dos artefatos de modelagem.

### projeto-jl-serralheria

Contém o aplicativo principal, incluindo:

- Cadastro de clientes
- Cadastro de produtos
- Cadastro de serviços
- Criação de orçamentos
- Listagem de orçamentos
- Detalhamento de orçamento
- Geração de PDF

### modelo-uml

Contém os diagramas utilizados para representar as principais partes do sistema, principalmente para apoio durante a apresentação.

Diagramas previstos:

- Diagrama de Caso de Uso
- Diagrama de Componentes
- Diagrama de Implantação

## Participantes

| Nome | E-mail institucional |
|---|---|
| GABRIEL FUJII | gabriel.fujii@unisantos.br |
| BRENO OLIVEIRA  | b.severino@unisantos.br |
| FELIPE SHINZATO  | shinzato@unisantos.br |
| DANIEL THALYS | dthalys@unisantos.br |
| JOÃO VITOR TEODORO  | joaonascimento@unisantos.br |

## Fluxo de desenvolvimento

O desenvolvimento será organizado utilizando branches e Pull Requests.

Branches principais:

- `main`: versão final e estável do projeto
- `develop`: branch de integração das funcionalidades
- `feature/clientes`: desenvolvimento do módulo de clientes
- `feature/produtos-servicos`: desenvolvimento do módulo de produtos e serviços
- `feature/orcamentos`: desenvolvimento do módulo de orçamentos
- `feature/pdf-documentacao`: geração de PDF, testes, prints e documentação

## Regras de contribuição

Antes de iniciar uma nova tarefa:

```bash
git checkout develop
git pull
git checkout -b feature/nome-da-tarefa

