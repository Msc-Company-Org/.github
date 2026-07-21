# Governança da MSC Company

Este repositório concentra os padrões compartilhados pelos projetos da organização [Msc-Company-Org](https://github.com/Msc-Company-Org).

> Ele não contém um produto. Seu papel é tornar contribuição, segurança e comunicação consistentes em todos os monorepos.

## Visão geral

| Item | Definição |
|---|---|
| Status | Ativo |
| Tipo | Governança organizacional |
| Escopo | Todos os repositórios da MSC Company |
| Branch principal | `main` |

## Monorepos oficiais

| Repositório | Responsabilidade |
|---|---|
| [MSC Academy](https://github.com/Msc-Company-Org/msc-academy) | Educação e plataformas de aprendizagem |
| [MSC Consultoria](https://github.com/Msc-Company-Org/msc-consultoria) | Produtos, sites e operações de clientes |
| [Recanto do Açaí](https://github.com/Msc-Company-Org/recanto-acai) | Delivery, eventos e operação do Recanto |
| [MSC Labs](https://github.com/Msc-Company-Org/msc-labs) | IA, modelos, avaliações e infraestrutura |
| [Alexandria](https://github.com/Msc-Company-Org/alexandria) | Conhecimento, documentação e decisões |

## O que este repositório fornece

- `profile/README.md`: apresentação pública da organização;
- `CONTRIBUTING.md`: fluxo comum de contribuição;
- `SECURITY.md`: política de reporte e tratamento de vulnerabilidades;
- `PULL_REQUEST_TEMPLATE.md`: contexto mínimo esperado em pull requests;
- `.github/ISSUE_TEMPLATE/`: modelos para bugs e melhorias;
- `.github/workflows/ci.yml`: validação do próprio repositório de governança.

## Fluxo de contribuição

1. Crie uma branch curta a partir da `main`.
2. Explique objetivo, impacto e validação no pull request.
3. Não versiona segredos, credenciais ou dados pessoais.
4. Execute os testes relevantes ao repositório alterado.
5. Exclua a branch após o merge.

## Princípios de documentação

A documentação deve ser:

- legível por pessoas que ainda não conhecem o projeto;
- objetiva, com propósito e estado visíveis no início;
- dividida em seções curtas e bem espaçadas;
- descritiva o suficiente para orientar execução e decisões;
- vinculada à Alexandria quando representar conhecimento transversal.

## Segurança

Vulnerabilidades não devem ser publicadas em issues abertas. Consulte [SECURITY.md](SECURITY.md) para o canal correto.
