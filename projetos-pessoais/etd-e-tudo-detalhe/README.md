# ETD: É Tudo Detalhe

> Marca de moda feminina que estou construindo como um sistema: infraestrutura, dados e governança antes do produto.

## O que construí

- Monorepo com pnpm, reunindo o site, os tokens de design e as ferramentas internas em um único repositório.
- Banco de dados no Supabase (PostgreSQL), com o esquema evoluindo por migrações SQL versionadas.
- Pipeline de dados que coleta imagens de domínio público pela API do Rijksmuseum (licença CC0).
- Geração de imagens por IA (fal.ai), com armazenamento no Cloudflare R2.
- Integração contínua no GitHub Actions: geração automática dos tokens de design e scripts que validam a integridade da documentação a cada envio.
- Hooks do Git versionados no repositório: o pre-push bloqueia o envio se alguma validação falhar.
- Governança documentada: decisões registradas em ADRs (Architecture Decision Records), backlog vivo e commits atômicos.
- Agentes de IA com permissões restritas por função. Por exemplo, o agente executa commits, mas não pode publicar no repositório remoto.

## Tecnologias

TypeScript · Node.js · pnpm · Supabase (PostgreSQL) · GitHub Actions · Cloudflare R2 · Vercel · fal.ai

## Status

Em desenvolvimento. O código está em repositório privado.
