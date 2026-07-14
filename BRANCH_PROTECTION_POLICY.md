# Política de Proteção de Branches

Aplica-se aos repositórios `active` e `canonical` da organização.

## Regras mínimas para `main`

- mudanças somente por pull request;
- pelo menos uma aprovação;
- conversas de revisão resolvidas;
- branch atualizada antes do merge;
- CI obrigatório com typecheck, lint, testes e build quando aplicável;
- scan de segredos obrigatório;
- force push bloqueado;
- exclusão da branch bloqueada;
- administradores sujeitos às mesmas regras em projetos de produção.

## Exceções

Repositórios `experimental` podem exigir apenas CI e scan de segredos. Exceções devem ser registradas em ADR ou issue.

## Repositórios prioritários

1. `msc-ai`
2. `msc-mcp-core`
3. `msc-operations`
4. `msc-workspace-os`
5. `msc-marketing`
6. `recanto-acai`
7. `msc-labs-site`

## Tamanho e escopo de PR

- preferir mudanças pequenas e focadas;
- banco, segurança e infraestrutura devem ser isolados;
- PRs grandes devem conter plano de revisão por trilhas;
- código gerado não deve mascarar o tamanho da alteração manual.

## Merge

Padrão recomendado: squash merge para funcionalidades e correções. Merge commit é permitido para consolidação de históricos ou monorepos quando houver justificativa.
