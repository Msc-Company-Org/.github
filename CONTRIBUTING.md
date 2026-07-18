# Contribuindo

O processo da MSC Company é deliberadamente leve.

## Fluxo

1. Parta de `main` atualizado.
2. Use uma branch curta: `feat/*`, `fix/*`, `docs/*` ou `chore/*`.
3. Faça commits pequenos seguindo Conventional Commits.
4. Rode os checks existentes no repositório.
5. Abra PR para mudanças relevantes, arriscadas ou colaborativas.

Correções pequenas, reversíveis e de baixo risco podem ir direto para `main`, desde que o CI permaneça verde.

## Issues

Abra issue quando o trabalho precisar sobreviver à sessão atual, tiver dependências ou exigir acompanhamento. Ajustes imediatos não precisam de issue.

## Pull requests

Explique objetivo, impacto e como validar. Revisão humana é recomendada, não obrigatória para trabalho individual. CI existente deve passar antes do merge.

## Segurança

Nunca versione segredos, `.env` real, dados pessoais, bancos locais ou documentos de cliente sem autorização. Use nomes de variáveis e valores fictícios em `.env.example`.
