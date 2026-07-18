# Segurança

Esta política vale para os repositórios da organização `Msc-Company-Org`.

## Relato de vulnerabilidade

Não abra issue pública contendo vulnerabilidade, credencial ou dado de cliente. Envie o relato por canal privado ao responsável, incluindo repositório, impacto e passos mínimos para reprodução.

## Regras básicas

- nunca versionar `.env` real, tokens, chaves privadas ou bancos locais;
- não incluir dados pessoais ou documentos de clientes sem autorização;
- usar `.env.example` somente com valores fictícios;
- revogar imediatamente qualquer segredo exposto e depois remover o valor do histórico.
